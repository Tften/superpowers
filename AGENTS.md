# Superpowers 个人特调版 — 维护指南

本仓库是基于 [obra/superpowers](https://github.com/obra/superpowers) 的**个人定制版本**:

- 仅支持 **OpenCode**(V1 + V2),其他 harness 的适配层已全部移除
- 与上游彻底独立,不维护同步能力,不向上游提交 PR
- 保留上游全部技能内容与设计档案,作为定制的基础
- 已删除 subagent-driven-development 与 dispatching-parallel-agents(本环境工作流为纯 Inline,禁用 Subagent);executing-plans 继承了 SDD 的 workspace/ledger 脚本

## 如果你是 AI Agent

在本仓库工作前,先了解以下约束:

1. **技能是行为塑造代码,不是散文。** `skills/` 下的内容(Red Flags 表、合理化清单、"your human partner" 措辞等)经过上游大量实测调优。修改任何技能内容前,先读 `docs/superpowers/specs/` 下对应的设计文档;没有明确的改进证据,不要"顺手"重写、重排或"规范化"这些内容。
2. **不要重新引入多 harness 支持。** 删除的插件目录(`.claude-plugin/`、`.codex-plugin/` 等)是有意移除的,个人版只跑 OpenCode。
3. **零依赖原则。** 不给核心技能引入第三方依赖;领域特定的功能应该独立成技能或脚本,而不是往上游结构里塞。
4. **设计档案是唯一依据。** "为什么这样设计"的答案在 `docs/superpowers/specs/`(20 份 spec)和 `docs/superpowers/plans/`(16 份 plan)里,不要凭直觉推翻有档案支撑的决策。

## 仓库结构

| 路径 | 内容 |
|---|---|
| `skills/` | 12 个技能本体(纯 Inline 工作流),是仓库的核心资产 |
| `.opencode/plugins/superpowers.js` | OpenCode 插件逻辑(bootstrap 注入 + 技能注册,内嵌工具映射) |
| `index.js` | OpenCode V2 目录形式插件入口(re-export superpowers.js) |
| `scripts/` | `lint-shell.sh`(shell lint)、`bump-version.sh`(版本同步) |
| `docs/superpowers/` | 上游设计档案(specs + plans),只读参考 |
| `docs/testing.md` | 测试设施说明 |
| `tests/` | 非 LLM 测试(opencode、shell-lint 等) |
| `graphify-out/` | 代码库知识图谱(见下) |

## 测试

```bash
# OpenCode 插件测试(Windows 下 2 个用例因 symlink/tmp 路径问题固有问题失败)
bash tests/opencode/run-tests.sh

# 其余静态套件
bash tests/shell-lint/test-lint-shell.sh
bash tests/diagnosing-superpowers/test-skill-structure.sh
bash tests/systematic-debugging/test-find-polluter.sh
bash tests/version-bump/test-bump-version.sh      # 本机缺 jq,基线即失败
```

改动 `skills/` 或插件代码后,至少跑相关的套件确认无回归。

## 版本管理

版本号在 `package.json`,由 `.version-bump.json` 声明、`scripts/bump-version.sh` 同步:

```bash
scripts/bump-version.sh --check   # 查看当前版本
scripts/bump-version.sh 6.5.0     # 升版本
```

## 知识图谱(graphify-out/)

仓库带有 graphify 知识图谱,用于结构化理解代码库:

- 修改代码后增量更新:`graphify --update`(`D:\documents\98_project\graphify_install` 环境)
- 自然语言查询:`graphify query "<问题>"`
- 交互式图谱:`graphify-out/graph.html`

技能内容大改后建议重建图谱,并在会话中用查询验证改动影响面。

## 提交约定

分支:`fea/*`(功能)、个人维护无 PR 流程。提交信息风格沿用上游:`type: 描述`(如 `docs: 图谱初始化`、`feat: ...`、`fix: ...`)。一次提交聚焦一件事。

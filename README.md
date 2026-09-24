# Superpowers(个人特调版)

基于 [obra/superpowers](https://github.com/obra/superpowers) 的个人定制版本:一套完整的软件开发方法论,以可组合的技能形式注入 coding agent,让 agent 在正确的时机自动执行正确的流程。

本仓库与上游的差异:

- **仅支持 OpenCode** —— 已移除 Claude Code / Codex / Gemini / Pi 等其他 harness 的全部适配层
- **彻底独立** —— 不维护与上游的同步能力,不向上游提交 PR
- **保留全部 16 个技能** 与完整的设计档案(`docs/superpowers/`),用于理解"为什么这样设计"

## 工作原理

从启动 coding agent 的那一刻开始工作。当你想构建某个东西时,它*不会*直接动手写代码,而是退后一步,先弄清你真正想做什么。

它会通过对话逐步提炼出规格说明,并分成足够短的段落呈现给你阅读和确认。

设计签字确认后,agent 会制定一份实施计划——清晰到一位热情但缺乏判断力、没有项目上下文、厌恶测试的初级工程师也能照着执行。计划强调真正的红/绿 TDD、YAGNI 和 DRY。

你说"开始"之后,进入 *subagent-driven-development* 流程:每个工程任务由独立的 subagent 执行,每个任务完成后接受审查,然后继续推进。agent 常常可以在不偏离计划的前提下自主工作数小时。

技能自动触发,无需手动操作。你的 coding agent 天生就有 Superpowers。

## 安装(OpenCode V2)

OpenCode 需要 2.0.4 或更高版本。本地安装时,把本仓库目录(含 `index.js`)配置到 opencode.json:

```json
{
  "plugins": ["D:/documents/98_project/superpowers"]
}
```

重启 OpenCode 后生效。验证方式:新开会话,问 "Tell me about your superpowers"。

详见 [docs/README.opencode.md](docs/README.opencode.md) 与 [.opencode/INSTALL.md](.opencode/INSTALL.md)。

## 基本工作流

1. **brainstorming** —— 写代码前激活。通过提问打磨粗略想法,探索备选方案,分段呈现设计供确认,保存设计文档。
2. **using-git-worktrees** —— 设计确认后激活。在新分支上创建隔离工作区,执行项目初始化,验证干净的测试基线。
3. **writing-plans** —— 有了批准的设计后激活。把工作拆成小任务(每个 2-5 分钟),每个任务都有精确的文件路径、完整代码和验证步骤。
4. **subagent-driven-development** 或 **executing-plans** —— 有了计划后激活。前者每个任务派发全新 subagent 并逐一审查(最彻底);后者在当前会话内联执行全部任务,最后对整个分支做一次全新审查(最省)。
5. **test-driven-development** —— 实施期间激活。强制 RED-GREEN-REFACTOR:写失败测试、看着它失败、写最小实现、看着它通过、提交。删除先于测试编写的代码。
6. **requesting-code-review** —— 任务之间激活。对照计划审查,按严重程度报告问题,关键问题阻塞推进。
7. **finishing-a-development-branch** —— 任务完成后激活。验证测试,呈现选项(合并/保留/丢弃),清理 worktree。

**agent 在执行任何任务前都会检查相关技能。** 这是强制工作流,不是建议。

## 出问题时

会话行为异常(技能误触发、该触发时沉默、agent 无视计划、重复劳动、token 消耗异常)时,对 agent 说"figure out what went wrong with superpowers in this session",它会调用 **diagnosing-superpowers** 技能。也可以指定历史会话:"figure out what went wrong with superpowers in session `<id>`"。

该技能会读取会话记录,给出带行号证据的分析报告。

## 内容清单

### 技能库

**测试**
- **test-driven-development** —— RED-GREEN-REFACTOR 循环(含测试反模式参考)

**调试**
- **systematic-debugging** —— 四阶段根因分析流程(含 root-cause-tracing、defense-in-depth、condition-based-waiting 技术)
- **verification-before-completion** —— 确认它真的修好了
- **diagnosing-superpowers** —— 用证据分析会话哪里出了问题

**协作**
- **brainstorming** —— 苏格拉底式设计打磨
- **writing-plans** —— 详细的实施计划
- **executing-plans** —— 内联执行计划:一个上下文,一次终审
- **dispatching-parallel-agents** —— 并发 subagent 工作流
- **requesting-code-review** —— 预审查清单
- **receiving-code-review** —— 回应审查反馈
- **using-git-worktrees** —— 并行开发分支
- **finishing-a-development-branch** —— 合并/丢弃决策流程
- **subagent-driven-development** —— 两阶段审查的快速迭代(先规格合规,后代码质量)

**元技能**
- **writing-skills** —— 按最佳实践创建新技能(含测试方法论)
- **using-superpowers** —— 技能系统入门

## 哲学

- **测试驱动开发** —— 永远先写测试
- **系统化优于临时起意** —— 流程优于猜测
- **降低复杂度** —— 简洁是首要目标
- **证据优于断言** —— 先验证再宣布成功

上游原始发布公告:[Superpowers: Tools for a new age of software development](https://blog.fsck.com/2025/10/09/superpowers/)。

## 维护

本仓库的个人维护指南见 [AGENTS.md](AGENTS.md)。设计决策的完整档案见 `docs/superpowers/specs/` 与 `docs/superpowers/plans/`——修改任何技能前,先读对应的设计文档。

## 许可

MIT License —— 见 LICENSE 文件。基于 obra/superpowers,版权归上游作者所有。

## 可视化伴侣遥测

brainstorming 的可视化伴侣默认从 Prime Radiant 网站加载 logo(仅含版本号,不含项目/提示词/agent 信息)。如需禁用,设置环境变量 `SUPERPOWERS_DISABLE_TELEMETRY` 为任意真值。

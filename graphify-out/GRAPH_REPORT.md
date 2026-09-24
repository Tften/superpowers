# Graph Report - superpowers  (2026-09-25)

## Corpus Check
- 105 files · ~151,737 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 564 nodes · 827 edges · 45 communities (26 shown, 19 thin omitted)
- Extraction: 89% EXTRACTED · 10% INFERRED · 0% AMBIGUOUS · INFERRED: 86 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- 个人版维护指南
- 技能测试方法档案
- 技能改进反馈档案
- Codex 兼容设计档案
- TDD 与好测试原则
- 会话诊断规则
- OpenCode 插件集成
- 可视化头脑风暴档案
- opencode 测试环境
- 行为准则与 OpenCode 指南
- 事件模型与检查点
- 系统化调试案例
- 分支完成与 Handoff 档案
- 零依赖服务器档案
- Bootstrap 映射测试
- 版本管理 CLI
- 插件入口与缓存
- 头脑风暴三路径
- Shell 脚本 Lint
- Lint 脚本测试
- Python 测试夹具
- find-polluter 测试
- package.json 清单
- 品牌图标资产
- 视觉伴侣实现档案
- Hermes 版本接线实现
- Hermes 版本接线设计
- 执行计划脚本
- opencode run-tests
- session-bootstrap 测试
- Logo SVG 资产
- Lean Context 选项档案
- E2E 流程卫生档案
- 交接自省档案
- Auth 共享夹具档案
- 只读评审规则档案
- Exercise the Real Thing 档案
- Name the Break 档案
- 原生 Worktree 工具档案
- Lean Context 选项档案
- E2E 流程卫生档案
- 交接自省档案
- Auth 共享夹具档案
- 只读评审规则档案
- Exercise the Real Thing 档案

## God Nodes (most connected - your core abstractions)
1. `diagnosing-superpowers (SKILL.md)` - 30 edges
2. `executing-plans SKILL.md — 在当前会话内联执行实施计划` - 25 edges
3. `README.md — Superpowers(个人特调版)项目说明` - 17 edges
4. `AGENTS.md — Superpowers 个人特调版维护指南` - 16 edges
5. `writing-plans SKILL.md — 有了规格/需求后、动代码之前编写实施计划` - 15 edges
6. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
7. `Diagnosing Superpowers Skill Implementation Plan` - 13 edges
8. `Strict-Cost SDD Design (spec)` - 12 edges
9. `原则 2:每个测试锻炼真实对象(Exercise the Real Thing)` - 11 edges
10. `Triage (workflow step 3)` - 11 edges

## Surprising Connections (you probably didn't know these)
- `obra/superpowers(上游仓库)` --semantically_similar_to--> `obra/superpowers(上游仓库)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `仅支持 OpenCode(已移除 Claude Code/Codex/Gemini/Pi 等其他 harness 适配层)` --semantically_similar_to--> `仅支持 OpenCode(V1+V2),多 harness 适配层已全部移除`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `个人特调版:一套完整软件开发方法论,以可组合技能形式注入 coding agent` --semantically_similar_to--> `个人定制版仓库(基于 obra/superpowers,与上游彻底独立)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `技能清单:11 个技能(测试1/调试3/协作6/元技能1)` --semantically_similar_to--> `skills/ — 11 个技能本体(纯 Inline 工作流,仓库核心资产)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `finishing-a-development-branch — 任务完成后激活,验证测试,呈现合并/保留/丢弃选项` --semantically_similar_to--> `收尾子技能:superpowers:finishing-a-development-branch`  [INFERRED] [semantically similar]
  README.md → skills/executing-plans/SKILL.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Diagnosing-Superpowers Analyst Prompt Suite** — docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill, skills_diagnosing_superpowers_prompts_analyst_common, skills_diagnosing_superpowers_prompts_cost_and_time, skills_diagnosing_superpowers_prompts_plan_adherence, skills_diagnosing_superpowers_prompts_quality_evidence, skills_diagnosing_superpowers_prompts_repeated_work, skills_diagnosing_superpowers_prompts_request_conflicts [EXTRACTED 1.00]
- **Cross-Platform Shared-Core Architecture** — docs_plans_2025_11_22_opencode_support_design, docs_plans_2025_11_22_opencode_support_implementation, lib_skills_core, _opencode_plugin_superpowers, _codex_superpowers_codex [EXTRACTED 1.00]
- **Platform-Neutral Migration Phases A B C** — docs_superpowers_specs_2026_05_05_platform_neutral_prose_design_phase_a_replacement_style, docs_superpowers_specs_2026_05_05_platform_neutral_config_refs_design_phase_b_substitution_rules, docs_superpowers_specs_2026_05_05_platform_neutral_readme_design_phase_c_alphabetical_ordering [EXTRACTED 1.00]
- **Systematic Debugging Supporting Techniques** — skills_systematic_debugging_skill, skills_systematic_debugging_root_cause_tracing, skills_systematic_debugging_defense_in_depth, skills_systematic_debugging_condition_based_waiting [EXTRACTED 1.00]
- **Visual Companion Auth Hardening Security Layer** — docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_bootstrap_keyed_loads, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_session_storage_key, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_websocket_same_origin_enforcement, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_files_containment, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_leak_reduction_headers [EXTRACTED 1.00]
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_plans_2026_07_30_codex_efficiency_fixes_hypothesis_log, docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill [INFERRED 0.85]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]

## Communities (45 total, 19 thin omitted)

### Community 0 - "个人版维护指南"
Cohesion: 0.06
Nodes (67): 提交约定(fea/* 分支,个人维护无 PR 流程,'type: 描述'风格), 设计档案是唯一依据(docs/superpowers/specs 20 份 + plans 16 份), AGENTS.md — Superpowers 个人特调版维护指南, 纯 Inline 工作流(禁用 Subagent), graphify-out/ — 代码库知识图谱(--update 增量更新、query 自然语言查询、graph.html 交互式图谱), 仅支持 OpenCode(V1+V2),多 harness 适配层已全部移除, .opencode/plugins/superpowers.js — OpenCode 插件逻辑(bootstrap 注入+技能注册,内嵌工具映射), 个人定制版仓库(基于 obra/superpowers,与上游彻底独立) (+59 more)

### Community 1 - "技能测试方法档案"
Cohesion: 0.08
Nodes (47): Bash Test Deletion Gate, Lift Drill into superpowers as evals/ Design (spec), Drill Skill-Compliance Benchmark, evals/ Canonical Eval Harness, Subagent-Gated Verification Protocol, SUPERPOWERS_ROOT Auto-Default, Cannot-Verify-From-Diff Channel, code-quality-reviewer-prompt.md (+39 more)

### Community 2 - "技能改进反馈档案"
Cohesion: 0.10
Nodes (37): diagnosing-superpowers (SKILL.md), prompts/analyst-common.md, Approval gates (hard rule), templates/bundle-README.md, templates/case.md, Case workspace (~/.superpowers/diagnosing-superpowers/<session-id>/), cost-and-time analyst dimension (prompts/cost-and-time.md), Dispatch or inline (hard rule) (+29 more)

### Community 3 - "Codex 兼容设计档案"
Cohesion: 0.07
Nodes (31): Real-World Debugging Session (2025-10-03), Skills Improvements from User Feedback, Configuration Change Verification, Mock-Interface Drift Anti-Pattern, Skill: finishing-a-development-branch, Skill: receiving-code-review, code-reviewer.md (review template), requesting-code-review (skill) (+23 more)

### Community 4 - "TDD 与好测试原则"
Cohesion: 0.10
Nodes (28): Diagnosed Session Case File, Diagnosing Superpowers Skill Implementation Plan, Transcript Context Safety Rules, Per-Harness Reference Files, No-Diagnosis Reporting Rule, Scrub Pipeline (scrub plus scrub-audit), analyst-common.md Shared Analyst Prompt Header, references/context-safety.md (+20 more)

### Community 5 - "会话诊断规则"
Cohesion: 0.11
Nodes (27): superpowers-codex CLI Script, Installing Superpowers for OpenCode, OpenCode Tool Mapping, superpowers.js OpenCode Plugin, OpenCode Support Design, find_skills Custom Tool, session.started Bootstrap Hook, Skill Shadowing (personal skills override core skills) (+19 more)

### Community 6 - "OpenCode 插件集成"
Cohesion: 0.15
Nodes (25): Visual Brainstorming Refactor Implementation Plan, brainstorm-server (lib/brainstorm-server), Browser Displays, Terminal Commands Model, Visual Brainstorming Refactor Design (spec), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar (+17 more)

### Community 7 - "可视化头脑风暴档案"
Cohesion: 0.11
Nodes (24): Worktree Rototill Implementation Plan, Native Tool Preference Rule, Provenance-Based Worktree Cleanup, Testing Skills Framework (RED/GREEN/PRESSURE), Lift Drill into Superpowers as evals Implementation Plan, drill Eval Harness (evals/drill), SUPERPOWERS_ROOT Default, SDD Task-Scoped Review Dispatch Implementation Plan (+16 more)

### Community 8 - "opencode 测试环境"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 9 - "行为准则与 OpenCode 指南"
Cohesion: 0.10
Nodes (23): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, Prime Radiant Community Code of Conduct, Superpowers for OpenCode Guide, OpenCode V1 Plugin Integration, OpenCode V2 Plugin API Integration, Platform-Neutral Config-File References Phase B Design (spec), Phase B Config-File Substitution Rules (+15 more)

### Community 10 - "事件模型与检查点"
Cohesion: 0.14
Nodes (16): brainstorm-server JS, superpowers-evals(外部 LLM 行为评测仓库), docs/testing.md — 测试设施说明, tests/opencode/ — OpenCode 插件测试, fail(), pass(), test-skill-structure.sh script, assert_contains() (+8 more)

### Community 11 - "系统化调试案例"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 12 - "分支完成与 Handoff 档案"
Cohesion: 0.16
Nodes (18): Zero-Dependency Brainstorm Server Implementation Plan, server.js Zero-Dependency Brainstorm Server, WebSocket Protocol Layer (RFC 6455 Frame Handling), Visual Brainstorming Companion Issue and Change Catalog, PID Ownership Check, Per-Session Secret Key Authentication, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI) (+10 more)

### Community 13 - "零依赖服务器档案"
Cohesion: 0.16
Nodes (18): 测行为,不测文本(Behavior, not text), 测你的边界契约,不测框架(Your code, not the framework), 完整镜像真实数据(Mirror real data completely), 原则 2:每个测试锻炼真实对象(Exercise the Real Thing), 门函数 2:加 mock 或测试辅助前的检查, 门函数 1:写测试体前的检查, 独立推导期望值(字面量与手工校验 fixture), mock 不配拥有断言(The mock earns no assertions) (+10 more)

### Community 14 - "Bootstrap 映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 15 - "版本管理 CLI"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 16 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _bootstrapCache, _cacheChildSession(), _childSessionCache, __dirname, extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup() (+4 more)

### Community 17 - "头脑风暴三路径"
Cohesion: 0.22
Nodes (14): brainstorming 技能 (SKILL.md), Architectural 路径, Bounded 路径, 设计文档约定 (docs/superpowers/specs/YYYY-MM-DD-<topic>-design.md), elements-of-style:writing-clearly-and-concisely 技能 (可选), HARD-GATE 实施前置门, 路径单向棘轮 (只能升级), Red Flags 表 (想法 vs 现实) (+6 more)

### Community 18 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 19 - "Lint 脚本测试"
Cohesion: 0.40
Nodes (9): assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell(), test-lint-shell.sh script (+1 more)

### Community 20 - "Python 测试夹具"
Cohesion: 0.29
Nodes (10): Consent-Authorization Bridge, Detect-and-Defer Worktree Strategy, Worktree Rototill Detect-and-Defer Design (spec), Worktree Hooks Symlinking, Provenance-Based Worktree Ownership, Step 0.5: Worktree Consent, Step 0: Detect Existing Isolation, Step 1a: Native Worktree Tools (preferred) (+2 more)

### Community 21 - "find-polluter 测试"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 22 - "package.json 清单"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 23 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Superpowers App Icon (app-icon.png, 2134x2134 square PNG), Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)

### Community 24 - "视觉伴侣实现档案"
Cohesion: 0.83
Nodes (4): Visual Brainstorming Companion Implementation Plan, Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Visual Companion Reference (visual-companion.md)

### Community 25 - "Hermes 版本接线实现"
Cohesion: 0.67
Nodes (3): Plan-Scoped SDD Workspace (.superpowers/sdd/<plan-basename>/), Superpowers v6.2.0 Release, writing-good-tests Reference Catalog

## Ambiguous Edges - Review These
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to
- `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` → `skills/ — 11 个技能本体(纯 Inline 工作流,仓库核心资产)`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to
- `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` → `技能清单:11 个技能(测试1/调试3/协作6/元技能1)`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to

## Knowledge Gaps
- **126 isolated node(s):** `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `checkpoint`, `childEvent`, `empty` (+121 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 193 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **19 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` and `skills/ — 11 个技能本体(纯 Inline 工作流,仓库核心资产)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` and `技能清单:11 个技能(测试1/调试3/协作6/元技能1)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `diagnosing-superpowers (SKILL.md)` connect `技能改进反馈档案` to `Codex 兼容设计档案`, `TDD 与好测试原则`?**
  _High betweenness centrality (0.068) - this node is a cross-community bridge._
- **Why does `diagnosing-superpowers skill` connect `行为准则与 OpenCode 指南` to `TDD 与好测试原则`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Why does `Diagnosing Superpowers Skill Implementation Plan` connect `TDD 与好测试原则` to `行为准则与 OpenCode 指南`?**
  _High betweenness centrality (0.053) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `diagnosing-superpowers (SKILL.md)` (e.g. with `Similar-Session Matcher Prompt (diagnosing-superpowers)` and `Skill Timeline Analyst Prompt (diagnosing-superpowers)`) actually correct?**
  _`diagnosing-superpowers (SKILL.md)` has 4 INFERRED edges - model-reasoned connections that need verification._
# Graph Report - superpowers  (2026-09-24)

## Corpus Check
- 3 files · ~170,323 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 570 nodes · 875 edges · 40 communities (27 shown, 13 thin omitted)
- Extraction: 88% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 99 edges (avg confidence: 0.86)
- Token cost: 5,400 input · 11,200 output

## Community Hubs (Navigation)
- 技能测试方法档案
- 基本工作流与核心技能
- 零依赖服务器档案
- 个人版维护指南
- Codex 兼容设计档案
- 会话诊断规则
- OpenCode 插件集成
- 行为准则与 OpenCode 指南
- opencode 测试环境
- 分支完成与 Handoff 档案
- 事件模型与检查点
- 系统化调试案例
- 好测试原则(writing-good-tests)
- Bootstrap 映射测试
- 版本管理 CLI
- 插件入口与缓存
- 头脑风暴三路径
- Shell 脚本 Lint
- Lint 脚本测试
- Python 测试夹具
- find-polluter 测试
- package.json 清单
- 诊断与结构测试
- 品牌图标资产
- 视觉伴侣实现档案
- Hermes 版本接线实现
- Hermes 版本接线设计
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
- 计划评审提示档案
- Spec 评审提示档案

## God Nodes (most connected - your core abstractions)
1. `executing-plans 技能(内联执行计划)` - 24 edges
2. `Superpowers 个人特调版(基于 obra/superpowers 的个人定制版)` - 20 edges
3. `executing-plans Skill` - 15 edges
4. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
5. `Systematic Debugging Skill` - 14 edges
6. `writing-plans 技能(实施计划编写)` - 14 edges
7. `内容清单·技能库(12 个技能:测试/调试/协作/元技能)` - 14 edges
8. `Diagnosing Superpowers Skill Implementation Plan` - 13 edges
9. `Strict-Cost SDD Design (spec)` - 12 edges
10. `SDD Fix-Loop Redesign Implementation Plan` - 11 edges

## Surprising Connections (you probably didn't know these)
- `Superpowers(个人特调版)— 注入 coding agent 的软件开发方法论技能集` --semantically_similar_to--> `Superpowers 个人特调版(基于 obra/superpowers 的个人定制版)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `obra/superpowers(上游项目)` --semantically_similar_to--> `obra/superpowers(上游仓库)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `仓库差异:仅支持 OpenCode` --semantically_similar_to--> `仅支持 OpenCode(V1 + V2)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `测试与实现一起交付(Tests ship with the implementation)` --conceptually_related_to--> `test-driven-development — RED-GREEN-REFACTOR 循环(含测试反模式参考)`  [INFERRED]
  skills/test-driven-development/writing-good-tests.md → README.md
- `OpenCode Tool Mapping` --conceptually_related_to--> `using-superpowers Skill`  [INFERRED]
  .opencode/INSTALL.md → docs/plans/2025-11-22-opencode-support-design.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Diagnosing-Superpowers Analyst Prompt Suite** — docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill, skills_diagnosing_superpowers_prompts_analyst_common, skills_diagnosing_superpowers_prompts_cost_and_time, skills_diagnosing_superpowers_prompts_plan_adherence, skills_diagnosing_superpowers_prompts_quality_evidence, skills_diagnosing_superpowers_prompts_repeated_work, skills_diagnosing_superpowers_prompts_request_conflicts [EXTRACTED 1.00]
- **Cross-Platform Shared-Core Architecture** — docs_plans_2025_11_22_opencode_support_design, docs_plans_2025_11_22_opencode_support_implementation, lib_skills_core, _opencode_plugin_superpowers, _codex_superpowers_codex [EXTRACTED 1.00]
- **Platform-Neutral Migration Phases A B C** — docs_superpowers_specs_2026_05_05_platform_neutral_prose_design_phase_a_replacement_style, docs_superpowers_specs_2026_05_05_platform_neutral_config_refs_design_phase_b_substitution_rules, docs_superpowers_specs_2026_05_05_platform_neutral_readme_design_phase_c_alphabetical_ordering [EXTRACTED 1.00]
- **Systematic Debugging Supporting Techniques** — skills_systematic_debugging_skill, skills_systematic_debugging_root_cause_tracing, skills_systematic_debugging_defense_in_depth, skills_systematic_debugging_condition_based_waiting [EXTRACTED 1.00]
- **Visual Companion Auth Hardening Security Layer** — docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_bootstrap_keyed_loads, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_session_storage_key, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_websocket_same_origin_enforcement, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_files_containment, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_leak_reduction_headers [EXTRACTED 1.00]
- **Per-Harness Platform Tool References** — docs_superpowers_plans_2026_03_23_codex_app_compatibility_codex_tools_reference, docs_superpowers_plans_2026_05_07_pi_extension_and_evals_pi_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_antigravity_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_gemini_tools_reference [INFERRED 0.85]
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_plans_2026_07_30_codex_efficiency_fixes_hypothesis_log, docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill [INFERRED 0.85]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]

## Communities (40 total, 13 thin omitted)

### Community 0 - "技能测试方法档案"
Cohesion: 0.05
Nodes (68): Bash Test Deletion Gate, subagent-driven-development skill, Platform-Neutral Config-File References Phase B Design (spec), Phase B Config-File Substitution Rules, Platform-Neutral Prose Phase A Design (spec), Phase A Agent-Neutral Prose Style, Claude Search Optimization to Skill Discovery Optimization Rename, writing-skills skill (+60 more)

### Community 1 - "基本工作流与核心技能"
Cohesion: 0.08
Nodes (45): 基本工作流(7 步强制流程), 哲学:测试驱动/系统化优于临时起意/降低复杂度/证据优于断言, brainstorming — 苏格拉底式设计打磨, executing-plans — 内联执行计划(一个上下文,一次终审), finishing-a-development-branch — 合并/保留/丢弃决策流程, 内容清单·技能库(12 个技能:测试/调试/协作/元技能), receiving-code-review — 回应审查反馈, requesting-code-review — 预审查清单 (+37 more)

### Community 2 - "零依赖服务器档案"
Cohesion: 0.08
Nodes (44): Visual Brainstorming Refactor Implementation Plan, Zero-Dependency Brainstorm Server Implementation Plan, server.js Zero-Dependency Brainstorm Server, WebSocket Protocol Layer (RFC 6455 Frame Handling), Visual Brainstorming Companion Issue and Change Catalog, PID Ownership Check, Per-Session Secret Key Authentication, Terminal vs HTML Approval Gate (+36 more)

### Community 3 - "个人版维护指南"
Cohesion: 0.07
Nodes (38): scripts/bump-version.sh — 版本同步脚本, 提交约定(fea/* 分支,type: 描述,一次提交聚焦一件事), 约束:设计档案是唯一依据, docs/superpowers/ — 上游设计档案(specs + plans,20 份 spec / 16 份 plan),只读参考, graphify-out/ — 代码库知识图谱, graphify 知识图谱工作流(--update / query / graph.html), index.js — OpenCode V2 目录形式插件入口(re-export superpowers.js), 纯 Inline 工作流(禁用 Subagent) (+30 more)

### Community 4 - "Codex 兼容设计档案"
Cohesion: 0.08
Nodes (39): Codex App Compatibility Implementation Plan, references/codex-tools.md, Detached HEAD Handoff to Bash, Codex App Environment Detection, Worktree Rototill Implementation Plan, Native Tool Preference Rule, Provenance-Based Worktree Cleanup, Testing Skills Framework (RED/GREEN/PRESSURE) (+31 more)

### Community 5 - "会话诊断规则"
Cohesion: 0.11
Nodes (28): Diagnosed Session Case File, Diagnosing Superpowers Skill Implementation Plan, Transcript Context Safety Rules, Per-Harness Reference Files, No-Diagnosis Reporting Rule, Scrub Pipeline (scrub plus scrub-audit), analyst-common.md Shared Analyst Prompt Header, references/context-safety.md (+20 more)

### Community 6 - "OpenCode 插件集成"
Cohesion: 0.11
Nodes (27): superpowers-codex CLI Script, Installing Superpowers for OpenCode, OpenCode Tool Mapping, superpowers.js OpenCode Plugin, OpenCode Support Design, find_skills Custom Tool, session.started Bootstrap Hook, Skill Shadowing (personal skills override core skills) (+19 more)

### Community 7 - "行为准则与 OpenCode 指南"
Cohesion: 0.11
Nodes (26): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, Prime Radiant Community Code of Conduct, Skills Improvements from User Feedback, Configuration Change Verification, Mock-Interface Drift Anti-Pattern, Superpowers for OpenCode Guide, OpenCode V1 Plugin Integration (+18 more)

### Community 8 - "opencode 测试环境"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 9 - "分支完成与 Handoff 档案"
Cohesion: 0.13
Nodes (23): Codex App Finishing Handoff Payload, codex-tools.md platform reference, Codex App Compatibility Design (spec), Read-Only Git Environment Detection, finishing-a-development-branch skill, IN_LINKED_WORKTREE Signal, ON_DETACHED_HEAD Signal, Sandbox Fallback Behavior (+15 more)

### Community 10 - "事件模型与检查点"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 11 - "系统化调试案例"
Cohesion: 0.13
Nodes (14): Real-World Debugging Session (2025-10-03), Condition-Based Waiting Technique, Defense-in-Depth Validation Technique, find-polluter.sh script, Root Cause Tracing Technique, Systematic Debugging Skill, Four-Phase Debugging Framework, The Iron Law: No Fixes Without Root Cause Investigation (+6 more)

### Community 12 - "好测试原则(writing-good-tests)"
Cohesion: 0.16
Nodes (18): 测行为,不测文本(Behavior, not text), 测你的边界契约,不测框架(Your code, not the framework), 完整镜像真实数据(Mirror real data completely), 原则 2:每个测试锻炼真实对象(Exercise the Real Thing), 门函数 2:加 mock 或测试辅助前的检查, 门函数 1:写测试体前的检查, 独立推导期望值(字面量与手工校验 fixture), mock 不配拥有断言(The mock earns no assertions) (+10 more)

### Community 13 - "Bootstrap 映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 14 - "版本管理 CLI"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 15 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _bootstrapCache, _cacheChildSession(), _childSessionCache, __dirname, extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup() (+4 more)

### Community 16 - "头脑风暴三路径"
Cohesion: 0.22
Nodes (14): brainstorming 技能 (SKILL.md), Architectural 路径, Bounded 路径, 设计文档约定 (docs/superpowers/specs/YYYY-MM-DD-<topic>-design.md), elements-of-style:writing-clearly-and-concisely 技能 (可选), HARD-GATE 实施前置门, 路径单向棘轮 (只能升级), Red Flags 表 (想法 vs 现实) (+6 more)

### Community 17 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 18 - "Lint 脚本测试"
Cohesion: 0.40
Nodes (9): assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell(), test-lint-shell.sh script (+1 more)

### Community 19 - "Python 测试夹具"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 20 - "find-polluter 测试"
Cohesion: 0.43
Nodes (6): assert_contains(), fail(), pass(), run_polluter(), setup_project(), test-find-polluter.sh script

### Community 21 - "package.json 清单"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 22 - "诊断与结构测试"
Cohesion: 0.47
Nodes (5): 会话异常诊断入口, diagnosing-superpowers — 用证据分析会话哪里出了问题, fail(), pass(), test-skill-structure.sh script

### Community 23 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Superpowers App Icon (app-icon.png, 2134x2134 square PNG), Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)

### Community 24 - "视觉伴侣实现档案"
Cohesion: 0.83
Nodes (4): Visual Brainstorming Companion Implementation Plan, Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Visual Companion Reference (visual-companion.md)

### Community 25 - "Hermes 版本接线实现"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Implementation Plan, Extension-Based Manifest Dispatcher (jq/yq), Preflight Manifest Reads

### Community 26 - "Hermes 版本接线设计"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Design (spec), Read-Only Preflight Manifest Validation, Hermes plugin.yaml Version-Bump YAML Wiring

## Ambiguous Edges - Review These
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to
- `skills/ — 12 个技能本体(纯 Inline 工作流),仓库核心资产` → `仓库差异:保留上游技能与完整设计档案`  [AMBIGUOUS]
  README.md · relation: references

## Knowledge Gaps
- **114 isolated node(s):** `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `checkpoint`, `childEvent`, `empty` (+109 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 176 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **13 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `skills/ — 12 个技能本体(纯 Inline 工作流),仓库核心资产` and `仓库差异:保留上游技能与完整设计档案`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **Why does `executing-plans Skill` connect `行为准则与 OpenCode 指南` to `分支完成与 Handoff 档案`, `OpenCode 插件集成`, `基本工作流与核心技能`?**
  _High betweenness centrality (0.278) - this node is a cross-community bridge._
- **Why does `Review Focus(审查焦点)` connect `基本工作流与核心技能` to `行为准则与 OpenCode 指南`?**
  _High betweenness centrality (0.224) - this node is a cross-community bridge._
- **Why does `Bash Test Deletion Gate` connect `技能测试方法档案` to `Codex 兼容设计档案`, `OpenCode 插件集成`?**
  _High betweenness centrality (0.168) - this node is a cross-community bridge._
- **What connects `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `checkpoint` to the rest of the system?**
  _114 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `技能测试方法档案` be split into smaller, more focused modules?**
  _Cohesion score 0.050921861281826165 - nodes in this community are weakly interconnected._
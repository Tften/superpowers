# Graph Report - superpowers  (2026-09-24)

## Corpus Check
- 0 files · ~0 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 577 nodes · 873 edges · 47 communities (35 shown, 12 thin omitted)
- Extraction: 88% EXTRACTED · 12% INFERRED · 0% AMBIGUOUS · INFERRED: 104 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- 事件模型与检查点
- 系统化调试案例
- 版本管理 CLI
- find-polluter 测试
- 可视化头脑风暴档案
- 个人版维护指南
- 只读评审规则档案
- Exercise the Real Thing 档案
- Name the Break 档案
- 原生 Worktree 工具档案
- OpenCode 插件集成
- 技能测试方法档案
- Bootstrap 映射测试
- Shell 脚本 Lint
- Hermes 版本接线设计
- 执行计划脚本
- session-bootstrap 测试
- 只读评审规则档案
- Exercise the Real Thing 档案
- Name the Break 档案
- 会话诊断规则
- 分支完成与 Handoff 档案
- 零依赖服务器档案
- 插件入口与缓存
- 头脑风暴三路径
- Lint 脚本测试
- 技能改进反馈档案
- Python 测试夹具
- package.json 清单
- 品牌图标资产
- 视觉伴侣实现档案
- Hermes 版本接线实现
- opencode run-tests
- Codex 兼容设计档案
- Logo SVG 资产
- Lean Context 选项档案
- E2E 流程卫生档案
- 交接自省档案
- Auth 共享夹具档案
- 原生 Worktree 工具档案
- Lean Context 选项档案
- TDD 与好测试原则
- E2E 流程卫生档案
- 交接自省档案
- Auth 共享夹具档案
- opencode 测试环境
- 行为准则与 OpenCode 指南

## God Nodes (most connected - your core abstractions)
1. `executing-plans (skill)` - 33 edges
2. `Superpowers 个人特调版(基于 obra/superpowers 的个人定制版)` - 20 edges
3. `内容清单·技能库(12 个技能:测试/调试/协作/元技能)` - 14 edges
4. `writing-plans 技能(实施计划编写)` - 14 edges
5. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
6. `Diagnosing Superpowers Skill Implementation Plan` - 13 edges
7. `requesting-code-review (skill)` - 12 edges
8. `Strict-Cost SDD Design (spec)` - 12 edges
9. `Verification Before Completion Skill` - 11 edges
10. `Systematic Debugging Skill` - 11 edges

## Surprising Connections (you probably didn't know these)
- `obra/superpowers(上游项目)` --semantically_similar_to--> `obra/superpowers(上游仓库)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `仓库差异:仅支持 OpenCode` --semantically_similar_to--> `仅支持 OpenCode(V1 + V2)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `Superpowers(个人特调版)— 注入 coding agent 的软件开发方法论技能集` --semantically_similar_to--> `Superpowers 个人特调版(基于 obra/superpowers 的个人定制版)`  [INFERRED] [semantically similar]
  README.md → AGENTS.md
- `OpenCode Tool Mapping` --conceptually_related_to--> `using-superpowers Skill`  [INFERRED]
  .opencode/INSTALL.md → docs/plans/2025-11-22-opencode-support-design.md
- `Native (Inline) Execution Mode for executing-plans` --references--> `executing-plans (skill)`  [EXTRACTED]
  RELEASE-NOTES.md → skills/executing-plans/SKILL.md

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

## Communities (47 total, 12 thin omitted)

### Community 10 - "事件模型与检查点"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 11 - "系统化调试案例"
Cohesion: 0.16
Nodes (10): find-polluter.sh script, Real-World Debugging Session (2025-10-03), Condition-Based Waiting Technique, Defense-in-Depth Validation Technique, Root Cause Tracing Technique, Systematic Debugging Skill, Four-Phase Debugging Framework, The Iron Law: No Fixes Without Root Cause Investigation (+2 more)

### Community 15 - "版本管理 CLI"
Cohesion: 0.22
Nodes (12): _cacheChildSession(), extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup(), SuperpowersPlugin(), _bootstrapCache, _childSessionCache (+4 more)

### Community 21 - "find-polluter 测试"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 7 - "可视化头脑风暴档案"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 0 - "个人版维护指南"
Cohesion: 0.06
Nodes (52): SDD Workspace and Ledger, Red-Green-Refactor TDD Cycle, Declined to Judge List, The Spec is a Vision Document, TDD Iron Law: No Production Code Without a Failing Test First, Red Flags / Common Rationalizations Pattern, Verification Gate Function, Verification Iron Law: No Completion Claims Without Fresh Verification Evidence (+44 more)

### Community 6 - "OpenCode 插件集成"
Cohesion: 0.13
Nodes (22): OpenCode Tool Mapping, superpowers-codex CLI Script, superpowers.js OpenCode Plugin, lib/skills-core.js Shared Skill Core Module, checkForUpdates, extractFrontmatter, findSkillsInDir, resolveSkillPath (+14 more)

### Community 1 - "技能测试方法档案"
Cohesion: 0.06
Nodes (47): assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell(), test-lint-shell.sh script (+39 more)

### Community 14 - "Bootstrap 映射测试"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 18 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 26 - "Hermes 版本接线设计"
Cohesion: 0.43
Nodes (6): assert_contains(), fail(), pass(), run_polluter(), setup_project(), test-find-polluter.sh script

### Community 27 - "执行计划脚本"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 29 - "session-bootstrap 测试"
Cohesion: 0.47
Nodes (5): fail(), pass(), test-skill-structure.sh script, 会话异常诊断入口, diagnosing-superpowers — 用证据分析会话哪里出了问题

### Community 5 - "会话诊断规则"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 12 - "分支完成与 Handoff 档案"
Cohesion: 0.23
Nodes (15): Per-Harness Reference Files, Scrub Pipeline (scrub plus scrub-audit), references/context-safety.md, references/redaction-policy.md, Diagnosing Superpowers Skill Implementation Plan, analyst-common.md Shared Analyst Prompt Header, cost-and-time.md Cost and Time Analyst Prompt, plan-adherence.md Plan Adherence Analyst Prompt (+7 more)

### Community 13 - "零依赖服务器档案"
Cohesion: 0.16
Nodes (15): Drill Skill-Compliance Benchmark, Cannot-Verify-From-Diff Channel, Micro-Test Harness for Prompt Guidance, writing-plans No Placeholders Section, L1 Plan-Side Crispness, L2 Controller Tier Experiment, L3 Reviewer Tier Experiment, L4 Resident-Context Diet (+7 more)

### Community 16 - "插件入口与缓存"
Cohesion: 0.22
Nodes (14): Architectural 路径, Bounded 路径, 设计文档约定 (docs/superpowers/specs/YYYY-MM-DD-<topic>-design.md), elements-of-style:writing-clearly-and-concisely 技能 (可选), HARD-GATE 实施前置门, 路径单向棘轮 (只能升级), Red Flags 表 (想法 vs 现实), 建立共识 (Establish Shared Understanding) (+6 more)

### Community 17 - "头脑风暴三路径"
Cohesion: 0.22
Nodes (13): subagent-driven-development skill, implementer-prompt.md, Strict-Cost Experiment Ladder, Controller Adjudication at Circuit-Breaker Trip, Fix-Loop Circuit Breaker, Excuse/Reality Rationalization Table, re-review-prompt.md, Scoped Re-Review (+5 more)

### Community 19 - "Lint 脚本测试"
Cohesion: 0.35
Nodes (12): SDD Durable Progress Ledger, Eval Fixture Generator v3, S1 Stale-Ledger Scenario, S2 Same-Plan Resume Scenario, Ledger Plan-Identity First Line, Plan-Scoped SDD Workspace, review-package Script, sdd-workspace Script (+4 more)

### Community 2 - "技能改进反馈档案"
Cohesion: 0.07
Nodes (46): 基本工作流(7 步强制流程), 哲学:测试驱动/系统化优于临时起意/降低复杂度/证据优于断言, brainstorming — 苏格拉底式设计打磨, executing-plans — 内联执行计划(一个上下文,一次终审), finishing-a-development-branch — 合并/保留/丢弃决策流程, 内容清单·技能库(12 个技能:测试/调试/协作/元技能), receiving-code-review — 回应审查反馈, requesting-code-review — 预审查清单 (+38 more)

### Community 20 - "Python 测试夹具"
Cohesion: 0.29
Nodes (10): Plan Document Reviewer, Spec Document Reviewer, evals/ Canonical Eval Harness, Subagent-Gated Verification Protocol, SUPERPOWERS_ROOT Auto-Default, Document Review System Implementation Plan, Document Review System Design (spec), Lift Drill into superpowers as evals/ Design (spec) (+2 more)

### Community 22 - "package.json 清单"
Cohesion: 0.31
Nodes (9): Phase B Config-File Substitution Rules, Claude Search Optimization to Skill Discovery Optimization Rename, writing-skills skill, Phase C README Alphabetical Ordering, diagnosing-superpowers skill, Platform-Neutral Config-File References Phase B Design (spec), Platform-Neutral Prose Phase A Design (spec), Platform-Neutral README Ordering Phase C Design (spec) (+1 more)

### Community 23 - "品牌图标资产"
Cohesion: 0.29
Nodes (8): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, OpenCode V1 Plugin Integration, OpenCode V2 Plugin API Integration, Native (Inline) Execution Mode for executing-plans, Prime Radiant Community Code of Conduct, Superpowers for OpenCode Guide, Superpowers v6.4.1 Release

### Community 24 - "视觉伴侣实现档案"
Cohesion: 0.36
Nodes (8): code-quality-reviewer-prompt.md, requesting-code-review/code-reviewer.md template, spec-reviewer-prompt.md, task-reviewer-prompt.md (merged spec and quality reviewer), Task-Scoped Review, SDD Task-Scoped Review Dispatch Design (spec), Reviewer Scope Budget, Reviewer Test Budget

### Community 25 - "Hermes 版本接线实现"
Cohesion: 0.29
Nodes (8): Context Safety Rules (diagnosing-superpowers), GitHub Issues Reference (diagnosing-superpowers), Redaction Policy (diagnosing-superpowers), Session Discovery Reference, Diagnosis Bundle README Template, Diagnosis Case File Template, Diagnosis Issue Template, Diagnosis Report Template

### Community 28 - "opencode run-tests"
Cohesion: 0.33
Nodes (6): path:line Finding Shape, Bundle Scrub and Independent Audit, Similar-Session Signature Search, Diagnosing Superpowers Sessions Design (spec), file:line Evidence Rule, Context-Safety Rules

### Community 3 - "Codex 兼容设计档案"
Cohesion: 0.08
Nodes (39): references/codex-tools.md, Detached HEAD Handoff to Bash, drill Eval Harness (evals/drill), SUPERPOWERS_ROOT Default, Transcript Log Normalization, Pi Backend (evals/drill Transcript Log and Event Stream), Pi Harness Extension, references/pi-tools.md (+31 more)

### Community 30 - "Logo SVG 资产"
Cohesion: 0.50
Nodes (5): Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg), Superpowers App Icon (app-icon.png, 2134x2134 square PNG)

### Community 31 - "Lean Context 选项档案"
Cohesion: 0.60
Nodes (5): codex-tools.md platform reference, T2: Event-Driven Waiting, T3: codex-tools.md V1/V2 Corrections, T5: Explicit Model on Child-Issued Spawns, Codex Efficiency Fixes Design (spec)

### Community 32 - "E2E 流程卫生档案"
Cohesion: 0.83
Nodes (4): Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Visual Brainstorming Companion Implementation Plan, Visual Companion Reference (visual-companion.md)

### Community 33 - "交接自省档案"
Cohesion: 1.00
Nodes (3): Extension-Based Manifest Dispatcher (jq/yq), Hermes Version-Bump Wiring Implementation Plan, Preflight Manifest Reads

### Community 34 - "Auth 共享夹具档案"
Cohesion: 1.00
Nodes (3): Read-Only Preflight Manifest Validation, Hermes plugin.yaml Version-Bump YAML Wiring, Hermes Version-Bump Wiring Design (spec)

### Community 4 - "TDD 与好测试原则"
Cohesion: 0.15
Nodes (25): brainstorm-server (lib/brainstorm-server), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar, visual-companion.md skill instructions, wait-for-feedback.sh (deleted script), wrapInFrame Comment-Placeholder Injection (+17 more)

### Community 8 - "opencode 测试环境"
Cohesion: 0.15
Nodes (19): server.js Zero-Dependency Brainstorm Server, PID Ownership Check, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI), WebSocket Origin Check, Bootstrap-Keyed Server Root, Strict Origin Enforcement, Realpath-Based Path Containment (/files/* Guard) (+11 more)

### Community 9 - "行为准则与 OpenCode 指南"
Cohesion: 0.18
Nodes (18): Codex App Finishing Handoff Payload, Read-Only Git Environment Detection, finishing-a-development-branch skill, IN_LINKED_WORKTREE Signal, ON_DETACHED_HEAD Signal, Sandbox Fallback Behavior, Worktree Hooks Symlinking, Step 0.5: Worktree Consent (+10 more)

## Ambiguous Edges - Review These
- `skills/ — 12 个技能本体(纯 Inline 工作流),仓库核心资产` → `仓库差异:保留上游技能与完整设计档案`  [AMBIGUOUS]
  README.md · relation: references
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to

## Knowledge Gaps
- **118 isolated node(s):** `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `afterFirst`, `afterSecond`, `firstOutput` (+113 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 182 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **12 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `skills/ — 12 个技能本体(纯 Inline 工作流),仓库核心资产` and `仓库差异:保留上游技能与完整设计档案`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `executing-plans (skill)` connect `个人版维护指南` to `技能改进反馈档案`, `OpenCode 插件集成`, `行为准则与 OpenCode 指南`, `系统化调试案例`, `品牌图标资产`?**
  _High betweenness centrality (0.310) - this node is a cross-community bridge._
- **Why does `Review Focus(审查焦点)` connect `技能改进反馈档案` to `个人版维护指南`?**
  _High betweenness centrality (0.201) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `内容清单·技能库(12 个技能:测试/调试/协作/元技能)` (e.g. with `skills/ — 12 个技能本体(纯 Inline 工作流),仓库核心资产` and `仓库差异:保留上游技能与完整设计档案`) actually correct?**
  _`内容清单·技能库(12 个技能:测试/调试/协作/元技能)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `afterFirst` to the rest of the system?**
  _118 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `事件模型与检查点` be split into smaller, more focused modules?**
  _Cohesion score 0.125 - nodes in this community are weakly interconnected._
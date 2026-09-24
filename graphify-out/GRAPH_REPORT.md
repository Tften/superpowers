# Graph Report - superpowers  (2026-09-24)

## Corpus Check
- 5 files · ~185,631 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 571 nodes · 873 edges · 39 communities (28 shown, 11 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 97 edges (avg confidence: 0.86)
- Token cost: 6,800 input · 14,800 output

## Community Hubs (Navigation)
- 文档评审系统设计档案
- 个人版维护指南
- Codex 兼容设计档案
- 技能改进反馈档案
- SDD 提示模板
- 可视化头脑风暴档案
- opencode 测试环境
- 行为准则与 OpenCode 指南
- OpenCode 插件集成
- 技能编写方法论
- 系统化调试案例
- 事件模型与检查点
- 零依赖服务器档案
- 分支完成与 Handoff 档案
- Bootstrap 映射测试
- 会话诊断规则
- 版本管理 CLI
- 插件入口与缓存
- Shell 脚本 Lint
- Lint 脚本测试
- Python 测试夹具
- find-polluter 测试
- package.json 清单
- 品牌图标资产
- 视觉伴侣实现档案
- 技能结构测试
- Hermes 版本接线实现
- Hermes 版本接线设计
- task-done 脚本
- task-start 脚本
- run-all 测试入口
- 扩展多轮测试
- haiku 模型测试
- 多轮对话测试
- 单测运行脚本
- opencode run-tests
- session-bootstrap 测试
- Logo SVG 资产
- 显式技能请求测试

## God Nodes (most connected - your core abstractions)
1. `README.md — Superpowers 个人特调版说明` - 26 edges
2. `Subagent-Driven Development Skill` - 23 edges
3. `writing-skills 技能 (SKILL.md)` - 20 edges
4. `executing-plans Skill` - 18 edges
5. `AGENTS.md — Superpowers 个人特调版维护指南` - 18 edges
6. `Systematic Debugging Skill` - 15 edges
7. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
8. `Diagnosing Superpowers Skill Implementation Plan` - 13 edges
9. `brainstorming 技能 (SKILL.md)` - 13 edges
10. `Strict-Cost SDD Design (spec)` - 12 edges

## Surprising Connections (you probably didn't know these)
- `OpenCode Tool Mapping` --conceptually_related_to--> `using-superpowers Skill`  [INFERRED]
  .opencode/INSTALL.md → docs/plans/2025-11-22-opencode-support-design.md
- `Subagent-Driven Development Skill` --implements--> `Lean Context Option for Subagent Dispatch`  [INFERRED]
  skills/subagent-driven-development/SKILL.md → docs/plans/2025-11-28-skills-improvements-from-user-feedback.md
- `Native (Inline) Execution Mode for executing-plans` --references--> `executing-plans Skill`  [EXTRACTED]
  RELEASE-NOTES.md → docs/plans/2025-11-22-opencode-support-implementation.md
- `executing-plans Skill` --conceptually_related_to--> `Skill: receiving-code-review`  [INFERRED]
  docs/plans/2025-11-22-opencode-support-implementation.md → skills/receiving-code-review/SKILL.md
- `executing-plans Skill` --references--> `SDD Workspace and Ledger`  [EXTRACTED]
  docs/plans/2025-11-22-opencode-support-implementation.md → skills/executing-plans/SKILL.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Code Review Dispatch Flow** — skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_executing_plans_skill, skills_requesting_code_review_code_reviewer_declined_to_judge, skills_requesting_code_review_code_reviewer_spec_vision_document [EXTRACTED 1.00]
- **Diagnosing-Superpowers Analyst Prompt Suite** — docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill, skills_diagnosing_superpowers_prompts_analyst_common, skills_diagnosing_superpowers_prompts_cost_and_time, skills_diagnosing_superpowers_prompts_plan_adherence, skills_diagnosing_superpowers_prompts_quality_evidence, skills_diagnosing_superpowers_prompts_repeated_work, skills_diagnosing_superpowers_prompts_request_conflicts [EXTRACTED 1.00]
- **Cross-Platform Shared-Core Architecture** — docs_plans_2025_11_22_opencode_support_design, docs_plans_2025_11_22_opencode_support_implementation, lib_skills_core, _opencode_plugin_superpowers, _codex_superpowers_codex [EXTRACTED 1.00]
- **Platform-Neutral Migration Phases A B C** — docs_superpowers_specs_2026_05_05_platform_neutral_prose_design_phase_a_replacement_style, docs_superpowers_specs_2026_05_05_platform_neutral_config_refs_design_phase_b_substitution_rules, docs_superpowers_specs_2026_05_05_platform_neutral_readme_design_phase_c_alphabetical_ordering [EXTRACTED 1.00]
- **SDD Per-Task Review Loop** — skills_subagent_driven_development_skill, skills_subagent_driven_development_implementer_prompt, skills_subagent_driven_development_task_reviewer_prompt, skills_subagent_driven_development_re_review_prompt, skills_subagent_driven_development_skill_fix_loop [EXTRACTED 1.00]
- **Superpowers Plan Execution Lifecycle** — skills_executing_plans_skill, skills_test_driven_development_skill, skills_verification_before_completion_skill, skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_finishing_a_development_branch_skill, skills_using_git_worktrees_skill [EXTRACTED 1.00]
- **Systematic Debugging Supporting Techniques** — skills_systematic_debugging_skill, skills_systematic_debugging_root_cause_tracing, skills_systematic_debugging_defense_in_depth, skills_systematic_debugging_condition_based_waiting [EXTRACTED 1.00]
- **Visual Companion Auth Hardening Security Layer** — docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_bootstrap_keyed_loads, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_session_storage_key, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_websocket_same_origin_enforcement, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_files_containment, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_leak_reduction_headers [EXTRACTED 1.00]
- **Explicit Skill Request Trigger Test Suite** — tests_explicit_skill_requests_prompts_action_oriented, tests_explicit_skill_requests_prompts_after_planning_flow, tests_explicit_skill_requests_prompts_claude_suggested_it, tests_explicit_skill_requests_prompts_i_know_what_sdd_means, tests_explicit_skill_requests_prompts_mid_conversation_execute_plan, tests_explicit_skill_requests_prompts_please_use_brainstorming, tests_explicit_skill_requests_prompts_skip_formalities, tests_explicit_skill_requests_prompts_subagent_driven_development_please, tests_explicit_skill_requests_prompts_use_systematic_debugging [INFERRED 0.85]
- **Per-Harness Platform Tool References** — docs_superpowers_plans_2026_03_23_codex_app_compatibility_codex_tools_reference, docs_superpowers_plans_2026_05_07_pi_extension_and_evals_pi_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_antigravity_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_gemini_tools_reference [INFERRED 0.85]
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_plans_2026_07_30_codex_efficiency_fixes_hypothesis_log, docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill [INFERRED 0.85]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]

## Communities (39 total, 11 thin omitted)

### Community 0 - "文档评审系统设计档案"
Cohesion: 0.06
Nodes (62): Document Review System Implementation Plan, Bash Test Deletion Gate, Document Review System Design (spec), Plan Document Reviewer, Review Loop Error Handling Policy, Spec Document Reviewer, codex-tools.md platform reference, subagent-driven-development skill (+54 more)

### Community 1 - "个人版维护指南"
Cohesion: 0.06
Nodes (58): AGENTS.md — Superpowers 个人特调版维护指南, 技能是行为塑造代码原则, 提交约定 (fea/* 分支), 设计档案 (docs/superpowers/specs + plans), graphify-out/ 代码库知识图谱, index.js — OpenCode V2 目录形式插件入口, obra/superpowers 上游仓库, 仅支持 OpenCode 约束 (V1 + V2) (+50 more)

### Community 2 - "Codex 兼容设计档案"
Cohesion: 0.08
Nodes (39): Codex App Compatibility Implementation Plan, references/codex-tools.md, Detached HEAD Handoff to Bash, Codex App Environment Detection, Worktree Rototill Implementation Plan, Native Tool Preference Rule, Provenance-Based Worktree Cleanup, Testing Skills Framework (RED/GREEN/PRESSURE) (+31 more)

### Community 3 - "技能改进反馈档案"
Cohesion: 0.09
Nodes (34): Diagnosed Session Case File, Skills Improvements from User Feedback, Configuration Change Verification, Mock-Interface Drift Anti-Pattern, Similar-Session Matcher Prompt (diagnosing-superpowers), Skill Timeline Analyst Prompt (diagnosing-superpowers), Stumbles Analyst Prompt (diagnosing-superpowers), diagnosing-superpowers Skill (+26 more)

### Community 4 - "SDD 提示模板"
Cohesion: 0.09
Nodes (30): Lean Context Option for Subagent Dispatch, Process Hygiene for E2E Tests, Self-Reflection Before Handoff, Auth System Plan (shared test fixture), Spec Document Reviewer Prompt Template, Context Safety Rules (diagnosing-superpowers), GitHub Issues Reference (diagnosing-superpowers), Redaction Policy (diagnosing-superpowers) (+22 more)

### Community 5 - "可视化头脑风暴档案"
Cohesion: 0.15
Nodes (25): Visual Brainstorming Refactor Implementation Plan, brainstorm-server (lib/brainstorm-server), Browser Displays, Terminal Commands Model, Visual Brainstorming Refactor Design (spec), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar (+17 more)

### Community 6 - "opencode 测试环境"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 7 - "行为准则与 OpenCode 指南"
Cohesion: 0.10
Nodes (23): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, Prime Radiant Community Code of Conduct, Superpowers for OpenCode Guide, OpenCode V1 Plugin Integration, OpenCode V2 Plugin API Integration, Platform-Neutral Config-File References Phase B Design (spec), Phase B Config-File Substitution Rules (+15 more)

### Community 8 - "OpenCode 插件集成"
Cohesion: 0.13
Nodes (22): superpowers-codex CLI Script, Installing Superpowers for OpenCode, OpenCode Tool Mapping, superpowers.js OpenCode Plugin, OpenCode Support Design, find_skills Custom Tool, session.started Bootstrap Hook, Skill Shadowing (personal skills override core skills) (+14 more)

### Community 9 - "技能编写方法论"
Cohesion: 0.16
Nodes (21): writing-skills 技能 (SKILL.md), agentskills.io 技能规范 (frontmatter 字段), 防合理化加固 (Bulletproofing), codex-tools.md 参考 (using-superpowers/references), 跨技能引用规范, 技能创建检查清单 (TDD 适配), 技能发现工作流, 流程图使用规范 (+13 more)

### Community 10 - "系统化调试案例"
Cohesion: 0.13
Nodes (15): Real-World Debugging Session (2025-10-03), Condition-Based Waiting Technique, Defense-in-Depth Validation Technique, find-polluter.sh script, Root Cause Tracing Technique, Systematic Debugging Skill, Four-Phase Debugging Framework, The Iron Law: No Fixes Without Root Cause Investigation (+7 more)

### Community 11 - "事件模型与检查点"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 12 - "零依赖服务器档案"
Cohesion: 0.15
Nodes (19): Zero-Dependency Brainstorm Server Implementation Plan, server.js Zero-Dependency Brainstorm Server, WebSocket Protocol Layer (RFC 6455 Frame Handling), Visual Brainstorming Companion Issue and Change Catalog, PID Ownership Check, Per-Session Secret Key Authentication, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI) (+11 more)

### Community 13 - "分支完成与 Handoff 档案"
Cohesion: 0.16
Nodes (19): Codex App Finishing Handoff Payload, Codex App Compatibility Design (spec), Read-Only Git Environment Detection, finishing-a-development-branch skill, IN_LINKED_WORKTREE Signal, ON_DETACHED_HEAD Signal, Sandbox Fallback Behavior, Consent-Authorization Bridge (+11 more)

### Community 14 - "Bootstrap 映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 15 - "会话诊断规则"
Cohesion: 0.23
Nodes (15): Diagnosing Superpowers Skill Implementation Plan, Transcript Context Safety Rules, Per-Harness Reference Files, No-Diagnosis Reporting Rule, Scrub Pipeline (scrub plus scrub-audit), analyst-common.md Shared Analyst Prompt Header, references/context-safety.md, cost-and-time.md Cost and Time Analyst Prompt (+7 more)

### Community 16 - "版本管理 CLI"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 17 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _bootstrapCache, _cacheChildSession(), _childSessionCache, __dirname, extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup() (+4 more)

### Community 18 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 19 - "Lint 脚本测试"
Cohesion: 0.35
Nodes (10): scripts/lint-shell.sh — shell lint 脚本, assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell() (+2 more)

### Community 20 - "Python 测试夹具"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 21 - "find-polluter 测试"
Cohesion: 0.36
Nodes (7): find-polluter 调试助手, assert_contains(), fail(), pass(), run_polluter(), setup_project(), test-find-polluter.sh script

### Community 22 - "package.json 清单"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 23 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Superpowers App Icon (app-icon.png, 2134x2134 square PNG), Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)

### Community 24 - "视觉伴侣实现档案"
Cohesion: 0.83
Nodes (4): Visual Brainstorming Companion Implementation Plan, Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Visual Companion Reference (visual-companion.md)

### Community 25 - "技能结构测试"
Cohesion: 0.83
Nodes (3): fail(), pass(), test-skill-structure.sh script

### Community 26 - "Hermes 版本接线实现"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Implementation Plan, Extension-Based Manifest Dispatcher (jq/yq), Preflight Manifest Reads

### Community 27 - "Hermes 版本接线设计"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Design (spec), Read-Only Preflight Manifest Validation, Hermes plugin.yaml Version-Bump YAML Wiring

## Ambiguous Edges - Review These
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to

## Knowledge Gaps
- **116 isolated node(s):** `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `HOME`, `OPENCODE_CONFIG_DIR`, `setup.sh script` (+111 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 183 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **11 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Bash Test Deletion Gate` connect `文档评审系统设计档案` to `Codex 兼容设计档案`?**
  _High betweenness centrality (0.118) - this node is a cross-community bridge._
- **Why does `Lift Drill into Superpowers as evals Implementation Plan` connect `Codex 兼容设计档案` to `文档评审系统设计档案`?**
  _High betweenness centrality (0.117) - this node is a cross-community bridge._
- **What connects `SDD Workspace and Ledger`, `Red-Green-Refactor TDD Cycle`, `HOME` to the rest of the system?**
  _116 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `文档评审系统设计档案` be split into smaller, more focused modules?**
  _Cohesion score 0.05658381808566896 - nodes in this community are weakly interconnected._
- **Should `个人版维护指南` be split into smaller, more focused modules?**
  _Cohesion score 0.0576271186440678 - nodes in this community are weakly interconnected._
- **Should `Codex 兼容设计档案` be split into smaller, more focused modules?**
  _Cohesion score 0.07692307692307693 - nodes in this community are weakly interconnected._
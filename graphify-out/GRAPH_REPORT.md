# Graph Report - superpowers  (2026-09-24)

## Corpus Check
- 10 files · ~217,086 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 793 nodes · 1252 edges · 48 communities (38 shown, 10 thin omitted)
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 111 edges (avg confidence: 0.85)
- Token cost: 5,200 input · 10,500 output

## Community Hubs (Navigation)
- Brainstorm 服务器核心
- SDD 计划与技能库
- OpenCode 安装与技能改进
- 个人版仓库结构
- Codex 兼容设计档案
- 会诊诊断技能
- 服务器生命周期测试
- OpenCode 指南与行为准则
- 可视化头脑风暴伴侣
- 技能编写最佳实践
- SDD 子代理提示模板
- Shell 脚本 Lint
- 服务器品牌化测试
- opencode 测试环境
- 服务器功能测试
- 系统化调试案例
- 服务器认证测试
- 版本管理 CLI
- 事件模型与检查点
- 零依赖服务器实现
- Bootstrap 映射测试
- Codex Handoff 设计档案
- 插件入口与缓存
- OpenCode 插件设计
- 品牌资产与浏览器库
- Windows 生命周期测试
- Python 测试夹具
- 客户端重连逻辑
- helper 客户端测试
- 停止服务器测试
- WebSocket 协议测试
- package.json 清单
- stop-server 脚本
- start-server 测试
- 品牌图标资产
- Hermes 版本接线实现
- Hermes 版本接线设计
- 评估设施引用
- start-server 脚本
- task-done 脚本
- task-start 脚本
- run-all 测试入口
- 扩展多轮测试
- haiku 模型测试
- 多轮对话测试
- 单测运行脚本
- opencode run-tests
- session-bootstrap 测试

## God Nodes (most connected - your core abstractions)
1. `Subagent-Driven Development Skill` - 24 edges
2. `executing-plans Skill` - 20 edges
3. `Superpowers 个人特调版 (OpenCode-Only Personal Fork)` - 17 edges
4. `runTests()` - 16 edges
5. `Systematic Debugging Skill` - 16 edges
6. `Writing Skills Skill (formerly skill-creation)` - 15 edges
7. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
8. `handleRequest()` - 14 edges
9. `main()` - 14 edges
10. `runTests()` - 13 edges

## Surprising Connections (you probably didn't know these)
- `Brainstorm Companion Frame Template` --references--> `Superpowers Logo Mark (small SVG)`  [INFERRED]
  skills/brainstorming/scripts/frame-template.html → assets/superpowers-small.svg
- `Subagent-Driven Development Skill` --implements--> `Lean Context Option for Subagent Dispatch`  [INFERRED]
  skills/subagent-driven-development/SKILL.md → docs/plans/2025-11-28-skills-improvements-from-user-feedback.md
- `Native (Inline) Execution Mode for executing-plans` --references--> `executing-plans Skill`  [EXTRACTED]
  RELEASE-NOTES.md → docs/plans/2025-11-22-opencode-support-implementation.md
- `executing-plans Skill` --conceptually_related_to--> `Skill: receiving-code-review`  [INFERRED]
  docs/plans/2025-11-22-opencode-support-implementation.md → skills/receiving-code-review/SKILL.md
- `Skill: requesting-code-review` --semantically_similar_to--> `Skill: dispatching-parallel-agents`  [INFERRED] [semantically similar]
  skills/requesting-code-review/SKILL.md → skills/dispatching-parallel-agents/SKILL.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Brainstorming Visual Companion System** — skills_brainstorming_visual_companion, skills_brainstorming_scripts_frame_template, skills_brainstorming_visual_companion_content_fragments [EXTRACTED 1.00]
- **Code Review Dispatch Flow** — skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_executing_plans_skill, skills_requesting_code_review_code_reviewer_declined_to_judge, skills_requesting_code_review_code_reviewer_spec_vision_document [EXTRACTED 1.00]
- **Diagnosing-Superpowers Analyst Prompt Suite** — docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill, skills_diagnosing_superpowers_prompts_analyst_common, skills_diagnosing_superpowers_prompts_cost_and_time, skills_diagnosing_superpowers_prompts_plan_adherence, skills_diagnosing_superpowers_prompts_quality_evidence, skills_diagnosing_superpowers_prompts_repeated_work, skills_diagnosing_superpowers_prompts_request_conflicts [EXTRACTED 1.00]
- **Cross-Platform Shared-Core Architecture** — docs_plans_2025_11_22_opencode_support_design, docs_plans_2025_11_22_opencode_support_implementation, lib_skills_core, _opencode_plugin_superpowers, _codex_superpowers_codex [EXTRACTED 1.00]
- **Platform-Neutral Migration Phases A B C** — docs_superpowers_specs_2026_05_05_platform_neutral_prose_design_phase_a_replacement_style, docs_superpowers_specs_2026_05_05_platform_neutral_config_refs_design_phase_b_substitution_rules, docs_superpowers_specs_2026_05_05_platform_neutral_readme_design_phase_c_alphabetical_ordering [EXTRACTED 1.00]
- **SDD Per-Task Review Loop** — skills_subagent_driven_development_skill, skills_subagent_driven_development_implementer_prompt, skills_subagent_driven_development_task_reviewer_prompt, skills_subagent_driven_development_re_review_prompt, skills_subagent_driven_development_skill_fix_loop [EXTRACTED 1.00]
- **Superpowers Plan Execution Lifecycle** — skills_writing_plans_skill, skills_executing_plans_skill, skills_test_driven_development_skill, skills_verification_before_completion_skill, skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_finishing_a_development_branch_skill, skills_using_git_worktrees_skill [EXTRACTED 1.00]
- **Systematic Debugging Supporting Techniques** — skills_systematic_debugging_skill, skills_systematic_debugging_root_cause_tracing, skills_systematic_debugging_defense_in_depth, skills_systematic_debugging_condition_based_waiting [EXTRACTED 1.00]
- **Visual Companion Auth Hardening Security Layer** — docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_bootstrap_keyed_loads, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_session_storage_key, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_websocket_same_origin_enforcement, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_files_containment, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_leak_reduction_headers [EXTRACTED 1.00]
- **Explicit Skill Request Trigger Test Suite** — tests_explicit_skill_requests_prompts_action_oriented, tests_explicit_skill_requests_prompts_after_planning_flow, tests_explicit_skill_requests_prompts_claude_suggested_it, tests_explicit_skill_requests_prompts_i_know_what_sdd_means, tests_explicit_skill_requests_prompts_mid_conversation_execute_plan, tests_explicit_skill_requests_prompts_please_use_brainstorming, tests_explicit_skill_requests_prompts_skip_formalities, tests_explicit_skill_requests_prompts_subagent_driven_development_please, tests_explicit_skill_requests_prompts_use_systematic_debugging [INFERRED 0.85]
- **Per-Harness Platform Tool References** — docs_superpowers_plans_2026_03_23_codex_app_compatibility_codex_tools_reference, docs_superpowers_plans_2026_05_07_pi_extension_and_evals_pi_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_antigravity_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_gemini_tools_reference [INFERRED 0.85]
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_plans_2026_07_30_codex_efficiency_fixes_hypothesis_log, docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill [INFERRED 0.85]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Adversarial Pressure Testing of Systematic Debugging Skill** — skills_systematic_debugging_skill, skills_systematic_debugging_creation_log, skills_systematic_debugging_test_academic, skills_systematic_debugging_test_pressure_1, skills_systematic_debugging_test_pressure_2, skills_systematic_debugging_test_pressure_3 [INFERRED 0.85]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]
- **Core Development Workflow** — docs_superpowers_specs_2026_01_22_document_review_system_design_brainstorming_skill, skills_using_git_worktrees_skill, skills_writing_plans_skill, docs_superpowers_specs_2026_03_23_codex_app_compatibility_design_subagent_driven_development_skill, skills_executing_plans_skill, readme_test_driven_development_skill, readme_requesting_code_review_skill, docs_superpowers_specs_2026_03_23_codex_app_compatibility_design_finishing_a_development_branch_skill [EXTRACTED 1.00]
- **Plugin Test Suite (tests/)** — docs_testing_plugin_tests, docs_testing_brainstorm_server_tests, docs_testing_opencode_plugin_tests, tests_diagnosing_superpowers_test_skill_structure, docs_testing_explicit_skill_request_tests, tests_shell_lint_test_lint_shell, tests_systematic_debugging_test_find_polluter, tests_version_bump_test_bump_version, tests_writing_skills_test_render_graphs [EXTRACTED 1.00]
- **Personal Fork Maintenance Constraints** — agents_opencode_only_constraint, agents_skill_content_protection, agents_zero_dependency_principle, agents_design_archive_authority [EXTRACTED 1.00]

## Communities (48 total, 10 thin omitted)

### Community 0 - "Brainstorm 服务器核心"
Cohesion: 0.05
Nodes (59): RFC-6455, bootstrapPage(), brandMarkup(), broadcast(), browserLauncherForPlatform(), chmodOwnerOnly(), clients, companionUrl() (+51 more)

### Community 1 - "SDD 计划与技能库"
Cohesion: 0.06
Nodes (58): Bash Test Deletion Gate, codex-tools.md platform reference, finishing-a-development-branch skill, subagent-driven-development skill, Lift Drill into superpowers as evals/ Design (spec), Drill Skill-Compliance Benchmark, evals/ Canonical Eval Harness, Subagent-Gated Verification Protocol (+50 more)

### Community 2 - "OpenCode 安装与技能改进"
Cohesion: 0.08
Nodes (45): Installing Superpowers for OpenCode, OpenCode Tool Mapping, Skills Improvements from User Feedback, Configuration Change Verification, Mock-Interface Drift Anti-Pattern, Document Review System Implementation Plan, brainstorming skill, Document Review System Design (spec) (+37 more)

### Community 3 - "个人版仓库结构"
Cohesion: 0.07
Nodes (40): brainstorm server (skills/brainstorming/scripts/), Commit Conventions, Design Archive Authority, graphify-out/ Knowledge Graph, index.js (OpenCode V2 Plugin Entry), OpenCode-Only Constraint, .opencode/plugins/superpowers.js (OpenCode Plugin), Superpowers 个人特调版 (OpenCode-Only Personal Fork) (+32 more)

### Community 4 - "Codex 兼容设计档案"
Cohesion: 0.08
Nodes (39): Codex App Compatibility Implementation Plan, references/codex-tools.md, Detached HEAD Handoff to Bash, Codex App Environment Detection, Worktree Rototill Implementation Plan, Native Tool Preference Rule, Provenance-Based Worktree Cleanup, Testing Skills Framework (RED/GREEN/PRESSURE) (+31 more)

### Community 5 - "会诊诊断技能"
Cohesion: 0.09
Nodes (31): Diagnosed Session Case File, Diagnosing Superpowers Skill Implementation Plan, Transcript Context Safety Rules, Per-Harness Reference Files, No-Diagnosis Reporting Rule, Scrub Pipeline (scrub plus scrub-audit), analyst-common.md Shared Analyst Prompt Header, references/context-safety.md (+23 more)

### Community 6 - "服务器生命周期测试"
Cohesion: 0.11
Nodes (29): ws, assert, firstServerStarted(), fs, httpStatus(), isWindowsLikeShell(), killAndWait(), makeShellTempDir() (+21 more)

### Community 7 - "OpenCode 指南与行为准则"
Cohesion: 0.09
Nodes (26): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, Prime Radiant Community Code of Conduct, Superpowers for OpenCode Guide, OpenCode V1 Plugin Integration, OpenCode V2 Plugin API Integration, Platform-Neutral Config-File References Phase B Design (spec), Phase B Config-File Substitution Rules (+18 more)

### Community 8 - "可视化头脑风暴伴侣"
Cohesion: 0.15
Nodes (25): Visual Brainstorming Refactor Implementation Plan, brainstorm-server (lib/brainstorm-server), Browser Displays, Terminal Commands Model, Visual Brainstorming Refactor Design (spec), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar (+17 more)

### Community 9 - "技能编写最佳实践"
Cohesion: 0.10
Nodes (24): codex-tools.md Reference (using-superpowers), gemini-tools.md Reference (using-superpowers), Anthropic Skill Authoring Best Practices, Anthropic Agent Skills Documentation, Progressive Disclosure Pattern for Skills, graphviz-conventions.dot, Persuasion Principles for Skill Design, Cialdini (2021) Influence: The Psychology of Persuasion (+16 more)

### Community 10 - "SDD 子代理提示模板"
Cohesion: 0.13
Nodes (21): Lean Context Option for Subagent Dispatch, Process Hygiene for E2E Tests, Self-Reflection Before Handoff, Auth System Plan (shared test fixture), Spec Document Reviewer Prompt Template, Implementer Subagent Prompt Template, Scoped Re-Review Prompt Template, review-package script (+13 more)

### Community 11 - "Shell 脚本 Lint"
Cohesion: 0.19
Nodes (21): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+13 more)

### Community 12 - "服务器品牌化测试"
Cohesion: 0.19
Nodes (23): assert, assertBrandedFallbackText(), assertBrandedWithLogo(), assertFramedLogoSupportsDarkTheme(), assertFramedScreenUsesBrandHeader(), assertHeaderAvoidsNarrowOverlap(), assertLogoKeepsTransparentBackground(), assertTelemetryImage() (+15 more)

### Community 13 - "opencode 测试环境"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 14 - "服务器功能测试"
Cohesion: 0.15
Nodes (20): assert, assertStartedOnExpectedPort(), cleanup(), CONTENT_DIR, ensureSymlinkWorks(), fetch(), fs, http (+12 more)

### Community 15 - "系统化调试案例"
Cohesion: 0.14
Nodes (17): Real-World Debugging Session (2025-10-03), Condition-Based Waiting Technique, Systematic Debugging Creation Log, Defense-in-Depth Validation Technique, find-polluter.sh script, Root Cause Tracing Technique, Systematic Debugging Skill, Four-Phase Debugging Framework (+9 more)

### Community 16 - "服务器认证测试"
Cohesion: 0.16
Nodes (20): assert, assertSecurityHeaders(), assertStartedOnExpectedPort(), cleanup(), CONTENT_DIR, EXPECTED_SECURITY_HEADERS, fs, get() (+12 more)

### Community 17 - "版本管理 CLI"
Cohesion: 0.20
Nodes (15): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+7 more)

### Community 18 - "事件模型与检查点"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 19 - "零依赖服务器实现"
Cohesion: 0.15
Nodes (19): Zero-Dependency Brainstorm Server Implementation Plan, server.js Zero-Dependency Brainstorm Server, WebSocket Protocol Layer (RFC 6455 Frame Handling), Visual Brainstorming Companion Issue and Change Catalog, PID Ownership Check, Per-Session Secret Key Authentication, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI) (+11 more)

### Community 20 - "Bootstrap 映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 21 - "Codex Handoff 设计档案"
Cohesion: 0.22
Nodes (15): Codex App Finishing Handoff Payload, Codex App Compatibility Design (spec), Read-Only Git Environment Detection, IN_LINKED_WORKTREE Signal, ON_DETACHED_HEAD Signal, Sandbox Fallback Behavior, Consent-Authorization Bridge, Worktree Rototill Detect-and-Defer Design (spec) (+7 more)

### Community 22 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _bootstrapCache, _cacheChildSession(), _childSessionCache, __dirname, extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup() (+4 more)

### Community 23 - "OpenCode 插件设计"
Cohesion: 0.26
Nodes (13): superpowers-codex CLI Script, superpowers.js OpenCode Plugin, OpenCode Support Design, find_skills Custom Tool, session.started Bootstrap Hook, Skill Shadowing (personal skills override core skills), use_skill Custom Tool, OpenCode Support Implementation Plan (+5 more)

### Community 24 - "品牌资产与浏览器库"
Cohesion: 0.24
Nodes (12): Superpowers Logo Mark (small SVG), Visual Brainstorming Companion Implementation Plan, Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Brainstorm Companion Frame Template, Brainstorming Skill, HARD-GATE Approval Prerequisites, Three Paths Classification (Spike / Bounded / Architectural) (+4 more)

### Community 25 - "Windows 生命周期测试"
Cohesion: 0.36
Nodes (8): fail(), get_key_from_info(), get_port_from_info(), http_check(), pass(), windows-lifecycle.test.sh script, skip(), wait_for_server_info()

### Community 26 - "Python 测试夹具"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 27 - "客户端重连逻辑"
Cohesion: 0.42
Nodes (7): connect(), nextReconnectDelay(), reloadAfterRecovery(), sessionKey(), setStatus(), showTombstone(), websocketUrl()

### Community 28 - "helper 客户端测试"
Cohesion: 0.22
Nodes (6): assert, fs, HELPER, moduleShim, path, src

### Community 29 - "停止服务器测试"
Cohesion: 0.39
Nodes (7): bad(), new_server_id(), ok(), stop-server.test.sh script, track_dir(), track_pid(), untrack_pid()

### Community 30 - "WebSocket 协议测试"
Cohesion: 0.25
Nodes (6): assert, crypto, RFC-6455, path, runTests(), SERVER_PATH

### Community 31 - "package.json 清单"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 32 - "stop-server 脚本"
Cohesion: 0.52
Nodes (6): command_has_server_id(), command_line_for_pid(), is_brainstorm_server(), mark_stopped(), read_expected_server_id(), stop-server.sh script

### Community 33 - "start-server 测试"
Cohesion: 0.53
Nodes (4): fail(), make_fake_uname(), pass(), start-server.test.sh script

### Community 34 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Superpowers App Icon (app-icon.png, 2134x2134 square PNG), Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)

### Community 35 - "Hermes 版本接线实现"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Implementation Plan, Extension-Based Manifest Dispatcher (jq/yq), Preflight Manifest Reads

### Community 36 - "Hermes 版本接线设计"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Design (spec), Read-Only Preflight Manifest Validation, Hermes plugin.yaml Version-Bump YAML Wiring

### Community 37 - "评估设施引用"
Cohesion: 1.00
Nodes (3): Quorum Eval Harness, Skill Behavior Evals (evals/), superpowers-evals Repo

## Ambiguous Edges - Review These
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to

## Knowledge Gaps
- **167 isolated node(s):** `assert`, `{
  browserLauncherForPlatform
}`, `CONTENT_DIR`, `fs`, `http` (+162 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 254 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **10 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Bash Test Deletion Gate` connect `SDD 计划与技能库` to `OpenCode 安装与技能改进`, `Codex 兼容设计档案`?**
  _High betweenness centrality (0.096) - this node is a cross-community bridge._
- **Why does `Lift Drill into Superpowers as evals Implementation Plan` connect `Codex 兼容设计档案` to `SDD 计划与技能库`?**
  _High betweenness centrality (0.095) - this node is a cross-community bridge._
- **Why does `writing-plans Skill` connect `OpenCode 安装与技能改进` to `品牌资产与浏览器库`, `SDD 计划与技能库`?**
  _High betweenness centrality (0.086) - this node is a cross-community bridge._
- **What connects `assert`, `{
  browserLauncherForPlatform
}`, `CONTENT_DIR` to the rest of the system?**
  _167 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Brainstorm 服务器核心` be split into smaller, more focused modules?**
  _Cohesion score 0.051923076923076926 - nodes in this community are weakly interconnected._
- **Should `SDD 计划与技能库` be split into smaller, more focused modules?**
  _Cohesion score 0.06170598911070781 - nodes in this community are weakly interconnected._
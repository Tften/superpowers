# Graph Report - superpowers  (2026-09-24)

## Corpus Check
- 225 files · ~252,998 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 1049 nodes · 1642 edges · 93 communities (72 shown, 20 thin omitted)
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 137 edges (avg confidence: 0.84)
- Token cost: 212,000 input · 56,000 output

## Community Hubs (Navigation)
- Brainstorm 服务器核心
- Codex 兼容与 Worktree 计划
- 插件同步测试脚本
- 服务器认证测试
- 插件清单与贡献模板
- 可视化头脑风暴伴侣
- Harness 工具参考与技能编写
- 服务器品牌化测试
- 安装与环境设置脚本
- 服务器生命周期测试
- 服务器功能测试
- 系统化调试案例与技巧
- SDD 子代理提示模板
- 事件模型与检查点
- 零依赖服务器实现
- 插件同步脚本
- Python 插件测试
- 执行计划与 Codex Handoff
- 贡献指南与 Issue 模板
- TDD 与分支完成技能
- 会话诊断技能
- Bootstrap 注入测试
- Bootstrap 版本映射测试
- 版本与审计 CLI
- 技能改进与 SDD 工作区
- SDD 进度账本与工作区
- 插件入口与缓存
- Bootstrap 注入机制
- 核心工作流技能群
- Shell 脚本 Lint
- Codex 插件打包测试
- 品牌资产与浏览器辅助库
- 计划编写与指令重设计
- superpowers.ts 扩展
- Lint 脚本测试
- 文档评审系统
- SDD 严格成本设计
- 代码评审分发设计
- package.json 清单元数据
- Windows 生命周期测试
- Frontmatter 测试夹具
- Pi 扩展测试
- 测试与评估设施
- 平台中立化设计
- 客户端重连逻辑
- 诊断参考文档
- helper 客户端测试
- 停止服务器测试
- WebSocket 协议测试
- Token 用量分析脚本
- 插件打包脚本
- find-polluter 测试
- 新 Harness 验收测试
- 工具映射与技能命名规则
- 诊断分析师提示
- 头脑风暴与效率修复
- stop-server 脚本
- session-start 测试
- render-graphs 测试
- 诊断证据规则
- Hermes 插件加载
- start-server 测试
- executing-plans 脚本测试
- sdd-workspace 测试
- 品牌图标资产
- Superpowers 哲学与版本
- bump-version 测试
- Pre-commit 质量门禁
- worktree 路径策略测试
- 技能结构测试
- Hermes 版本接线实现
- Hermes 版本接线设计
- pytest 夹具
- session-start 脚本
- start-server 脚本
- sdd-workspace 脚本
- antigravity 工具测试
- devin 插件测试
- task-done 脚本
- task-start 脚本
- antigravity run-tests
- 技能测试运行器
- marketplace 清单测试
- run-all 测试入口
- 扩展多轮测试
- haiku 模型测试
- 多轮对话测试
- 单测运行脚本
- kimi run-tests
- 插件清单测试
- opencode run-tests
- session-bootstrap 测试

## God Nodes (most connected - your core abstractions)
1. `main()` - 27 edges
2. `Subagent-Driven Development Skill` - 24 edges
3. `main()` - 16 edges
4. `runTests()` - 16 edges
5. `Systematic Debugging Skill` - 16 edges
6. `executing-plans Skill` - 16 edges
7. `Writing Skills Skill (formerly skill-creation)` - 15 edges
8. `handleRequest()` - 14 edges
9. `SDD Task-Scoped Review Dispatch Design (spec)` - 14 edges
10. `runTests()` - 13 edges

## Surprising Connections (you probably didn't know these)
- `requesting-code-review Skill` --semantically_similar_to--> `Skill: dispatching-parallel-agents`  [INFERRED] [semantically similar]
  docs/plans/2025-11-28-skills-improvements-from-user-feedback.md → skills/dispatching-parallel-agents/SKILL.md
- `Superpowers Contributor Guidelines (AGENTS.md)` --references--> `Quorum Eval Harness`  [INFERRED]
  AGENTS.md → docs/testing.md
- `New-Harness Acceptance Test (AGENTS.md)` --semantically_similar_to--> `New-Harness Acceptance Test (react todo list)`  [INFERRED] [semantically similar]
  AGENTS.md → docs/porting-to-a-new-harness.md
- `Hermes skill_view Fallback (read SKILL.md directly)` --conceptually_related_to--> `Porting Superpowers to a New Harness Guide`  [INFERRED]
  skills/using-superpowers/references/hermes-tools.md → docs/porting-to-a-new-harness.md
- `Claude Code Skills Tests README` --semantically_similar_to--> `CLAUDE_MD_TESTING.md Worked Example`  [INFERRED] [semantically similar]
  tests/claude-code/README.md → skills/writing-skills/testing-skills-with-subagents.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Visual Companion Auth Hardening Security Layer** — docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_bootstrap_keyed_loads, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_session_storage_key, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_websocket_same_origin_enforcement, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_files_containment, docs_superpowers_specs_2026_06_10_visual_companion_auth_hardening_design_leak_reduction_headers [EXTRACTED 1.00]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Platform-Neutral Migration Phases A B C** — docs_superpowers_specs_2026_05_05_platform_neutral_prose_design_phase_a_replacement_style, docs_superpowers_specs_2026_05_05_platform_neutral_config_refs_design_phase_b_substitution_rules, docs_superpowers_specs_2026_05_05_platform_neutral_readme_design_phase_c_alphabetical_ordering [EXTRACTED 1.00]
- **Per-Harness Platform Tool References** — docs_superpowers_plans_2026_03_23_codex_app_compatibility_codex_tools_reference, docs_superpowers_plans_2026_05_07_pi_extension_and_evals_pi_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_antigravity_tools_reference, docs_superpowers_plans_2026_06_09_sdd_task_scoped_review_dispatch_gemini_tools_reference [INFERRED 0.85]
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_plans_2026_07_30_codex_efficiency_fixes_hypothesis_log, docs_superpowers_plans_2026_08_27_diagnosing_superpowers_diagnosing_skill [INFERRED 0.85]
- **Diagnosing-Superpowers Analyst Prompt Suite** — docs_superpowers_plans_2026_08_27_diagnosing_superpowers_diagnosing_skill, skills_diagnosing_superpowers_prompts_analyst_common, skills_diagnosing_superpowers_prompts_cost_and_time, skills_diagnosing_superpowers_prompts_plan_adherence, skills_diagnosing_superpowers_prompts_quality_evidence, skills_diagnosing_superpowers_prompts_repeated_work, skills_diagnosing_superpowers_prompts_request_conflicts [EXTRACTED 1.00]
- **Systematic Debugging Supporting Techniques** — skills_systematic_debugging_skill, skills_systematic_debugging_root_cause_tracing, skills_systematic_debugging_defense_in_depth, skills_systematic_debugging_condition_based_waiting [EXTRACTED 1.00]
- **Adversarial Pressure Testing of Systematic Debugging Skill** — skills_systematic_debugging_skill, skills_systematic_debugging_creation_log, skills_systematic_debugging_test_academic, skills_systematic_debugging_test_pressure_1, skills_systematic_debugging_test_pressure_2, skills_systematic_debugging_test_pressure_3 [INFERRED 0.85]
- **Explicit Skill Request Trigger Test Suite** — tests_explicit_skill_requests_prompts_action_oriented, tests_explicit_skill_requests_prompts_after_planning_flow, tests_explicit_skill_requests_prompts_claude_suggested_it, tests_explicit_skill_requests_prompts_i_know_what_sdd_means, tests_explicit_skill_requests_prompts_mid_conversation_execute_plan, tests_explicit_skill_requests_prompts_please_use_brainstorming, tests_explicit_skill_requests_prompts_skip_formalities, tests_explicit_skill_requests_prompts_subagent_driven_development_please, tests_explicit_skill_requests_prompts_use_systematic_debugging [INFERRED 0.85]
- **Superpowers Basic Workflow Pipeline** — readme_brainstorming_skill, readme_using_git_worktrees_skill, readme_writing_plans_skill, readme_subagent_driven_development_skill, readme_executing_plans_skill, readme_test_driven_development_skill, readme_requesting_code_review_skill, readme_finishing_a_development_branch_skill [EXTRACTED 1.00]
- **Bootstrap Injection Mechanisms Across Harnesses** — docs_porting_to_a_new_harness_bootstrap, docs_porting_to_a_new_harness_integration_shapes, gemini_context_file, docs_readme_opencode_opencode_v1_plugin_integration, docs_readme_opencode_opencode_v2_plugin_api, docs_readme_kimi_kimi_plugin_manifest, docs_porting_to_a_new_harness_run_hook_polyglot [EXTRACTED 1.00]
- **Per-Harness Tool Mapping References** — docs_porting_to_a_new_harness_tool_mapping, skills_using_superpowers_references_antigravity_tools_antigravity_tool_mapping, skills_using_superpowers_references_codex_tools_codex_tool_mapping, skills_using_superpowers_references_gemini_tools_gemini_cli_tool_mapping, skills_using_superpowers_references_hermes_tools_hermes_tool_mapping, skills_using_superpowers_references_muse_tools_muse_tool_mapping, skills_using_superpowers_references_pi_tools_pi_tool_mapping [INFERRED 0.85]
- **SDD Per-Task Review Loop** — skills_subagent_driven_development_skill, skills_subagent_driven_development_implementer_prompt, skills_subagent_driven_development_task_reviewer_prompt, skills_subagent_driven_development_re_review_prompt, skills_subagent_driven_development_skill_fix_loop [EXTRACTED 1.00]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Cross-Platform Shared-Core Architecture** — docs_plans_2025_11_22_opencode_support_design, docs_plans_2025_11_22_opencode_support_implementation, lib_skills_core, _opencode_plugin_superpowers, _codex_superpowers_codex [EXTRACTED 1.00]
- **Superpowers Plan Execution Lifecycle** — skills_writing_plans_skill, skills_executing_plans_skill, skills_test_driven_development_skill, skills_verification_before_completion_skill, skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_finishing_a_development_branch_skill, skills_using_git_worktrees_skill [EXTRACTED 1.00]
- **Code Review Dispatch Flow** — skills_requesting_code_review_skill, skills_requesting_code_review_code_reviewer, skills_executing_plans_skill, skills_requesting_code_review_code_reviewer_declined_to_judge, skills_requesting_code_review_code_reviewer_spec_vision_document [EXTRACTED 1.00]
- **Brainstorming Visual Companion System** — skills_brainstorming_visual_companion, skills_brainstorming_scripts_frame_template, skills_brainstorming_visual_companion_content_fragments [EXTRACTED 1.00]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]

## Communities (93 total, 20 thin omitted)

### Community 0 - "Brainstorm 服务器核心"
Cohesion: 0.05
Nodes (59): bootstrapPage(), brandMarkup(), broadcast(), browserLauncherForPlatform(), chmodOwnerOnly(), RFC-6455, clients, companionUrl() (+51 more)

### Community 1 - "Codex 兼容与 Worktree 计划"
Cohesion: 0.05
Nodes (50): Codex App Compatibility Implementation Plan, references/codex-tools.md, Detached HEAD Handoff to Bash, Codex App Environment Detection, Worktree Rototill Implementation Plan, Native Tool Preference Rule, Provenance-Based Worktree Cleanup, Testing Skills Framework (RED/GREEN/PRESSURE) (+42 more)

### Community 2 - "插件同步测试脚本"
Cohesion: 0.15
Nodes (31): add_openai_agent_metadata_fixture(), assert_branch_absent(), assert_contains(), assert_current_branch(), assert_equals(), assert_file_equals(), assert_matches(), assert_not_contains() (+23 more)

### Community 3 - "服务器认证测试"
Cohesion: 0.10
Nodes (27): ws, assert, assertSecurityHeaders(), assertStartedOnExpectedPort(), cleanup(), CONTENT_DIR, EXPECTED_SECURITY_HEADERS, fs (+19 more)

### Community 4 - "插件清单与贡献模板"
Cohesion: 0.11
Nodes (26): superpowers-codex CLI Script, GitHub FUNDING Config (obra), Superpowers Pull Request Template, Brainstorming Acceptance Test ('Let's make a react todo list'), Hermes Agent Plugin Manifest (superpowers), Installing Superpowers for OpenCode, OpenCode Tool Mapping, superpowers.js OpenCode Plugin (+18 more)

### Community 5 - "可视化头脑风暴伴侣"
Cohesion: 0.14
Nodes (26): Visual Brainstorming Refactor Implementation Plan, brainstorm-server (lib/brainstorm-server), Browser Displays, Terminal Commands Model, Visual Brainstorming Refactor Design (spec), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar (+18 more)

### Community 6 - "Harness 工具参考与技能编写"
Cohesion: 0.10
Nodes (24): codex-tools.md Reference (using-superpowers), gemini-tools.md Reference (using-superpowers), Anthropic Skill Authoring Best Practices, Anthropic Agent Skills Documentation, Progressive Disclosure Pattern for Skills, graphviz-conventions.dot, Persuasion Principles for Skill Design, Cialdini (2021) Influence: The Psychology of Persuasion (+16 more)

### Community 7 - "服务器品牌化测试"
Cohesion: 0.19
Nodes (24): assert, assertBrandedFallbackText(), assertBrandedWithLogo(), assertFramedLogoSupportsDarkTheme(), assertFramedScreenUsesBrandHeader(), assertHeaderAvoidsNarrowOverlap(), assertLogoKeepsTransparentBackground(), assertTelemetryImage() (+16 more)

### Community 8 - "安装与环境设置脚本"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 9 - "服务器生命周期测试"
Cohesion: 0.16
Nodes (22): assert, firstServerStarted(), fs, httpStatus(), isWindowsLikeShell(), killAndWait(), makeShellTempDir(), newestSessionDir() (+14 more)

### Community 10 - "服务器功能测试"
Cohesion: 0.15
Nodes (20): assert, assertStartedOnExpectedPort(), cleanup(), CONTENT_DIR, ensureSymlinkWorks(), fetch(), fs, http (+12 more)

### Community 11 - "系统化调试案例与技巧"
Cohesion: 0.14
Nodes (17): Real-World Debugging Session (2025-10-03), Condition-Based Waiting Technique, Systematic Debugging Creation Log, Defense-in-Depth Validation Technique, find-polluter.sh script, Root Cause Tracing Technique, Systematic Debugging Skill, Four-Phase Debugging Framework (+9 more)

### Community 12 - "SDD 子代理提示模板"
Cohesion: 0.15
Nodes (19): Lean Context Option for Subagent Dispatch, Process Hygiene for E2E Tests, Self-Reflection Before Handoff, Auth System Plan (shared test fixture), Spec Document Reviewer Prompt Template, Implementer Subagent Prompt Template, Scoped Re-Review Prompt Template, review-package script (+11 more)

### Community 13 - "事件模型与检查点"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 14 - "零依赖服务器实现"
Cohesion: 0.15
Nodes (19): Zero-Dependency Brainstorm Server Implementation Plan, server.js Zero-Dependency Brainstorm Server, WebSocket Protocol Layer (RFC 6455 Frame Handling), Visual Brainstorming Companion Issue and Change Catalog, PID Ownership Check, Per-Session Secret Key Authentication, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI) (+11 more)

### Community 15 - "插件同步脚本"
Cohesion: 0.21
Nodes (17): append_git_ignored_directory_excludes(), append_git_ignored_file_excludes(), apply_to_preview_checkout(), confirm(), copy_local_destination_overlay(), copy_preserved_destination_metadata(), die(), ignored_directory_has_tracked_descendants() (+9 more)

### Community 16 - "Python 插件测试"
Cohesion: 0.19
Nodes (7): _fire_pre_llm(), _load_plugin(), Copy the plugin module + a minimal skills tree in the given layout., Re-import plugin module fresh., TestBootstrapInjection, TestLayoutResolution, TestPluginRegistration

### Community 17 - "执行计划与 Codex Handoff"
Cohesion: 0.18
Nodes (18): Codex App Finishing Handoff Payload, Codex App Compatibility Design (spec), Read-Only Git Environment Detection, executing-plans skill, IN_LINKED_WORKTREE Signal, ON_DETACHED_HEAD Signal, Sandbox Fallback Behavior, using-git-worktrees skill (+10 more)

### Community 18 - "贡献指南与 Issue 模板"
Cohesion: 0.18
Nodes (17): Bug Report Issue Template, Session Diagnosis Report Template, Feature Request Issue Template, IDE / Platform Support Request Template, Superpowers Contributor Guidelines (AGENTS.md), PRs Target dev Branch Policy, Submitter Identification Policy, 94% PR Rejection Anti-Slop Rationale (+9 more)

### Community 19 - "TDD 与分支完成技能"
Cohesion: 0.18
Nodes (17): Configuration Change Verification, finishing-a-development-branch Skill, Test-Driven Development Skill, TDD Iron Law: No Production Code Without a Failing Test First, Red-Green-Refactor TDD Cycle, Writing Good Tests, Principle: Exercise the Real Thing, Principle: Name the Break (+9 more)

### Community 20 - "会话诊断技能"
Cohesion: 0.21
Nodes (16): Diagnosing Superpowers Skill Implementation Plan, Transcript Context Safety Rules, diagnosing-superpowers Skill, Per-Harness Reference Files, No-Diagnosis Reporting Rule, Scrub Pipeline (scrub plus scrub-audit), analyst-common.md Shared Analyst Prompt Header, references/context-safety.md (+8 more)

### Community 21 - "Bootstrap 注入测试"
Cohesion: 0.23
Nodes (5): _bootstrap(), _load(), TestBootstrapContent, TestSkillsDirResolution, TestStripFrontmatter

### Community 22 - "Bootstrap 版本映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 23 - "版本与审计 CLI"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 24 - "技能改进与 SDD 工作区"
Cohesion: 0.22
Nodes (14): Skills Improvements from User Feedback, Mock-Interface Drift Anti-Pattern, executing-plans Skill, SDD Workspace and Ledger, Skill: receiving-code-review, code-reviewer Prompt (requesting-code-review), Declined to Judge List, Read-Only Review Rule (+6 more)

### Community 25 - "SDD 进度账本与工作区"
Cohesion: 0.27
Nodes (14): finishing-a-development-branch skill, SDD Durable Progress Ledger, L4 Resident-Context Diet, SDD Plan-Scoped Workspace Design (spec), SDD Plan-Scoped Workspace Eval Results, Eval Fixture Generator v3, S1 Stale-Ledger Scenario, S2 Same-Plan Resume Scenario (+6 more)

### Community 26 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _bootstrapCache, _cacheChildSession(), _childSessionCache, __dirname, extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup() (+4 more)

### Community 27 - "Bootstrap 注入机制"
Cohesion: 0.22
Nodes (13): using-superpowers Bootstrap Injection, Install-Mechanism-Only Rule (never edit user config), Integration Shapes A/B/C (shell-hook, in-process, instructions-file), run-hook.cmd Polyglot Wrapper, Automatic Session-Start Injection Requirement, Superpowers for Kimi Code Guide, Kimi Plugin Manifest (.kimi-plugin/plugin.json), Superpowers for OpenCode Guide (+5 more)

### Community 28 - "核心工作流技能群"
Cohesion: 0.18
Nodes (13): Superpowers Basic Workflow, executing-plans Skill, finishing-a-development-branch Skill, requesting-code-review Skill, subagent-driven-development Skill, using-git-worktrees Skill, writing-plans Skill, Native (Inline) Execution Mode for executing-plans (+5 more)

### Community 29 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 30 - "Codex 插件打包测试"
Cohesion: 0.36
Nodes (11): assert_contains(), assert_equals(), assert_not_matches(), extract_archive(), fail(), list_archive(), normalize_archive_paths(), pass() (+3 more)

### Community 31 - "品牌资产与浏览器辅助库"
Cohesion: 0.24
Nodes (12): Superpowers Logo Mark (small SVG), Visual Brainstorming Companion Implementation Plan, Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Brainstorm Companion Frame Template, Brainstorming Skill, HARD-GATE Approval Prerequisites, Three Paths Classification (Spike / Bounded / Architectural) (+4 more)

### Community 32 - "计划编写与指令重设计"
Cohesion: 0.23
Nodes (12): writing-plans skill, Drill Skill-Compliance Benchmark, Positive-Instruction Redesign of Skill Guidance Design (spec), Micro-Test Harness for Prompt Guidance, writing-plans No Placeholders Section, Positive-Instruction Doctrine, Strict-Cost SDD Design (spec), L1 Plan-Side Crispness (+4 more)

### Community 33 - "superpowers.ts 扩展"
Cohesion: 0.27
Nodes (10): bootstrapSkillPath, extensionDir, firstNonCompactionSummaryIndex(), getBootstrapContent(), messageContainsBootstrap(), packageRoot, piToolMapping(), skillsDir (+2 more)

### Community 34 - "Lint 脚本测试"
Cohesion: 0.40
Nodes (9): assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell(), test-lint-shell.sh script (+1 more)

### Community 35 - "文档评审系统"
Cohesion: 0.29
Nodes (10): Document Review System Implementation Plan, Document Review System Design (spec), Plan Document Reviewer, Review Loop Error Handling Policy, Spec Document Reviewer, Bash Test Deletion Gate, Lift Drill into superpowers as evals/ Design (spec), evals/ Canonical Eval Harness (+2 more)

### Community 36 - "SDD 严格成本设计"
Cohesion: 0.31
Nodes (10): subagent-driven-development skill, implementer-prompt.md, Strict-Cost Experiment Ladder, Controller Adjudication at Circuit-Breaker Trip, SDD Fix-Loop Redesign Design (spec), Fix-Loop Circuit Breaker, Excuse/Reality Rationalization Table, re-review-prompt.md (+2 more)

### Community 37 - "代码评审分发设计"
Cohesion: 0.27
Nodes (10): Cannot-Verify-From-Diff Channel, code-quality-reviewer-prompt.md, requesting-code-review/code-reviewer.md template, SDD Task-Scoped Review Dispatch Design (spec), Reviewer Scope Budget, spec-reviewer-prompt.md, task-reviewer-prompt.md (merged spec and quality reviewer), Task-Scoped Review (+2 more)

### Community 38 - "package.json 清单元数据"
Cohesion: 0.20
Nodes (9): description, keywords, main, name, pi, extensions, skills, type (+1 more)

### Community 39 - "Windows 生命周期测试"
Cohesion: 0.36
Nodes (8): fail(), get_key_from_info(), get_port_from_info(), http_check(), pass(), windows-lifecycle.test.sh script, skip(), wait_for_server_info()

### Community 40 - "Frontmatter 测试夹具"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 41 - "Pi 扩展测试"
Cohesion: 0.20
Nodes (5): __dirname, extensionPath, packageJsonPath, piToolsPath, repoRoot

### Community 42 - "测试与评估设施"
Cohesion: 0.22
Nodes (9): Issue Template Config (Discord Contact Link), Plugin Tests (tests/), Quorum Eval Harness, Skill Behavior Evals (evals/), Testing Superpowers Doc, dispatching-parallel-agents Skill, Superpowers Plugin, Codex Tool Mapping (+1 more)

### Community 43 - "平台中立化设计"
Cohesion: 0.31
Nodes (9): Platform-Neutral Config-File References Phase B Design (spec), Phase B Config-File Substitution Rules, Platform-Neutral Prose Phase A Design (spec), Phase A Agent-Neutral Prose Style, Claude Search Optimization to Skill Discovery Optimization Rename, writing-skills skill, Platform-Neutral README Ordering Phase C Design (spec), Phase C README Alphabetical Ordering (+1 more)

### Community 44 - "客户端重连逻辑"
Cohesion: 0.42
Nodes (7): connect(), nextReconnectDelay(), reloadAfterRecovery(), sessionKey(), setStatus(), showTombstone(), websocketUrl()

### Community 45 - "诊断参考文档"
Cohesion: 0.25
Nodes (9): Context Safety Rules (diagnosing-superpowers), GitHub Issues Reference (diagnosing-superpowers), Redaction Policy (diagnosing-superpowers), Session Discovery Reference, Diagnosis Bundle README Template, Diagnosis Case File Template, Diagnosis Issue Template, Diagnosis Report Template (+1 more)

### Community 46 - "helper 客户端测试"
Cohesion: 0.22
Nodes (6): assert, fs, HELPER, moduleShim, path, src

### Community 47 - "停止服务器测试"
Cohesion: 0.39
Nodes (7): bad(), new_server_id(), ok(), stop-server.test.sh script, track_dir(), track_pid(), untrack_pid()

### Community 48 - "WebSocket 协议测试"
Cohesion: 0.25
Nodes (6): assert, crypto, RFC-6455, path, runTests(), SERVER_PATH

### Community 49 - "Token 用量分析脚本"
Cohesion: 0.31
Nodes (8): analyze_main_session(), calculate_cost(), format_tokens(), main(), Analyze a session file and return token usage broken down by agent., Analyze token usage from Claude Code session transcripts. Breaks down usage by…, Format token count with thousands separators., Calculate estimated cost in dollars.

### Community 50 - "插件打包脚本"
Cohesion: 0.46
Nodes (6): die(), infer_format_from_output(), metadata_root_from_dir(), prepare_metadata_root(), package-codex-plugin.sh script, usage()

### Community 51 - "find-polluter 测试"
Cohesion: 0.43
Nodes (6): assert_contains(), fail(), pass(), run_polluter(), setup_project(), test-find-polluter.sh script

### Community 52 - "新 Harness 验收测试"
Cohesion: 0.33
Nodes (7): New-Harness Acceptance Test (AGENTS.md), New-Harness Acceptance Test (react todo list), Unique-Marker Test, brainstorming Skill, Visual Companion Telemetry (SUPERPOWERS_DISABLE_TELEMETRY), Hermes Agent Tool Mapping, Hermes skill_view Fallback (read SKILL.md directly)

### Community 53 - "工具映射与技能命名规则"
Cohesion: 0.33
Nodes (7): Skill Content Protection Policy (behavior-shaping content), Skills Name Actions, Not Tools Rule, Per-Harness Tool Mapping, Antigravity CLI (agy) Tool Mapping, Antigravity Task Artifact Pattern, pi-subagents Companion Package, Pi Tool Mapping

### Community 54 - "诊断分析师提示"
Cohesion: 0.38
Nodes (7): Diagnosed Session Case File, Similar-Session Matcher Prompt (diagnosing-superpowers), Skill Timeline Analyst Prompt (diagnosing-superpowers), Stumbles Analyst Prompt (diagnosing-superpowers), diagnosing-superpowers Skill, Skill: dispatching-parallel-agents, One Agent Per Independent Problem Domain

### Community 55 - "头脑风暴与效率修复"
Cohesion: 0.38
Nodes (7): brainstorming skill, codex-tools.md platform reference, Codex Efficiency Fixes Design (spec), T2: Event-Driven Waiting, T3: codex-tools.md V1/V2 Corrections, T4: Brainstorming Three-Path Router, T5: Explicit Model on Child-Issued Spawns

### Community 56 - "stop-server 脚本"
Cohesion: 0.52
Nodes (6): command_has_server_id(), command_line_for_pid(), is_brainstorm_server(), mark_stopped(), read_expected_server_id(), stop-server.sh script

### Community 57 - "session-start 测试"
Cohesion: 0.57
Nodes (5): assert_command_output(), fail(), make_home(), pass(), test-session-start.sh script

### Community 58 - "render-graphs 测试"
Cohesion: 0.67
Nodes (5): assert_contains(), assert_not_contains(), fail(), pass(), test-render-graphs.sh script

### Community 59 - "诊断证据规则"
Cohesion: 0.33
Nodes (6): file:line Evidence Rule, Context-Safety Rules, Diagnosing Superpowers Sessions Design (spec), path:line Finding Shape, Bundle Scrub and Independent Audit, Similar-Session Signature Search

### Community 60 - "Hermes 插件加载"
Cohesion: 0.53
Nodes (5): _build_bootstrap(), Locate the stock skills/ tree for either supported install layout. - git-clone…, register(), _skills_dir(), _strip_frontmatter()

### Community 61 - "start-server 测试"
Cohesion: 0.53
Nodes (4): fail(), make_fake_uname(), pass(), start-server.test.sh script

### Community 62 - "executing-plans 脚本测试"
Cohesion: 0.53
Nodes (4): fail(), main(), pass(), test-executing-plans-scripts.sh script

### Community 63 - "sdd-workspace 测试"
Cohesion: 0.53
Nodes (4): fail(), main(), pass(), test-sdd-workspace.sh script

### Community 64 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Superpowers App Icon (app-icon.png, 2134x2134 square PNG), Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)

### Community 65 - "Superpowers 哲学与版本"
Cohesion: 0.40
Nodes (5): Superpowers Philosophy, test-driven-development Skill, Plan-Scoped SDD Workspace (.superpowers/sdd/<plan-basename>/), Superpowers v6.2.0 Release, writing-good-tests Reference Catalog

### Community 66 - "bump-version 测试"
Cohesion: 0.60
Nodes (3): fail(), make_fixture(), test-bump-version.sh script

### Community 67 - "Pre-commit 质量门禁"
Cohesion: 0.50
Nodes (4): Pre-commit Config (evals quality gates), evals-ruff-check Hook, evals-ruff-format-check Hook, evals-ty-check Hook

### Community 68 - "worktree 路径策略测试"
Cohesion: 0.83
Nodes (3): assert_contains(), assert_not_contains(), test-worktree-path-policy.sh script

### Community 69 - "技能结构测试"
Cohesion: 0.83
Nodes (3): fail(), pass(), test-skill-structure.sh script

### Community 70 - "Hermes 版本接线实现"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Implementation Plan, Extension-Based Manifest Dispatcher (jq/yq), Preflight Manifest Reads

### Community 71 - "Hermes 版本接线设计"
Cohesion: 1.00
Nodes (3): Hermes Version-Bump Wiring Design (spec), Read-Only Preflight Manifest Validation, Hermes plugin.yaml Version-Bump YAML Wiring

## Ambiguous Edges - Review These
- `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)` → `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to

## Knowledge Gaps
- **193 isolated node(s):** `__dirname`, `superpowersSkillsDir`, `V1_MAPPING`, `V2_MAPPING`, `_bootstrapCache` (+188 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 310 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **20 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)` and `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Subagent-Driven Development Skill` connect `SDD 子代理提示模板` to `Harness 工具参考与技能编写`, `sdd-workspace 脚本`, `诊断参考文档`, `TDD 与分支完成技能`, `技能改进与 SDD 工作区`?**
  _High betweenness centrality (0.010) - this node is a cross-community bridge._
- **Why does `executing-plans Skill` connect `技能改进与 SDD 工作区` to `TDD 与分支完成技能`, `插件清单与贡献模板`, `SDD 子代理提示模板`?**
  _High betweenness centrality (0.007) - this node is a cross-community bridge._
- **Why does `Test-Driven Development Skill` connect `TDD 与分支完成技能` to `技能改进与 SDD 工作区`, `系统化调试案例与技巧`, `Harness 工具参考与技能编写`?**
  _High betweenness centrality (0.006) - this node is a cross-community bridge._
- **What connects `__dirname`, `superpowersSkillsDir`, `V1_MAPPING` to the rest of the system?**
  _193 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Brainstorm 服务器核心` be split into smaller, more focused modules?**
  _Cohesion score 0.051923076923076926 - nodes in this community are weakly interconnected._
- **Should `Codex 兼容与 Worktree 计划` be split into smaller, more focused modules?**
  _Cohesion score 0.05263157894736842 - nodes in this community are weakly interconnected._
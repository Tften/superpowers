# Graph Report - superpowers  (2026-09-25)

## Corpus Check
- 103 files · ~144,526 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 550 nodes · 810 edges · 44 communities (25 shown, 19 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 86 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Bootstrap 事件测试
- Bootstrap 映射测试
- 插件入口与缓存
- find-polluter 测试
- 事件模型与等待函数
- SDD Workspace and Ledger 档案
- Declined to Judge 档案
- 只读评审规则档案
- Spec 愿景文档档案
- Exercise the Real Thing 原则档案
- Name the Break 原则档案
- OpenCode 插件集成
- 技能结构测试
- 版本管理 CLI
- Shell 脚本 Lint
- Lint 脚本测试
- package.json 清单
- 执行计划脚本:workspace
- 执行计划脚本:review-package
- 执行计划脚本:task-brief
- 执行计划脚本:task-done
- 执行计划脚本:task-start
- opencode run-tests
- session-bootstrap 测试
- opencode 测试环境
- 个人版维护指南
- 技能测试方法档案
- 零依赖服务器档案
- TDD 与好测试原则
- 头脑风暴三路径
- 会话诊断规则与分析师
- 品牌图标资产
- 视觉伴侣实现档案
- SDD 工作区与发布档案
- Logo 标记资产
- Subagent Lean Context 档案
- E2E 流程卫生档案
- 交接自省档案
- Auth 共享夹具档案
- 版本发布档案
- 会话诊断模板与脱敏
- 可视化头脑风暴档案
- Eval 实施档案
- 社区文档与插件说明

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
- **RED-GREEN Eval-Driven Skill Development Methodology** — docs_superpowers_plans_2026_04_06_worktree_rototill_testing_skills_framework, docs_superpowers_specs_2026_08_27_diagnosing_superpowers_design_diagnosing_superpowers_skill [INFERRED 0.85]
- **SDD Review-Cost Iteration Campaign** — docs_superpowers_specs_2026_06_09_sdd_task_scoped_review_dispatch_design_task_scoped_review, docs_superpowers_specs_2026_06_10_positive_instruction_redesign_design_positive_instruction_doctrine, docs_superpowers_specs_2026_06_10_strict_cost_sdd_design_experiment_ladder, docs_superpowers_specs_2026_07_15_sdd_fix_loop_redesign_design_fix_loop_circuit_breaker [INFERRED 0.85]
- **Session Diagnosis Bundle Workflow** — skills_diagnosing_superpowers_templates_bundle_readme, skills_diagnosing_superpowers_templates_case, skills_diagnosing_superpowers_templates_report, skills_diagnosing_superpowers_templates_issue, skills_diagnosing_superpowers_references_redaction_policy [INFERRED 0.95]
- **Superpowers Codex Plugin Branding** — assets_app-icon_app_icon, assets_app-icon_plugin_logo, assets_app-icon_brand_identity [INFERRED]

## Communities (44 total, 19 thin omitted)

### Community 11 - "Bootstrap 事件测试"
Cohesion: 0.10
Nodes (14): checkpoint, childEvent, empty, freshRootEvent, newPromptAfterCheckpoint, originalChild, originalRetainedUserChild, pluginURL (+6 more)

### Community 14 - "Bootstrap 映射测试"
Cohesion: 0.12
Nodes (6): afterFirst, afterSecond, firstOutput, mappingFailures, result, secondOutput

### Community 16 - "插件入口与缓存"
Cohesion: 0.22
Nodes (12): _cacheChildSession(), extractAndStripFrontmatter(), getBootstrapContent(), isChildSession(), setup(), SuperpowersPlugin(), _bootstrapCache, _childSessionCache (+4 more)

### Community 21 - "find-polluter 测试"
Cohesion: 0.20
Nodes (8): added, failures, fixtureRoot, frontmatterFixtures, pluginPath, result, skillsDir, survived

### Community 3 - "事件模型与等待函数"
Cohesion: 0.07
Nodes (31): Red-Green-Refactor TDD Cycle, TDD Iron Law: No Production Code Without a Failing Test First, Red Flags / Common Rationalizations Pattern, Verification Gate Function, Verification Iron Law: No Completion Claims Without Fresh Verification Evidence, find-polluter.sh script, Real-World Debugging Session (2025-10-03), Common rationalizations table (requesting-code-review) (+23 more)

### Community 5 - "OpenCode 插件集成"
Cohesion: 0.11
Nodes (27): OpenCode Tool Mapping, superpowers-codex CLI Script, superpowers.js OpenCode Plugin, lib/skills-core.js Shared Skill Core Module, checkForUpdates, extractFrontmatter, findSkillsInDir, resolveSkillPath (+19 more)

### Community 10 - "技能结构测试"
Cohesion: 0.14
Nodes (16): fail(), pass(), test-skill-structure.sh script, assert_contains(), fail(), pass(), run_polluter(), setup_project() (+8 more)

### Community 15 - "版本管理 CLI"
Cohesion: 0.30
Nodes (12): cmd_audit(), cmd_bump(), cmd_check(), preflight_manifests(), read_json_field(), read_manifest_field(), read_yaml_field(), require_tool() (+4 more)

### Community 18 - "Shell 脚本 Lint"
Cohesion: 0.38
Nodes (12): add_shell_file(), collect_all_shell_files(), collect_changed_shell_files(), collect_requested_shell_files(), die(), ensure_git_work_tree(), is_shell_file(), require_tool() (+4 more)

### Community 19 - "Lint 脚本测试"
Cohesion: 0.40
Nodes (9): assert_contains(), assert_not_contains(), configure_git_identity(), fail(), make_fixture_repo(), pass(), run_lint_shell(), test-lint-shell.sh script (+1 more)

### Community 22 - "package.json 清单"
Cohesion: 0.29
Nodes (6): description, keywords, main, name, type, version

### Community 8 - "opencode 测试环境"
Cohesion: 0.11
Nodes (17): HOME, OPENCODE_CONFIG_DIR, setup.sh script, XDG_CONFIG_HOME, run_missing_file_check(), run_present_file_check(), test-bootstrap-caching.sh script, test-plugin-loading.sh script (+9 more)

### Community 0 - "个人版维护指南"
Cohesion: 0.06
Nodes (67): README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致), obra/superpowers(上游仓库), obra/superpowers(上游仓库), 提交约定(fea/* 分支,个人维护无 PR 流程,'type: 描述'风格), 设计档案是唯一依据(docs/superpowers/specs 20 份 + plans 16 份), 纯 Inline 工作流(禁用 Subagent), graphify-out/ — 代码库知识图谱(--update 增量更新、query 自然语言查询、graph.html 交互式图谱), 仅支持 OpenCode(V1+V2),多 harness 适配层已全部移除 (+59 more)

### Community 1 - "技能测试方法档案"
Cohesion: 0.08
Nodes (47): Drill Skill-Compliance Benchmark, evals/ Canonical Eval Harness, Subagent-Gated Verification Protocol, SUPERPOWERS_ROOT Auto-Default, Cannot-Verify-From-Diff Channel, code-quality-reviewer-prompt.md, requesting-code-review/code-reviewer.md template, implementer-prompt.md (+39 more)

### Community 12 - "零依赖服务器档案"
Cohesion: 0.16
Nodes (18): server.js Zero-Dependency Brainstorm Server, PID Ownership Check, Terminal vs HTML Approval Gate, Visual Brainstorming Companion (server.cjs and Web UI), WebSocket Origin Check, Bootstrap-Keyed Server Root, Strict Origin Enforcement, Realpath-Based Path Containment (/files/* Guard) (+10 more)

### Community 13 - "TDD 与好测试原则"
Cohesion: 0.16
Nodes (18): 测行为,不测文本(Behavior, not text), 测你的边界契约,不测框架(Your code, not the framework), 完整镜像真实数据(Mirror real data completely), 原则 2:每个测试锻炼真实对象(Exercise the Real Thing), 门函数 2:加 mock 或测试辅助前的检查, 门函数 1:写测试体前的检查, 独立推导期望值(字面量与手工校验 fixture), mock 不配拥有断言(The mock earns no assertions) (+10 more)

### Community 17 - "头脑风暴三路径"
Cohesion: 0.22
Nodes (14): Architectural 路径, Bounded 路径, 设计文档约定 (docs/superpowers/specs/YYYY-MM-DD-<topic>-design.md), elements-of-style:writing-clearly-and-concisely 技能 (可选), HARD-GATE 实施前置门, 路径单向棘轮 (只能升级), Red Flags 表 (想法 vs 现实), 建立共识 (Establish Shared Understanding) (+6 more)

### Community 2 - "会话诊断规则与分析师"
Cohesion: 0.10
Nodes (37): Approval gates (hard rule), Case workspace (~/.superpowers/diagnosing-superpowers/<session-id>/), cost-and-time analyst dimension (prompts/cost-and-time.md), Dispatch or inline (hard rule), Exact paths to subagents (hard rule), Export (workflow step 6), GitHub issues (workflow step 5), Human prompts only (hard rule) (+29 more)

### Community 23 - "品牌图标资产"
Cohesion: 0.50
Nodes (5): Codex Plugin Asset Packaging, Superpowers Brand Identity (Prime Radiant), Codex Plugin Logo Role, Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg), Superpowers App Icon (app-icon.png, 2134x2134 square PNG)

### Community 24 - "视觉伴侣实现档案"
Cohesion: 0.83
Nodes (4): Browser Helper Library (lib/brainstorm-server/helper.js), Brainstorm Server (lib/brainstorm-server/index.js), Visual Brainstorming Companion Implementation Plan, Visual Companion Reference (visual-companion.md)

### Community 25 - "SDD 工作区与发布档案"
Cohesion: 0.67
Nodes (3): Plan-Scoped SDD Workspace (.superpowers/sdd/<plan-basename>/), writing-good-tests Reference Catalog, Superpowers v6.2.0 Release

### Community 4 - "会话诊断模板与脱敏"
Cohesion: 0.10
Nodes (28): Diagnosed Session Case File, Per-Harness Reference Files, Scrub Pipeline (scrub plus scrub-audit), references/context-safety.md, references/redaction-policy.md, Context safety (hard rule), Diagnosing Superpowers Skill Implementation Plan, analyst-common.md Shared Analyst Prompt Header (+20 more)

### Community 6 - "可视化头脑风暴档案"
Cohesion: 0.15
Nodes (25): brainstorm-server (lib/brainstorm-server), .events Per-Screen Event Stream, frame-template.html UI frame, helper.js client script, Selection Indicator Bar, visual-companion.md skill instructions, wait-for-feedback.sh (deleted script), wrapInFrame Comment-Placeholder Injection (+17 more)

### Community 7 - "Eval 实施档案"
Cohesion: 0.14
Nodes (20): drill Eval Harness (evals/drill), SUPERPOWERS_ROOT Default, references/antigravity-tools.md, references/gemini-tools.md, Planted Defect Review Scenario, Reviewer Warn Verdict Channel, Forensic Disambiguation Tax, scripts/sdd-workspace.sh (+12 more)

### Community 9 - "社区文档与插件说明"
Cohesion: 0.10
Nodes (23): Contributor Covenant v3.0, Code of Conduct Enforcement Ladder, OpenCode V1 Plugin Integration, OpenCode V2 Plugin API Integration, Phase B Config-File Substitution Rules, Claude Search Optimization to Skill Discovery Optimization Rename, writing-skills skill, Phase C README Alphabetical Ordering (+15 more)

## Ambiguous Edges - Review These
- `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` → `skills/ — 11 个技能本体(纯 Inline 工作流,仓库核心资产)`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to
- `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` → `技能清单:11 个技能(测试1/调试3/协作6/元技能1)`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to
- `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` → `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`  [AMBIGUOUS]
  assets/app-icon.png · relation: conceptually_related_to

## Knowledge Gaps
- **125 isolated node(s):** `Red-Green-Refactor TDD Cycle`, `SDD Workspace and Ledger`, `checkpoint`, `childEvent`, `empty` (+120 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 187 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **19 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` and `skills/ — 11 个技能本体(纯 Inline 工作流,仓库核心资产)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `README 声明'保留全部 16 个技能'(与技能清单 11 个、AGENTS '11 个技能本体'不一致)` and `技能清单:11 个技能(测试1/调试3/协作6/元技能1)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Swoosh-and-Central-Dot Emblem Motif (mirrored curved wings around a center dot, per companion superpowers-small.svg)` and `Superpowers App Icon (app-icon.png, 2134x2134 square PNG)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `diagnosing-superpowers (SKILL.md)` connect `会话诊断规则与分析师` to `事件模型与等待函数`, `会话诊断模板与脱敏`?**
  _High betweenness centrality (0.070) - this node is a cross-community bridge._
- **Why does `diagnosing-superpowers skill` connect `社区文档与插件说明` to `会话诊断模板与脱敏`?**
  _High betweenness centrality (0.056) - this node is a cross-community bridge._
- **Why does `Diagnosing Superpowers Skill Implementation Plan` connect `会话诊断模板与脱敏` to `社区文档与插件说明`?**
  _High betweenness centrality (0.055) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `diagnosing-superpowers (SKILL.md)` (e.g. with `Similar-Session Matcher Prompt (diagnosing-superpowers)` and `Skill Timeline Analyst Prompt (diagnosing-superpowers)`) actually correct?**
  _`diagnosing-superpowers (SKILL.md)` has 4 INFERRED edges - model-reasoned connections that need verification._
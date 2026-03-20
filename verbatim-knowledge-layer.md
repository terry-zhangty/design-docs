# Verbatim — Knowledge Layer Presentation (knowledge-layer/index.html)

> Edit the EN/CN text below. Preserve the `[section-id]` markers.

## Document

### [document-title]
**EN**: Knowledge Layer — Team Agent Knowledge System
**CN**: 知识层 — 团队 Agent 知识体系

## Hero

### [hero-title-line1]
**EN**: Knowledge Layer
**CN**: 知识层

### [hero-title-line2]
**EN**: Team Agent Knowledge Layer
**CN**: 团队 Agent 知识层

### [hero-sub-en]
**EN**: Portable domain packs and entry files agents can discover—shared methodology without duplicating long rules at the repo root.
**CN**: 可移植的 domain pack 与入口文件，供各工具发现；共享方法论，避免在仓库根重复冗长规则。

### [hero-sub-cn]
**EN**: Portable domain packs and entry files for tools to discover; avoid duplicating long rules at the repo root.
**CN**: 可移植的域包与入口文件，供各工具发现；避免在仓库根重复冗长规则。

### [metric-research-areas]
**EN**: 5 research areas
**CN**: 5 个调研方向

### [metric-indexed-urls]
**EN**: 23 indexed reference URLs
**CN**: 23 条已索引参考链接

### [metric-upstream-skills]
**EN**: 17 upstream example skills
**CN**: 17 个上游示例 skills

### [metric-stacked-prs]
**EN**: 3 stacked PRs
**CN**: 3 个堆叠 PR

## Executive Summary

### [exec-section-heading]
**EN**: Executive Summary
**CN**: 执行摘要

### [exec-section-sub-cn]
**EN**: Executive summary — decisions and asks at a glance
**CN**: 执行摘要 · 决策与请求一览

### [exec-problem]
**EN**: Problem · 问题 — Agent knowledge (rules, skills, methodology) is scattered across personal setups—no portable, sharable team baseline.
**CN**: 知识分散在个人配置，缺少可共享的团队基线。

### [exec-proposal]
**EN**: Proposal · 方案 — A structured Knowledge Layer following the agentskills.io open specification: three-layer progressive disclosure, cross-tool compatibility (Cursor, Codex, Claude Code), automated validation.
**CN**: 三层 progressive disclosure、跨工具兼容与自动化校验。

### [exec-ask]
**EN**: Ask · 请求 — Review 3 stacked PRs (~1200 lines total, split for focused review). MVP lands in 3 merges.
**CN**: 审阅三个堆叠 PR，MVP 分三次合并。

## Problem → Solution

### [problem-solution-heading]
**EN**: Problem → Solution
**CN**: 问题与对策

### [problem-solution-sub-cn]
**EN**: Problem & response — from fragmentation to structure
**CN**: 问题与对策 · 从分散到结构化

### [before-badge]
**EN**: Before
**CN**: 之前

### [before-heading-cn]
**EN**: Before
**CN**: 之前

### [before-li-1]
**EN**: Rules and guidance scattered; hard to share a single team baseline.
**CN**: 规则与指引分散，难以形成统一的团队基线。

### [before-li-2]
**EN**: No common progressive-disclosure shape across tools.
**CN**: 各工具缺少统一的 progressive disclosure 形态。

### [before-li-3]
**EN**: Personal or machine-specific notes do not travel as portable packs.
**CN**: 个人或机器专属笔记难以作为可移植包流转。

### [after-badge]
**EN**: After
**CN**: 之后

### [after-heading-cn]
**EN**: After
**CN**: 之后

### [after-li-1]
**EN**: Structured domain packs under one workspace root with a thin cross-tool index.
**CN**: 在工作区根目录下集中 domain pack，并配薄层跨工具索引。

### [after-li-2]
**EN**: L1→L2→L3 loading: catalog hint, SKILL.md router, references/ on demand.
**CN**: L1→L2→L3 加载：目录提示、SKILL.md 路由、按需加载 references/。

### [after-li-3]
**EN**: Cross-tool entry: same packs for Cursor, Codex, and Claude Code conventions.
**CN**: 跨工具入口：同一套包适配 Cursor、Codex、Claude Code 约定。

## Why It Matters · Business Value

### [business-heading-en]
**EN**: Why It Matters
**CN**: 为何重要

### [business-heading-cn]
**EN**: Business value
**CN**: 业务价值

### [business-sub-cn]
**EN**: Speed, quality, and reach
**CN**: 速度、质量与范围

### [biz-faster]
**EN**: Faster onboarding · 更快上手 — New team members get structured methodology instead of tribal knowledge.
**CN**: 新人获得结构化方法，而非依赖口耳相传。

### [biz-quality]
**EN**: Quality guardrails · 质量护栏 — Automated checks catch secrets, broken references, and rule bloat before merge.
**CN**: 合并前拦截密钥、断链与规则膨胀。

### [biz-cross-tool]
**EN**: Cross-tool reach · 跨工具覆盖 — Same packs work for Cursor IDE, Codex CLI, and Claude Code without duplication.
**CN**: 同一套包在多工具复用，避免重复维护。

## Architecture Overview

### [arch-heading]
**EN**: Architecture Overview
**CN**: 架构概览

### [arch-sub-cn]
**EN**: Three-layer progressive disclosure · aligned with multi-tool entry
**CN**: 三层渐进披露 · 与多工具入口对齐

### [layer-arrow]
**EN**: ↓
**CN**: ↓

### [layer-l1]
**EN**: L1
**CN**: L1

### [layer-l1-body]
**EN**: Catalog / discovery — description in SKILL.md frontmatter (~100 tokens). Stable routing surface: what/when/not.
**CN**: 目录 / 发现 — SKILL.md frontmatter 中的 description（约 100 tokens）。稳定路由面：做什么 / 何时 / 不做什么。

### [layer-l2]
**EN**: L2
**CN**: L2

### [layer-l2-body]
**EN**: Pack body — SKILL.md content (<5k tokens / <500 lines): safety, defaults, pointers—not long tutorials.
**CN**: 包主体 — SKILL.md 正文（&lt;5k tokens / &lt;500 行）：安全、默认值、指针——非长篇教程。

### [layer-l3]
**EN**: L3
**CN**: L3

### [layer-l3-body]
**EN**: Deep references — references/*.md loaded only when the router points there (guideline <300 lines each).
**CN**: 深度参考 — 仅当路由指向时加载 references/*.md（建议每篇 &lt;300 行）。

### [cross-tool-label-en]
**EN**: Cross-tool compatibility
**CN**: 跨工具兼容

### [cross-tool-label-cn]
**EN**: Cross-tool entry
**CN**: 跨工具入口

### [tool-cursor-name]
**EN**: Cursor
**CN**: Cursor

### [tool-cursor-hint]
**EN**: Rules precedence: Team → Project → User (official docs).
**CN**: 规则优先级：Team → Project → User（官方文档）。

### [tool-codex-name]
**EN**: Codex
**CN**: Codex

### [tool-codex-hint]
**EN**: AGENTS.md merged default 32 KiB ceiling; root→leaf, later overrides.
**CN**: AGENTS.md 合并默认上限 32 KiB；根到叶，后者覆盖前者。

### [tool-claude-name]
**EN**: Claude Code
**CN**: Claude Code

### [tool-claude-hint]
**EN**: CLAUDE.md guidance <200 lines; supports @import and nested files.
**CN**: CLAUDE.md 指引 &lt;200 行；支持 @import 与嵌套文件。

### [arch-footnote-cli]
**EN**: Cursor CLI does not load IDE plugins—do not assume plugin-only flows in headless automation.
**CN**: Cursor CLI 不加载 IDE 插件——无头自动化场景勿假设仅插件流程。

## Research Highlights

### [research-heading]
**EN**: Research Highlights
**CN**: 调研摘要

### [research-sub-cn]
**EN**: Research summary · five themes
**CN**: 调研摘要 · 五条主线

### [research-card-agent-skills-title]
**EN**: Agent Skills Spec
**CN**: Agent Skills 规范

### [research-card-agent-skills-li-1]
**EN**: Three layers: catalog → SKILL.md → references/ (agentskills.io model).
**CN**: 三层：catalog → SKILL.md → references/（agentskills.io 模型）。

### [research-card-agent-skills-li-2]
**EN**: skills-ref validate rejects unknown top-level keys—extensions belong in metadata.
**CN**: skills-ref validate 拒绝未知顶层键——扩展应放在 metadata。

### [research-card-agent-skills-li-3]
**EN**: 17 example skills in anthropics/skills; oversized SKILL.md is an anti-pattern signal.
**CN**: anthropics/skills 提供 17 个示例；过大的 SKILL.md 是反模式信号。

### [research-card-agent-skills-rec]
**EN**: → Keep SKILL.md a router; depth in references + scripts.
**CN**: → 将 SKILL.md 作为路由；深度放在 references 与 scripts。

### [research-card-cross-tool-title]
**EN**: Cross-Tool Compat
**CN**: 跨工具兼容

### [research-card-cross-tool-li-1]
**EN**: Thin root index + domain bodies to respect Codex merge limits.
**CN**: 薄根索引 + domain 正文，以适配 Codex 合并上限。

### [research-card-cross-tool-li-2]
**EN**: Thin CLAUDE.md that delegates to shared index where appropriate.
**CN**: 精简 CLAUDE.md，在合适处委托给共享索引。

### [research-card-cross-tool-li-3]
**EN**: Team marketplaces are org capabilities—not assumed for everyone.
**CN**: Team marketplace 属于组织级能力——并非人人具备。

### [research-card-cross-tool-rec]
**EN**: → Thin AGENTS + pack SKILL bodies; avoid duplicating methodology at root.
**CN**: → 薄 AGENTS + 各 pack 的 SKILL 正文；避免在根目录重复方法论。

### [research-card-security-title]
**EN**: Security & Safety
**CN**: 安全与合规

### [research-card-security-li-1]
**EN**: Secret/path leakage is a top risk in flow analysis.
**CN**: 密钥/路径泄露是流程分析中的首要风险。

### [research-card-security-li-2]
**EN**: Non-negotiable policies must live in L2, not only L3.
**CN**: 不可妥协的策略必须落在 L2，而非仅 L3。

### [research-card-security-li-3]
**EN**: Official anti-patterns: menu-style options, gotchas only in reference, kitchen-sink skills.
**CN**: 官方反模式：菜单式选项、陷阱仅写在参考里、万能技能包。

### [research-card-security-rec]
**EN**: → Use blocking checklists in L2; plan gitleaks/trufflehog with CI hardening.
**CN**: → 在 L2 使用阻塞式清单；规划 gitleaks/trufflehog 与 CI 加固。

### [research-card-governance-title]
**EN**: Governance
**CN**: 治理

### [research-card-governance-li-1]
**EN**: Pipeline pattern: skills-ref → secret scan → cross-ref → rule budget (staged).
**CN**: 流水线：skills-ref → 密钥扫描 → 交叉引用 → 规则预算（分阶段）。

### [research-card-governance-li-2]
**EN**: MVP: CONTRIBUTING + verify script; hardening: automated secret scanning.
**CN**: MVP：CONTRIBUTING + verify 脚本；加固：自动化密钥扫描。

### [research-card-governance-li-3]
**EN**: Lifecycle: MVP → hardening → long-term schema / multi-pack conflicts.
**CN**: 生命周期：MVP → 加固 → 长期 schema / 多包冲突管理。

### [research-card-governance-rec]
**EN**: → Land CONTRIBUTING + PR checklist with security and ownership early.
**CN**: → 尽早落地 CONTRIBUTING 与 PR 清单，明确安全与归属。

### [research-card-patterns-title]
**EN**: Patterns & Anti-patterns
**CN**: 模式与反模式

### [research-card-patterns-li-1]
**EN**: Suggested flow: Before you start → Defaults → Procedure → When to load references.
**CN**: 建议流程：开始前 → 默认值 → 步骤 → 何时加载 references。

### [research-card-patterns-li-2]
**EN**: Strong patterns: “Use when…”, quick-reference tables, deterministic scripts.
**CN**: 强模式：「Use when…」、速查表、确定性脚本。

### [research-card-patterns-li-3]
**EN**: Avoid rule bloat and non-deterministic disclosure—hurts adoption.
**CN**: 避免规则膨胀与非确定性披露——损害采纳。

### [research-card-patterns-rec]
**EN**: → Enforce consistent references/ naming; keep L2 skimmable.
**CN**: → 统一 references/ 命名；保持 L2 可扫读。

## What We Built

### [built-heading]
**EN**: What We Built
**CN**: 我们做了什么

### [built-sub-cn]
**EN**: Repo layout · local verification · PR split
**CN**: 仓库结构 · 本地校验 · PR 拆分

### [built-tree-wiki-dir]
**EN**: wiki/
**CN**: wiki/

### [built-tree-wiki-note]
**EN**: (open this folder as IDE workspace root)
**CN**: （在 IDE 中以此目录为工作区根目录打开）

### [built-tree-agents]
**EN**: AGENTS.md — 25 lines · cross-tool index
**CN**: AGENTS.md — 25 行 · 跨工具索引

### [built-tree-readme]
**EN**: README.md — 42 lines · quick start & scope
**CN**: README.md — 42 行 · 快速开始与范围

### [built-tree-contributing]
**EN**: CONTRIBUTING.md — 60 lines · checklist & merge order
**CN**: CONTRIBUTING.md — 60 行 · 清单与合并顺序

### [built-tree-claude]
**EN**: CLAUDE.md — thin bootstrap → @AGENTS.md
**CN**: CLAUDE.md — 薄引导 → @AGENTS.md

### [built-tree-agent-general-dir]
**EN**: agent-general/
**CN**: agent-general/

### [built-tree-skill-md]
**EN**: SKILL.md — 84 lines · methodology pack router
**CN**: SKILL.md — 84 行 · 方法论包路由

### [built-tree-references-dir]
**EN**: references/ (design-research, layering, security, …)
**CN**: references/（design-research、layering、security 等）

### [built-tree-rules-dir]
**EN**: rules/ · optional .mdc snippets
**CN**: rules/ · 可选 .mdc 片段

### [built-tree-docs-ci]
**EN**: docs/ci-validation.md — 68 lines · pipeline stages
**CN**: docs/ci-validation.md — 68 行 · 流水线阶段

### [built-tree-verify-script]
**EN**: scripts/verify-public-pack.sh — 506 lines · six checks
**CN**: scripts/verify-public-pack.sh — 506 行 · 六项检查

### [built-tree-templates-dir]
**EN**: templates/ · SKILL + domain-rule scaffolds
**CN**: templates/ · SKILL 与 domain rule 脚手架

### [built-verify-heading]
**EN**: verify-public-pack.sh — six automated checks
**CN**: verify-public-pack.sh — 六项自动化检查

### [built-verify-sub]
**EN**: Six checks match docs/ci-validation.md Stage A.
**CN**: 六项检查与 docs/ci-validation.md Stage A 一致。

### [built-check-1]
**EN**: 1 SKILL frontmatter validation
**CN**: 1 SKILL frontmatter 校验

### [built-check-2]
**EN**: 2 Denylist scan
**CN**: 2 Denylist 扫描

### [built-check-3]
**EN**: 3 Secret surface scan
**CN**: 3 密钥面扫描

### [built-check-4]
**EN**: 4 Resolvable cross-references
**CN**: 4 可解析的交叉引用

### [built-check-5]
**EN**: 5 Cited references exist (non-empty)
**CN**: 5 引用的 references 存在且非空

### [built-check-6]
**EN**: 6 AGENTS.md domain table consistency
**CN**: 6 AGENTS.md 域表一致性

### [built-pr-split]
**EN**: PR split: (1) core layout + first pack → (2) bash verify script + checks → (3) governance docs + templates + thin Claude entry—stacked merge keeps reviews focused.
**CN**: PR 拆分：(1) 核心布局 + 首个 pack → (2) bash verify 脚本 + 检查 → (3) 治理文档 + 模板 + 精简 Claude 入口——堆叠合并保持审查聚焦。

## PR Review Roadmap

### [prs-heading]
**EN**: PR Review Roadmap
**CN**: PR 审阅路线图

### [prs-sub-cn]
**EN**: Merge in order · review focus
**CN**: 按序合并 · 审查焦点

### [prs-merge-order-en]
**EN**: Merge order: #1 → #2 → #3 (stacked)
**CN**: 合并顺序：#1 → #2 → #3（堆叠）

### [prs-merge-order-cn]
**EN**: Merge order · depends on upstream
**CN**: 合并顺序 · 依赖上游

### [pr1-title]
**EN**: PR #1 — Core structure
**CN**: PR #1 — 核心结构

### [pr1-li-1]
**EN**: Workspace layout: AGENTS.md, agent-general/, pack conventions.
**CN**: 工作区布局：AGENTS.md、agent-general/、pack 约定。

### [pr1-li-2]
**EN**: First domain pack + references/ skeleton aligned to L1–L3.
**CN**: 首个 domain pack + 对齐 L1–L3 的 references/ 骨架。

### [pr1-li-3]
**EN**: Review: table in AGENTS, pack naming = SKILL.md name field.
**CN**: 审查要点：AGENTS 中的表、pack 命名与 SKILL.md 的 name 字段一致。

### [pr1-button]
**EN**: Open PR #1
**CN**: 打开 PR #1

### [pr1-lines]
**EN**: 482 lines
**CN**: 482 行

### [pr2-title]
**EN**: PR #2 — Verify script
**CN**: PR #2 — Verify 脚本

### [pr2-li-1]
**EN**: Bash + Python structural checks; optional rg for denylist speed.
**CN**: Bash + Python 结构检查；可选 rg 加速 denylist。

### [pr2-li-2]
**EN**: Aligns local pre-PR flow with documented CI Stage A intent.
**CN**: 与文档中的 CI Stage A 意图对齐本地提 PR 前流程。

### [pr2-li-3]
**EN**: Review: edge cases for frontmatter parsing, cited MVP reference list.
**CN**: 审查要点：frontmatter 解析边界、引用的 MVP 参考列表。

### [pr2-button]
**EN**: Open PR #2
**CN**: 打开 PR #2

### [pr2-lines]
**EN**: 512 lines
**CN**: 512 行

### [pr3-title]
**EN**: PR #3 — Governance + templates
**CN**: PR #3 — 治理与模板

### [pr3-li-1]
**EN**: CONTRIBUTING.md, PR checklist, rule budget targets, new-pack recipe.
**CN**: CONTRIBUTING.md、PR 清单、规则预算目标、新建 pack 配方。

### [pr3-li-2]
**EN**: Templates + docs/ci-validation.md + thin CLAUDE.md.
**CN**: 模板 + docs/ci-validation.md + 精简 CLAUDE.md。

### [pr3-li-3]
**EN**: Review: no secrets/paths; template copy path for future packs.
**CN**: 审查要点：无密钥/路径；未来 pack 的模板复制路径。

### [pr3-button]
**EN**: Open PR #3
**CN**: 打开 PR #3

### [pr3-lines]
**EN**: 397 lines
**CN**: 397 行

## Key Design Decisions

### [decisions-heading]
**EN**: Key Design Decisions
**CN**: 关键设计决策

### [decisions-sub-cn]
**EN**: Key design decisions · click to expand
**CN**: 关键设计决策 · 点击展开

### [decision-1-summary-en]
**EN**: Progressive disclosure — L2 holds non-negotiable safety
**CN**: 渐进披露 — L2 承载不可妥协的安全要点

### [decision-1-summary-cn]
**EN**: Progressive disclosure: L2 holds non-negotiable safety essentials
**CN**: 渐进披露：L2 承载不可妥协的安全要点

### [decision-1-body]
**EN**: Safety policies must be visible in the SKILL.md body (L2), not only in deep references—use checklists and validation loops. L3 is for depth once the task matches a trigger.
**CN**: 安全策略必须在 SKILL.md 正文（L2）可见，而非仅存在于 deep references——使用清单与校验循环。任务匹配触发条件后，再由 L3 展开深度。

### [decision-2-summary-en]
**EN**: Metadata-only extensions for custom keys
**CN**: 自定义扩展仅使用 metadata

### [decision-2-summary-cn]
**EN**: Custom keys only in metadata to keep validators compatible
**CN**: 自定义键仅走 metadata，保持校验器兼容

### [decision-2-body]
**EN**: skills-ref validate rejects unknown top-level YAML keys; team extensions belong under metadata so CI stays aligned with upstream schema behavior.
**CN**: skills-ref validate 拒绝未知顶层 YAML 键；团队扩展应放在 metadata，使 CI 与上游 schema 行为一致。

### [decision-3-summary-en]
**EN**: Team → Project → User merge order
**CN**: Team → Project → User 合并顺序

### [decision-3-summary-cn]
**EN**: Rule merge precedence (aligned with Cursor)
**CN**: 规则合并优先级（Cursor 对齐）

### [decision-3-body]
**EN**: When rules conflict, treat it as a bug. Personal overlays should only affect non-normative preferences—never weaken team-enforced rules. Documented in CONTRIBUTING with link to Cursor rules docs.
**CN**: 规则冲突应视为 bug。个人覆盖仅影响非规范性偏好——不得削弱团队强制规则。在 CONTRIBUTING 中说明并链接 Cursor rules 文档。

### [decision-4-summary-en]
**EN**: Bash-first verify script (minimal toolchain)
**CN**: Bash 优先的 verify 脚本（工具链最小）

### [decision-4-summary-cn]
**EN**: Bash verification script with minimal toolchain
**CN**: Bash 校验脚本，工具链最小化

### [decision-4-body]
**EN**: Stage A uses ./scripts/verify-public-pack.sh with bash, Python 3, and grep—optional ripgrep. Keeps local and future CI behavior aligned without heavy deps; npx skills-ref validate is a separate Stage B when Node is available.
**CN**: Stage A 使用 ./scripts/verify-public-pack.sh，依赖 bash、Python 3 与 grep——可选 ripgrep。在轻依赖下对齐本地与未来 CI；npx skills-ref validate 在具备 Node 时作为独立 Stage B。

### [decision-5-summary-en]
**EN**: Separate AGENTS.md and CLAUDE.md entry points
**CN**: 分离的 AGENTS.md 与 CLAUDE.md 入口

### [decision-5-summary-cn]
**EN**: Split entry: AGENTS.md and CLAUDE.md
**CN**: 分流入口：AGENTS 与 CLAUDE

### [decision-5-body]
**EN**: Single cross-tool index in AGENTS.md; tool-specific bootstraps stay thin. CLAUDE.md delegates via @AGENTS.md so Claude Code routes to the same packs without duplicating long guidance.
**CN**: AGENTS.md 承载单一跨工具索引；各工具引导保持精简。CLAUDE.md 通过 @AGENTS.md 委托，使 Claude Code 路由到同一套包而不重复冗长指引。

## References & Standards

### [references-heading-en]
**EN**: References & Standards
**CN**: 参考与标准

### [references-heading-cn]
**EN**: References & standards
**CN**: 参考标准

### [references-sub-cn]
**EN**: External specs and industry practice (numbered for citation)
**CN**: 外部规范与行业实践（编号便于引用）

### [ref-1]
**EN**: agentskills.io Specification — Open standard for agent skills.
**CN**: agentskills.io Specification — agent skills 开放标准。

### [ref-2]
**EN**: Architecture Decision Records — ADR community hub.
**CN**: Architecture Decision Records — ADR 社区枢纽。

### [ref-3]
**EN**: Anthropic Skills Repository — 17 example skills.
**CN**: Anthropic Skills Repository — 17 个示例 skills。

### [ref-4]
**EN**: Cursor Rules Documentation — Team → Project → User precedence.
**CN**: Cursor Rules Documentation — Team → Project → User 优先级。

### [ref-5]
**EN**: Codex AGENTS.md Guide — 32 KiB merge limit.
**CN**: Codex AGENTS.md Guide — 32 KiB 合并上限。

### [ref-6]
**EN**: Spotify Developer Experience — Developer platform thinking at scale.
**CN**: Spotify Developer Experience — 规模化开发者平台思维。

## Footer

### [footer-back-link]
**EN**: ← Tranxmart Grocery Engineering Hub
**CN**: ← Tranxmart Grocery 工程枢纽

### [footer-last-updated-en]
**EN**: Last updated: 2026-03-20
**CN**: 更新日期：2026-03-20

### [footer-last-updated-cn]
**EN**: Last updated: 2026-03-20
**CN**: 更新日期: 2026-03-20

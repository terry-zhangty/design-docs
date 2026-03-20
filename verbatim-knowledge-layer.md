# Verbatim — Knowledge Layer Presentation v0.2 (knowledge-layer/index.html)

> Edit the CN/EN text below. Preserve the `[section-id]` markers.
> v0.2: Chinese is the primary language. English is secondary.

## Meta

### [meta-title]
**CN**: 知识层 — 团队 Agent 知识体系
**EN**: Knowledge Layer — Team Agent Knowledge System

## Hero

### [hero-title-line1]
**CN**: 知识层
**EN**: Knowledge Layer

### [hero-title-line2]
**CN**: 团队 Agent 知识层
**EN**: Team Agent Knowledge Layer

### [hero-lead]
**CN**: 可移植的 domain pack 与入口文件，供各工具发现；共享方法论，避免在仓库根重复冗长规则。
**EN**: Portable domain packs and entry files agents can discover—shared methodology without duplicating long rules at the repo root.

### [hero-metric-1]
**CN**: 5 个调研方向
**EN**: 5 research areas

### [hero-metric-2]
**CN**: 23 条已索引链接
**EN**: 23 indexed URLs

### [hero-metric-3]
**CN**: 17 个上游示例
**EN**: 17 upstream skills

### [hero-metric-4]
**CN**: 3 个堆叠 PR
**EN**: 3 stacked PRs

## Executive Summary

### [exec-summary-heading]
**CN**: 执行摘要 · 决策与请求一览
**EN**: Executive Summary

### [exec-summary-problem]
**CN**: 知识分散在个人配置，缺少可共享的团队基线。
**EN**: Agent knowledge (rules, skills, methodology) is scattered across personal setups—no portable, sharable team baseline.

### [exec-summary-problem-label]
**CN**: 问题
**EN**: Problem

### [exec-summary-proposal]
**CN**: 三层渐进披露、跨工具兼容与自动化校验。
**EN**: A structured Knowledge Layer following the agentskills.io open specification: three-layer progressive disclosure, cross-tool compatibility (Cursor, Codex, Claude Code), automated validation.

### [exec-summary-proposal-label]
**CN**: 方案
**EN**: Proposal

### [exec-summary-ask]
**CN**: 审阅三个堆叠 PR，MVP 分三次合并。
**EN**: Review 3 stacked PRs (~1200 lines total, split for focused review). MVP lands in 3 merges.

### [exec-summary-ask-label]
**CN**: 请求
**EN**: Ask

### [exec-summary-link-agentskills]
**CN**: agentskills.io（规范链接）
**EN**: agentskills.io (specification link)

## Problem → Solution

### [problem-heading]
**CN**: 问题与对策 · 从分散到结构化
**EN**: Problem → Solution

### [problem-badge-before]
**CN**: 之前
**EN**: Before

### [problem-before-1]
**CN**: 规则与指引分散，难以形成统一的团队基线。
**EN**: Rules and guidance scattered; hard to share a single team baseline.

### [problem-before-2]
**CN**: 各工具缺少统一的 progressive disclosure 形态。
**EN**: No common progressive-disclosure shape across tools.

### [problem-before-3]
**CN**: 个人或机器专属笔记难以作为可移植包流转。
**EN**: Personal or machine-specific notes do not travel as portable packs.

### [problem-badge-after]
**CN**: 之后
**EN**: After

### [problem-after-1]
**CN**: 在工作区根目录下集中 domain pack，并配薄层跨工具索引。
**EN**: Structured domain packs under one workspace root with a thin cross-tool index.

### [problem-after-2]
**CN**: L1→L2→L3 加载：目录提示、`SKILL.md` 路由、按需加载 `references/`。
**EN**: L1→L2→L3 loading: catalog hint, `SKILL.md` router, `references/` on demand.

### [problem-after-3]
**CN**: 跨工具入口：同一套包适配 Cursor、Codex、Claude Code 约定。
**EN**: Cross-tool entry: same packs for Cursor, Codex, and Claude Code conventions.

## Why It Matters

### [business-value-heading]
**CN**: 业务价值 · 速度、质量与范围
**EN**: Why It Matters

### [business-value-1]
**CN**: 新人获得结构化方法，而非依赖口耳相传。
**EN**: New team members get structured methodology instead of tribal knowledge.

### [business-value-1-label]
**CN**: 更快上手
**EN**: Faster onboarding

### [business-value-2]
**CN**: 合并前拦截密钥、断链与规则膨胀。
**EN**: Automated checks catch secrets, broken references, and rule bloat before merge.

### [business-value-2-label]
**CN**: 质量护栏
**EN**: Quality guardrails

### [business-value-3]
**CN**: 同一套包在多工具复用，避免重复维护。
**EN**: Same packs work for Cursor IDE, Codex CLI, and Claude Code without duplication.

### [business-value-3-label]
**CN**: 跨工具覆盖
**EN**: Cross-tool reach

## Architecture Overview

### [architecture-heading]
**CN**: 三层渐进披露 · 与多工具入口对齐
**EN**: Architecture Overview

### [architecture-l1-id]
**EN**: L1

### [architecture-l1-body-en]
**EN**: Catalog / discovery — `description` in `SKILL.md` frontmatter (~100 tokens). Stable routing surface: what/when/not.

### [architecture-l1-body-cn]
**CN**: 目录 / 发现 — `SKILL.md` frontmatter 中的 description（约 100 tokens）。稳定路由面：做什么 / 何时 / 不做什么。

### [architecture-arrow]
**EN**: ↓

### [architecture-l2-id]
**EN**: L2

### [architecture-l2-body-en]
**EN**: Pack body — `SKILL.md` content (<5k tokens / <500 lines): safety, defaults, pointers—not long tutorials.

### [architecture-l2-body-cn]
**CN**: 包主体 — `SKILL.md` 正文（<5k tokens / <500 行）：安全、默认值、指针——非长篇教程。

### [architecture-l3-id]
**EN**: L3

### [architecture-l3-body-en]
**EN**: Deep references — `references/*.md` loaded only when the router points there (guideline <300 lines each).

### [architecture-l3-body-cn]
**CN**: 深度参考 — 仅当路由指向时加载 `references/*.md`（建议每篇 <300 行）。

### [architecture-cross-tool-caption]
**CN**: 跨工具兼容 · 跨工具入口
**EN**: Cross-tool compatibility

### [architecture-tool-cursor-name]
**EN**: Cursor

### [architecture-tool-cursor-hint]
**CN**: 规则优先级：Team → Project → User（官方文档）。
**EN**: Rules precedence: Team → Project → User (official docs).

### [architecture-tool-codex-name]
**EN**: Codex

### [architecture-tool-codex-hint]
**CN**: `AGENTS.md` 合并默认上限 32 KiB；根到叶，后者覆盖前者。
**EN**: `AGENTS.md` merged default 32 KiB ceiling; root→leaf, later overrides.

### [architecture-tool-claude-name]
**EN**: Claude Code

### [architecture-tool-claude-hint]
**CN**: `CLAUDE.md` 指引 <200 行；支持 `@import` 与嵌套文件。
**EN**: `CLAUDE.md` guidance <200 lines; supports `@import` and nested files.

### [architecture-cli-note]
**CN**: Cursor CLI 不加载 IDE 插件——无头自动化场景勿假设仅插件流程。
**EN**: Cursor CLI does not load IDE plugins—do not assume plugin-only flows in headless automation.

## Research Highlights

### [research-heading]
**CN**: 调研摘要 · 五条主线
**EN**: Research Highlights

### [research-card-1-title]
**CN**: Agent Skills 规范
**EN**: Agent Skills Spec

### [research-card-1-li-1]
**CN**: 三层：catalog → `SKILL.md` → `references/`（agentskills.io 模型）。
**EN**: Three layers: catalog → `SKILL.md` → `references/` (agentskills.io model).

### [research-card-1-li-2]
**CN**: `skills-ref validate` 拒绝未知顶层键——扩展应放在 `metadata`。
**EN**: `skills-ref validate` rejects unknown top-level keys—extensions belong in `metadata`.

### [research-card-1-li-3]
**CN**: anthropics/skills 提供 17 个示例；过大的 `SKILL.md` 是反模式信号。
**EN**: 17 example skills in anthropics/skills; oversized `SKILL.md` is an anti-pattern signal.

### [research-card-1-rec]
**CN**: → 将 SKILL.md 作为路由；深度放在 references 与 scripts。
**EN**: → Keep SKILL.md a router; depth in references + scripts.

### [research-card-2-title]
**CN**: 跨工具兼容
**EN**: Cross-Tool Compat

### [research-card-2-li-1]
**CN**: 薄根索引 + domain 正文，以适配 Codex 合并上限。
**EN**: Thin root index + domain bodies to respect Codex merge limits.

### [research-card-2-li-2]
**CN**: 精简 `CLAUDE.md`，在合适处委托给共享索引。
**EN**: Thin `CLAUDE.md` that delegates to shared index where appropriate.

### [research-card-2-li-3]
**CN**: Team marketplace 属于组织级能力——并非人人具备。
**EN**: Team marketplaces are org capabilities—not assumed for everyone.

### [research-card-2-rec]
**CN**: → 薄 AGENTS + 各 pack 的 SKILL 正文；避免在根目录重复方法论。
**EN**: → Thin AGENTS + pack SKILL bodies; avoid duplicating methodology at root.

### [research-card-3-title]
**CN**: 安全与合规
**EN**: Security & Safety

### [research-card-3-li-1]
**CN**: 密钥/路径泄露是流程分析中的首要风险。
**EN**: Secret/path leakage is a top risk in flow analysis.

### [research-card-3-li-2]
**CN**: 不可妥协的策略必须落在 L2，而非仅 L3。
**EN**: Non-negotiable policies must live in L2, not only L3.

### [research-card-3-li-3]
**CN**: 官方反模式：菜单式选项、陷阱仅写在参考里、万能技能包。
**EN**: Official anti-patterns: menu-style options, gotchas only in reference, kitchen-sink skills.

### [research-card-3-rec]
**CN**: → 在 L2 使用阻塞式清单；规划 gitleaks/trufflehog 与 CI 加固。
**EN**: → Use blocking checklists in L2; plan gitleaks/trufflehog with CI hardening.

### [research-card-4-title]
**CN**: 治理
**EN**: Governance

### [research-card-4-li-1]
**CN**: 流水线：skills-ref → 密钥扫描 → 交叉引用 → 规则预算（分阶段）。
**EN**: Pipeline pattern: skills-ref → secret scan → cross-ref → rule budget (staged).

### [research-card-4-li-2]
**CN**: MVP：CONTRIBUTING + verify 脚本；加固：自动化密钥扫描。
**EN**: MVP: CONTRIBUTING + verify script; hardening: automated secret scanning.

### [research-card-4-li-3]
**CN**: 生命周期：MVP → 加固 → 长期 schema / 多包冲突管理。
**EN**: Lifecycle: MVP → hardening → long-term schema / multi-pack conflicts.

### [research-card-4-rec]
**CN**: → 尽早落地 CONTRIBUTING 与 PR 清单，明确安全与归属。
**EN**: → Land CONTRIBUTING + PR checklist with security and ownership early.

### [research-card-5-title]
**CN**: 模式与反模式
**EN**: Patterns & Anti-patterns

### [research-card-5-li-1]
**CN**: 建议流程：开始前 → 默认值 → 步骤 → 何时加载 references。
**EN**: Suggested flow: Before you start → Defaults → Procedure → When to load references.

### [research-card-5-li-2]
**CN**: 强模式：「Use when…」、速查表、确定性脚本。
**EN**: Strong patterns: “Use when…”, quick-reference tables, deterministic scripts.

### [research-card-5-li-3]
**CN**: 避免规则膨胀与非确定性披露——损害采纳。
**EN**: Avoid rule bloat and non-deterministic disclosure—hurts adoption.

### [research-card-5-rec]
**CN**: → 统一 `references/` 命名；保持 L2 可扫读。
**EN**: → Enforce consistent `references/` naming; keep L2 skimmable.

## What We Built

### [built-heading]
**CN**: 我们做了什么 · 仓库结构 · 本地校验 · PR 拆分
**EN**: What We Built

### [built-tree-full]
**As rendered (bilingual line order matches page):**

```
wiki/  (open as IDE workspace root · 在 IDE 中以此目录为工作区根目录打开)
├── AGENTS.md — 25 lines · cross-tool index · 25 行 · 跨工具索引
├── README.md — 42 lines · quick start & scope · 42 行 · 快速开始与范围
├── CONTRIBUTING.md — 60 lines · checklist & merge order · 60 行 · 清单与合并顺序
├── CLAUDE.md — thin bootstrap → @AGENTS.md · 薄引导 → @AGENTS.md
├── agent-general/
│   ├── SKILL.md — 84 lines · methodology pack router · 84 行 · 方法论包路由
│   ├── references/ (design-research, layering, security, … · design-research、layering、security 等)
│   └── rules/ · optional .mdc snippets · 可选 .mdc 片段
├── docs/ci-validation.md — 68 lines · pipeline stages · 68 行 · 流水线阶段
├── scripts/verify-public-pack.sh — 506 lines · six checks · 506 行 · 六项检查
└── templates/ · SKILL + domain-rule scaffolds · SKILL 与 domain rule 脚手架
```

### [built-tree-caption]
**CN**: 在 IDE 中以此目录为工作区根目录打开
**EN**: (open as IDE workspace root)

### [built-tree-line-root]
**CN**: `wiki/`
**EN**: `wiki/`

### [built-tree-agents]
**CN**: 25 行 · 跨工具索引
**EN**: 25 lines · cross-tool index

### [built-tree-readme]
**CN**: 42 行 · 快速开始与范围
**EN**: 42 lines · quick start & scope

### [built-tree-contributing]
**CN**: 60 行 · 清单与合并顺序
**EN**: 60 lines · checklist & merge order

### [built-tree-claude]
**CN**: 薄引导 → @AGENTS.md
**EN**: thin bootstrap → @AGENTS.md

### [built-tree-agent-general-dir]
**CN**: `agent-general/`
**EN**: `agent-general/`

### [built-tree-agent-general-skill]
**CN**: 84 行 · 方法论包路由
**EN**: 84 lines · methodology pack router

### [built-tree-references-dir]
**CN**: design-research、layering、security 等
**EN**: design-research, layering, security, …

### [built-tree-rules-dir]
**CN**: 可选 .mdc 片段
**EN**: optional .mdc snippets

### [built-tree-docs-ci]
**CN**: 68 行 · 流水线阶段
**EN**: 68 lines · pipeline stages

### [built-tree-scripts-verify]
**CN**: 506 行 · 六项检查
**EN**: 506 lines · six checks

### [built-tree-templates]
**CN**: SKILL 与 domain rule 脚手架
**EN**: SKILL + domain-rule scaffolds

### [built-verify-heading]
**CN**: 六项自动化检查
**EN**: six automated checks

### [built-verify-sub]
**CN**: 六项检查与 `docs/ci-validation.md` Stage A 一致。
**EN**: Six checks match `docs/ci-validation.md` Stage A.

### [built-check-1]
**CN**: SKILL frontmatter 校验
**EN**: SKILL frontmatter validation

### [built-check-2]
**CN**: Denylist 扫描
**EN**: Denylist scan

### [built-check-3]
**CN**: 密钥面扫描
**EN**: Secret surface scan

### [built-check-4]
**CN**: 可解析交叉引用
**EN**: Resolvable cross-references

### [built-check-5]
**CN**: 引用 references 存在且非空
**EN**: Cited references exist (non-empty)

### [built-check-6]
**CN**: AGENTS.md 域表一致性
**EN**: AGENTS.md domain table consistency

### [built-pr-split]
**CN**: PR 拆分：(1) 核心布局 + 首个 pack → (2) bash verify 脚本 + 检查 → (3) 治理文档 + 模板 + 精简 Claude 入口——堆叠合并保持审查聚焦。
**EN**: PR split: (1) core layout + first pack → (2) bash verify script + checks → (3) governance docs + templates + thin Claude entry—stacked merge keeps reviews focused.

## PR Review Roadmap

### [prs-heading]
**CN**: 按序合并 · 审查焦点
**EN**: PR Review Roadmap

### [prs-merge-order]
**CN**: 合并顺序: #1 → #2 → #3 (堆叠 · 依赖上游)
**EN**: Merge order: #1 → #2 → #3 (stacked · depends on upstream)

### [prs-1-title]
**CN**: PR #1 — 核心结构
**EN**: PR #1 — Core structure

### [prs-1-li-1]
**CN**: 工作区布局：`AGENTS.md`、`agent-general/`、pack 约定。
**EN**: Workspace layout: `AGENTS.md`, `agent-general/`, pack conventions.

### [prs-1-li-2]
**CN**: 首个 domain pack + 对齐 L1–L3 的 `references/` 骨架。
**EN**: First domain pack + `references/` skeleton aligned to L1–L3.

### [prs-1-li-3]
**CN**: 审查：AGENTS 中的表、pack 命名与 `SKILL.md` 的 `name` 字段一致。
**EN**: Review: table in AGENTS, pack naming = `SKILL.md` `name` field.

### [prs-1-btn]
**CN**: 打开 PR #1
**EN**: Open PR #1

### [prs-1-lines]
**CN**: 482 行
**EN**: 482 lines

### [prs-2-title]
**CN**: PR #2 — Verify 脚本
**EN**: PR #2 — Verify script

### [prs-2-li-1]
**CN**: Bash + Python 结构检查；可选 `rg` 加速 denylist。
**EN**: Bash + Python structural checks; optional `rg` for denylist speed.

### [prs-2-li-2]
**CN**: 与文档中的 CI Stage A 意图对齐本地提 PR 前流程。
**EN**: Aligns local pre-PR flow with documented CI Stage A intent.

### [prs-2-li-3]
**CN**: 审查：frontmatter 解析边界、引用的 MVP 参考列表。
**EN**: Review: edge cases for frontmatter parsing, cited MVP reference list.

### [prs-2-btn]
**CN**: 打开 PR #2
**EN**: Open PR #2

### [prs-2-lines]
**CN**: 512 行
**EN**: 512 lines

### [prs-3-title]
**CN**: PR #3 — 治理与模板
**EN**: PR #3 — Governance + templates

### [prs-3-li-1]
**CN**: `CONTRIBUTING.md`、PR 清单、规则预算目标、新建 pack 配方。
**EN**: `CONTRIBUTING.md`, PR checklist, rule budget targets, new-pack recipe.

### [prs-3-li-2]
**CN**: 模板 + `docs/ci-validation.md` + 精简 `CLAUDE.md`。
**EN**: Templates + `docs/ci-validation.md` + thin `CLAUDE.md`.

### [prs-3-li-3]
**CN**: 审查：无密钥/路径；未来 pack 的模板复制路径。
**EN**: Review: no secrets/paths; template copy path for future packs.

### [prs-3-btn]
**CN**: 打开 PR #3
**EN**: Open PR #3

### [prs-3-lines]
**CN**: 397 行
**EN**: 397 lines

## Key Design Decisions

### [decisions-heading]
**CN**: 关键设计决策 · 点击展开
**EN**: Key Design Decisions

### [decisions-acc-1-summary-cn]
**CN**: 渐进披露：L2 承载不可妥协的安全要点
**EN**: Progressive disclosure — L2 holds non-negotiable safety

### [decisions-acc-1-body]
**CN**: 安全策略必须在 `SKILL.md` 正文（L2）可见，而非仅存在于 deep references——使用清单与校验循环。任务匹配触发条件后，再由 L3 展开深度。
**EN**: Safety policies must be visible in the `SKILL.md` body (L2), not only in deep references—use checklists and validation loops. L3 is for depth once the task matches a trigger.

### [decisions-acc-2-summary-cn]
**CN**: 自定义键仅走 metadata，保持校验器兼容
**EN**: Metadata-only extensions for custom keys

### [decisions-acc-2-body]
**CN**: `skills-ref validate` 拒绝未知顶层 YAML 键；团队扩展应放在 `metadata`，使 CI 与上游 schema 行为一致。
**EN**: `skills-ref validate` rejects unknown top-level YAML keys; team extensions belong under `metadata` so CI stays aligned with upstream schema behavior.

### [decisions-acc-3-summary-cn]
**CN**: 规则合并优先级（Cursor 对齐）
**EN**: Team → Project → User merge order

### [decisions-acc-3-body]
**CN**: 规则冲突应视为 bug。个人覆盖仅影响非规范性偏好——不得削弱团队强制规则。在 CONTRIBUTING 中说明并链接 Cursor rules 文档。
**EN**: When rules conflict, treat it as a bug. Personal overlays should only affect non-normative preferences—never weaken team-enforced rules. Documented in CONTRIBUTING with link to Cursor rules docs.

### [decisions-acc-4-summary-cn]
**CN**: Bash 校验脚本，工具链最小化
**EN**: Bash-first verify script (minimal toolchain)

### [decisions-acc-4-body]
**CN**: Stage A 使用 `./scripts/verify-public-pack.sh`，依赖 bash、Python 3 与 grep——可选 ripgrep。在轻依赖下对齐本地与未来 CI；`npx skills-ref validate` 在具备 Node 时作为独立 Stage B。
**EN**: Stage A uses `./scripts/verify-public-pack.sh` with bash, Python 3, and grep—optional ripgrep. Keeps local and future CI behavior aligned without heavy deps; `npx skills-ref validate` is a separate Stage B when Node is available.

### [decisions-acc-5-summary-cn]
**CN**: 分流入口：AGENTS 与 CLAUDE
**EN**: Separate `AGENTS.md` and `CLAUDE.md` entry points

### [decisions-acc-5-body]
**CN**: `AGENTS.md` 承载单一跨工具索引；各工具引导保持精简。`CLAUDE.md` 通过 `@AGENTS.md` 委托，使 Claude Code 路由到同一套包而不重复冗长指引。
**EN**: Single cross-tool index in `AGENTS.md`; tool-specific bootstraps stay thin. `CLAUDE.md` delegates via `@AGENTS.md` so Claude Code routes to the same packs without duplicating long guidance.

### [decisions-details-marker-closed]
**EN**: +

### [decisions-details-marker-open]
**EN**: −

## References & Standards

### [references-heading]
**CN**: 参考标准 · 外部规范与行业实践（编号便于引用）
**EN**: References & Standards

### [references-1]
**Link text**: agentskills.io Specification
**CN**: agent skills 开放标准。
**EN**: Open standard for agent skills.

### [references-2]
**Link text**: Architecture Decision Records
**CN**: ADR 社区枢纽。
**EN**: ADR community hub.

### [references-3]
**Link text**: Anthropic Skills Repository
**CN**: 17 个示例 skills。
**EN**: 17 example skills.

### [references-4]
**Link text**: Cursor Rules Documentation
**CN**: Team → Project → User 优先级。
**EN**: Team → Project → User precedence.

### [references-5]
**Link text**: Codex AGENTS.md Guide
**CN**: 32 KiB 合并上限。
**EN**: 32 KiB merge limit.

### [references-6]
**Link text**: Spotify Developer Experience
**CN**: 规模化开发者平台思维。
**EN**: Developer platform thinking at scale.

## Footer

### [footer-hub-link]
**CN**: ← Tranxmart Grocery 工程枢纽
**EN**: ← Tranxmart Grocery Engineering Hub

### [footer-updated]
**CN**: 更新日期: 2026-03-20
**EN**: Last updated: 2026-03-20

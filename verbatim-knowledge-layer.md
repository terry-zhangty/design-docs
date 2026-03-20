# Verbatim — Knowledge Layer Presentation (knowledge-layer/index.html)

> Edit the EN/CN text below. Preserve the `[section-id]` markers.

## Document

### [document-title]
**EN**: Knowledge Layer — Team Agent Knowledge System
**CN**: （待翻译）

## Hero

### [hero-title-line1]
**EN**: Knowledge Layer
**CN**: （无）

### [hero-title-line2]
**EN**: （待翻译）
**CN**: 团队 Agent 知识层

### [hero-sub-en]
**EN**: Portable domain packs and entry files agents can discover—shared methodology without duplicating long rules at the repo root.
**CN**: （无）

### [hero-sub-cn]
**EN**: （待翻译）
**CN**: 可移植的域包与入口文件，供各工具发现；避免在仓库根重复冗长规则。

### [metric-research-areas]
**EN**: 5 research areas
**CN**: （待翻译）

### [metric-indexed-urls]
**EN**: 23 indexed reference URLs
**CN**: （待翻译）

### [metric-upstream-skills]
**EN**: 17 upstream example skills
**CN**: （待翻译）

### [metric-stacked-prs]
**EN**: 3 stacked PRs
**CN**: （待翻译）

## Executive Summary

### [exec-section-heading]
**EN**: Executive Summary
**CN**: （待翻译）

### [exec-section-sub-cn]
**EN**: （待翻译）
**CN**: 执行摘要 · 决策与请求一览

### [exec-problem]
**EN**: Problem · 问题 — Agent knowledge (rules, skills, methodology) is scattered across personal setups—no portable, sharable team baseline.
**CN**: 知识分散在个人配置，缺少可共享的团队基线。

### [exec-proposal]
**EN**: Proposal · 方案 — A structured Knowledge Layer following the agentskills.io open specification: three-layer progressive disclosure, cross-tool compatibility (Cursor, Codex, Claude Code), automated validation.
**CN**: 三层渐进披露、跨工具兼容与自动化校验。

### [exec-ask]
**EN**: Ask · 请求 — Review 3 stacked PRs (~1200 lines total, split for focused review). MVP lands in 3 merges.
**CN**: 审阅三个堆叠 PR，MVP 分三次合并。

## Problem → Solution

### [problem-solution-heading]
**EN**: Problem → Solution
**CN**: （待翻译）

### [problem-solution-sub-cn]
**EN**: （待翻译）
**CN**: 问题与对策 · 从分散到结构化

### [before-badge]
**EN**: Before
**CN**: （待翻译）

### [before-heading-cn]
**EN**: （待翻译）
**CN**: 之前

### [before-li-1]
**EN**: Rules and guidance scattered; hard to share a single team baseline.
**CN**: （待翻译）

### [before-li-2]
**EN**: No common progressive-disclosure shape across tools.
**CN**: （待翻译）

### [before-li-3]
**EN**: Personal or machine-specific notes do not travel as portable packs.
**CN**: （待翻译）

### [after-badge]
**EN**: After
**CN**: （待翻译）

### [after-heading-cn]
**EN**: （待翻译）
**CN**: 之后

### [after-li-1]
**EN**: Structured domain packs under one workspace root with a thin cross-tool index.
**CN**: （待翻译）

### [after-li-2]
**EN**: L1→L2→L3 loading: catalog hint, SKILL.md router, references/ on demand.
**CN**: （待翻译）

### [after-li-3]
**EN**: Cross-tool entry: same packs for Cursor, Codex, and Claude Code conventions.
**CN**: （待翻译）

## Why It Matters · Business Value

### [business-heading-en]
**EN**: Why It Matters
**CN**: （待翻译）

### [business-heading-cn]
**EN**: （待翻译）
**CN**: 业务价值

### [business-sub-cn]
**EN**: （待翻译）
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
**CN**: （待翻译）

### [arch-sub-cn]
**EN**: （待翻译）
**CN**: 三层渐进披露 · 与多工具入口对齐

### [layer-arrow]
**EN**: ↓
**CN**: （无）

### [layer-l1]
**EN**: L1
**CN**: （无）

### [layer-l1-body]
**EN**: Catalog / discovery — description in SKILL.md frontmatter (~100 tokens). Stable routing surface: what/when/not.
**CN**: （待翻译）

### [layer-l2]
**EN**: L2
**CN**: （无）

### [layer-l2-body]
**EN**: Pack body — SKILL.md content (<5k tokens / <500 lines): safety, defaults, pointers—not long tutorials.
**CN**: （待翻译）

### [layer-l3]
**EN**: L3
**CN**: （无）

### [layer-l3-body]
**EN**: Deep references — references/*.md loaded only when the router points there (guideline <300 lines each).
**CN**: （待翻译）

### [cross-tool-label-en]
**EN**: Cross-tool compatibility
**CN**: （待翻译）

### [cross-tool-label-cn]
**EN**: （待翻译）
**CN**: 跨工具入口

### [tool-cursor-name]
**EN**: Cursor
**CN**: （无）

### [tool-cursor-hint]
**EN**: Rules precedence: Team → Project → User (official docs).
**CN**: （待翻译）

### [tool-codex-name]
**EN**: Codex
**CN**: （无）

### [tool-codex-hint]
**EN**: AGENTS.md merged default 32 KiB ceiling; root→leaf, later overrides.
**CN**: （待翻译）

### [tool-claude-name]
**EN**: Claude Code
**CN**: （无）

### [tool-claude-hint]
**EN**: CLAUDE.md guidance <200 lines; supports @import and nested files.
**CN**: （待翻译）

### [arch-footnote-cli]
**EN**: Cursor CLI does not load IDE plugins—do not assume plugin-only flows in headless automation.
**CN**: （待翻译）

## Research Highlights

### [research-heading]
**EN**: Research Highlights
**CN**: （待翻译）

### [research-sub-cn]
**EN**: （待翻译）
**CN**: 调研摘要 · 五条主线

### [research-card-agent-skills-title]
**EN**: Agent Skills Spec
**CN**: （待翻译）

### [research-card-agent-skills-li-1]
**EN**: Three layers: catalog → SKILL.md → references/ (agentskills.io model).
**CN**: （待翻译）

### [research-card-agent-skills-li-2]
**EN**: skills-ref validate rejects unknown top-level keys—extensions belong in metadata.
**CN**: （待翻译）

### [research-card-agent-skills-li-3]
**EN**: 17 example skills in anthropics/skills; oversized SKILL.md is an anti-pattern signal.
**CN**: （待翻译）

### [research-card-agent-skills-rec]
**EN**: → Keep SKILL.md a router; depth in references + scripts.
**CN**: （待翻译）

### [research-card-cross-tool-title]
**EN**: Cross-Tool Compat
**CN**: （待翻译）

### [research-card-cross-tool-li-1]
**EN**: Thin root index + domain bodies to respect Codex merge limits.
**CN**: （待翻译）

### [research-card-cross-tool-li-2]
**EN**: Thin CLAUDE.md that delegates to shared index where appropriate.
**CN**: （待翻译）

### [research-card-cross-tool-li-3]
**EN**: Team marketplaces are org capabilities—not assumed for everyone.
**CN**: （待翻译）

### [research-card-cross-tool-rec]
**EN**: → Thin AGENTS + pack SKILL bodies; avoid duplicating methodology at root.
**CN**: （待翻译）

### [research-card-security-title]
**EN**: Security & Safety
**CN**: （待翻译）

### [research-card-security-li-1]
**EN**: Secret/path leakage is a top risk in flow analysis.
**CN**: （待翻译）

### [research-card-security-li-2]
**EN**: Non-negotiable policies must live in L2, not only L3.
**CN**: （待翻译）

### [research-card-security-li-3]
**EN**: Official anti-patterns: menu-style options, gotchas only in reference, kitchen-sink skills.
**CN**: （待翻译）

### [research-card-security-rec]
**EN**: → Use blocking checklists in L2; plan gitleaks/trufflehog with CI hardening.
**CN**: （待翻译）

### [research-card-governance-title]
**EN**: Governance
**CN**: （待翻译）

### [research-card-governance-li-1]
**EN**: Pipeline pattern: skills-ref → secret scan → cross-ref → rule budget (staged).
**CN**: （待翻译）

### [research-card-governance-li-2]
**EN**: MVP: CONTRIBUTING + verify script; hardening: automated secret scanning.
**CN**: （待翻译）

### [research-card-governance-li-3]
**EN**: Lifecycle: MVP → hardening → long-term schema / multi-pack conflicts.
**CN**: （待翻译）

### [research-card-governance-rec]
**EN**: → Land CONTRIBUTING + PR checklist with security and ownership early.
**CN**: （待翻译）

### [research-card-patterns-title]
**EN**: Patterns & Anti-patterns
**CN**: （待翻译）

### [research-card-patterns-li-1]
**EN**: Suggested flow: Before you start → Defaults → Procedure → When to load references.
**CN**: （待翻译）

### [research-card-patterns-li-2]
**EN**: Strong patterns: “Use when…”, quick-reference tables, deterministic scripts.
**CN**: （待翻译）

### [research-card-patterns-li-3]
**EN**: Avoid rule bloat and non-deterministic disclosure—hurts adoption.
**CN**: （待翻译）

### [research-card-patterns-rec]
**EN**: → Enforce consistent references/ naming; keep L2 skimmable.
**CN**: （待翻译）

## What We Built

### [built-heading]
**EN**: What We Built
**CN**: （待翻译）

### [built-sub-cn]
**EN**: （待翻译）
**CN**: 仓库结构 · 本地校验 · PR 拆分

### [built-tree-wiki-dir]
**EN**: wiki/
**CN**: （无）

### [built-tree-wiki-note]
**EN**: (open this folder as IDE workspace root)
**CN**: （待翻译）

### [built-tree-agents]
**EN**: AGENTS.md — 25 lines · cross-tool index
**CN**: （待翻译）

### [built-tree-readme]
**EN**: README.md — 42 lines · quick start & scope
**CN**: （待翻译）

### [built-tree-contributing]
**EN**: CONTRIBUTING.md — 60 lines · checklist & merge order
**CN**: （待翻译）

### [built-tree-claude]
**EN**: CLAUDE.md — thin bootstrap → @AGENTS.md
**CN**: （待翻译）

### [built-tree-agent-general-dir]
**EN**: agent-general/
**CN**: （无）

### [built-tree-skill-md]
**EN**: SKILL.md — 84 lines · methodology pack router
**CN**: （待翻译）

### [built-tree-references-dir]
**EN**: references/ (design-research, layering, security, …)
**CN**: （待翻译）

### [built-tree-rules-dir]
**EN**: rules/ · optional .mdc snippets
**CN**: （待翻译）

### [built-tree-docs-ci]
**EN**: docs/ci-validation.md — 68 lines · pipeline stages
**CN**: （待翻译）

### [built-tree-verify-script]
**EN**: scripts/verify-public-pack.sh — 506 lines · six checks
**CN**: （待翻译）

### [built-tree-templates-dir]
**EN**: templates/ · SKILL + domain-rule scaffolds
**CN**: （待翻译）

### [built-verify-heading]
**EN**: verify-public-pack.sh — six automated checks
**CN**: （待翻译）

### [built-verify-sub]
**EN**: Six checks match docs/ci-validation.md Stage A.
**CN**: （待翻译）

### [built-check-1]
**EN**: 1 SKILL frontmatter validation
**CN**: （待翻译）

### [built-check-2]
**EN**: 2 Denylist scan
**CN**: （待翻译）

### [built-check-3]
**EN**: 3 Secret surface scan
**CN**: （待翻译）

### [built-check-4]
**EN**: 4 Resolvable cross-references
**CN**: （待翻译）

### [built-check-5]
**EN**: 5 Cited references exist (non-empty)
**CN**: （待翻译）

### [built-check-6]
**EN**: 6 AGENTS.md domain table consistency
**CN**: （待翻译）

### [built-pr-split]
**EN**: PR split: (1) core layout + first pack → (2) bash verify script + checks → (3) governance docs + templates + thin Claude entry—stacked merge keeps reviews focused.
**CN**: （待翻译）

## PR Review Roadmap

### [prs-heading]
**EN**: PR Review Roadmap
**CN**: （待翻译）

### [prs-sub-cn]
**EN**: （待翻译）
**CN**: 按序合并 · 审查焦点

### [prs-merge-order-en]
**EN**: Merge order: #1 → #2 → #3 (stacked)
**CN**: （待翻译）

### [prs-merge-order-cn]
**EN**: （待翻译）
**CN**: 合并顺序 · 依赖上游

### [pr1-title]
**EN**: PR #1 — Core structure
**CN**: （待翻译）

### [pr1-li-1]
**EN**: Workspace layout: AGENTS.md, agent-general/, pack conventions.
**CN**: （待翻译）

### [pr1-li-2]
**EN**: First domain pack + references/ skeleton aligned to L1–L3.
**CN**: （待翻译）

### [pr1-li-3]
**EN**: Review: table in AGENTS, pack naming = SKILL.md name field.
**CN**: （待翻译）

### [pr1-button]
**EN**: Open PR #1
**CN**: （待翻译）

### [pr1-lines]
**EN**: 482 lines
**CN**: （无）

### [pr2-title]
**EN**: PR #2 — Verify script
**CN**: （待翻译）

### [pr2-li-1]
**EN**: Bash + Python structural checks; optional rg for denylist speed.
**CN**: （待翻译）

### [pr2-li-2]
**EN**: Aligns local pre-PR flow with documented CI Stage A intent.
**CN**: （待翻译）

### [pr2-li-3]
**EN**: Review: edge cases for frontmatter parsing, cited MVP reference list.
**CN**: （待翻译）

### [pr2-button]
**EN**: Open PR #2
**CN**: （待翻译）

### [pr2-lines]
**EN**: 512 lines
**CN**: （无）

### [pr3-title]
**EN**: PR #3 — Governance + templates
**CN**: （待翻译）

### [pr3-li-1]
**EN**: CONTRIBUTING.md, PR checklist, rule budget targets, new-pack recipe.
**CN**: （待翻译）

### [pr3-li-2]
**EN**: Templates + docs/ci-validation.md + thin CLAUDE.md.
**CN**: （待翻译）

### [pr3-li-3]
**EN**: Review: no secrets/paths; template copy path for future packs.
**CN**: （待翻译）

### [pr3-button]
**EN**: Open PR #3
**CN**: （待翻译）

### [pr3-lines]
**EN**: 397 lines
**CN**: （无）

## Key Design Decisions

### [decisions-heading]
**EN**: Key Design Decisions
**CN**: （待翻译）

### [decisions-sub-cn]
**EN**: （待翻译）
**CN**: 关键设计决策 · 点击展开

### [decision-1-summary-en]
**EN**: Progressive disclosure — L2 holds non-negotiable safety
**CN**: （无）

### [decision-1-summary-cn]
**EN**: （待翻译）
**CN**: 渐进披露：L2 承载不可妥协的安全要点

### [decision-1-body]
**EN**: Safety policies must be visible in the SKILL.md body (L2), not only in deep references—use checklists and validation loops. L3 is for depth once the task matches a trigger.
**CN**: （待翻译）

### [decision-2-summary-en]
**EN**: Metadata-only extensions for custom keys
**CN**: （无）

### [decision-2-summary-cn]
**EN**: （待翻译）
**CN**: 自定义键仅走 metadata，保持校验器兼容

### [decision-2-body]
**EN**: skills-ref validate rejects unknown top-level YAML keys; team extensions belong under metadata so CI stays aligned with upstream schema behavior.
**CN**: （待翻译）

### [decision-3-summary-en]
**EN**: Team → Project → User merge order
**CN**: （无）

### [decision-3-summary-cn]
**EN**: （待翻译）
**CN**: 规则合并优先级（Cursor 对齐）

### [decision-3-body]
**EN**: When rules conflict, treat it as a bug. Personal overlays should only affect non-normative preferences—never weaken team-enforced rules. Documented in CONTRIBUTING with link to Cursor rules docs.
**CN**: （待翻译）

### [decision-4-summary-en]
**EN**: Bash-first verify script (minimal toolchain)
**CN**: （无）

### [decision-4-summary-cn]
**EN**: （待翻译）
**CN**: Bash 校验脚本，工具链最小化

### [decision-4-body]
**EN**: Stage A uses ./scripts/verify-public-pack.sh with bash, Python 3, and grep—optional ripgrep. Keeps local and future CI behavior aligned without heavy deps; npx skills-ref validate is a separate Stage B when Node is available.
**CN**: （待翻译）

### [decision-5-summary-en]
**EN**: Separate AGENTS.md and CLAUDE.md entry points
**CN**: （无）

### [decision-5-summary-cn]
**EN**: （待翻译）
**CN**: 分流入口：AGENTS 与 CLAUDE

### [decision-5-body]
**EN**: Single cross-tool index in AGENTS.md; tool-specific bootstraps stay thin. CLAUDE.md delegates via @AGENTS.md so Claude Code routes to the same packs without duplicating long guidance.
**CN**: （待翻译）

## References & Standards

### [references-heading-en]
**EN**: References & Standards
**CN**: （待翻译）

### [references-heading-cn]
**EN**: （待翻译）
**CN**: 参考标准

### [references-sub-cn]
**EN**: （待翻译）
**CN**: 外部规范与行业实践（编号便于引用）

### [ref-1]
**EN**: agentskills.io Specification — Open standard for agent skills.
**CN**: （待翻译）

### [ref-2]
**EN**: Architecture Decision Records — ADR community hub.
**CN**: （待翻译）

### [ref-3]
**EN**: Anthropic Skills Repository — 17 example skills.
**CN**: （待翻译）

### [ref-4]
**EN**: Cursor Rules Documentation — Team → Project → User precedence.
**CN**: （待翻译）

### [ref-5]
**EN**: Codex AGENTS.md Guide — 32 KiB merge limit.
**CN**: （待翻译）

### [ref-6]
**EN**: Spotify Developer Experience — Developer platform thinking at scale.
**CN**: （待翻译）

## Footer

### [footer-back-link]
**EN**: ← Tranxmart Grocery Engineering Hub
**CN**: （待翻译）

### [footer-last-updated-en]
**EN**: Last updated: 2026-03-20
**CN**: （待翻译）

### [footer-last-updated-cn]
**EN**: （待翻译）
**CN**: 更新日期: 2026-03-20

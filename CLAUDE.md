# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static HTML design documentation site for the Tranxmart engineering team. No build system, no dependencies — files are served directly or opened in a browser.

## Structure

- `index.html` — Landing page listing all design docs
- `mock-control-cli/` — Design doc for the Mock Control CLI tool
  - `index.html` — Full implementation roadmap page (self-contained)
  - `architecture.drawio`, `phase1.drawio`, `phase2.drawio` — Source diagram files

## Diagrams

Diagrams are draw.io (`.drawio`) files. They are embedded directly into the HTML pages using the `<div class="mxgraph" data-mxgraph="...">` pattern, with the diagram XML inlined as a JSON-encoded string in the `data-mxgraph` attribute. The draw.io viewer JS (`https://viewer.diagrams.net/js/viewer-static.min.js`) renders them client-side.

To update a diagram: edit the `.drawio` file in draw.io, then export the XML and update the `data-mxgraph` attribute in the corresponding HTML file.

## Visual Conventions

All pages share a consistent dark theme using CSS custom properties:

```css
--bg: #0f172a       /* page background */
--surface: #1e293b  /* card/panel background */
--border: #334155
--text: #e2e8f0
--muted: #94a3b8
--accent: #38bdf8   /* primary accent (sky blue) */
```

Phase 1 uses `--accent1: #38bdf8` (sky blue) and Phase 2 uses `--accent2: #a78bfa` (purple) for visual differentiation.

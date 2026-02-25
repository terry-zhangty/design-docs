# AGENTS.md

## Cursor Cloud specific instructions

This is a **static HTML documentation site** with no dependencies, no build system, no package manager, no tests, and no lint configuration.

### Running the dev server

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a browser. The site consists of:
- `index.html` — landing page listing design documents
- `mock-control-cli/index.html` — detailed design doc with embedded draw.io diagrams

### Notes

- The draw.io diagrams load via an external CDN (`viewer.diagrams.net`). Internet access is required for diagrams to render; text content works without it.
- There is no `package.json`, `requirements.txt`, `Makefile`, or any dependency file. No install step is needed.
- There are no automated tests or lint checks to run.

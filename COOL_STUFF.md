# Cool Stuff Selection

A running list of tools and projects worth keeping an eye on.

## Developer tools

### [Graphify](https://github.com/Graphify-Labs/graphify)

Turns a codebase (plus its docs, SQL schemas, configs and PDFs) into a queryable knowledge graph. Works as a `/graphify` skill for AI coding assistants like Claude Code, Cursor, Codex and Gemini CLI.

- Parses code locally with tree-sitter (~40 languages), no LLM needed for code
- Tags each link as `EXTRACTED` or `INFERRED`
- Ranks "god nodes", detects communities, and supports `query`, `path` and `explain`
- Outputs an interactive `graph.html`, a `GRAPH_REPORT.md` summary and `graph.json`
- Python 3.10+, Apache-2.0 / MIT

Quick start:

```bash
uv tool install graphifyy   # note the double "y"
graphify install
# then, inside your AI assistant:
/graphify .
```

**Why it's useful here:** once this repo has real trading code, a graph of it would make it easier to see how strategies, data feeds and order logic connect.

## Matt Hull

Software craftsman practicing agentic engineering. I harness LLM agents to implement robust software systems, carefully defining the boundary between agent autonomy and human judgment. Agents accelerate implementation, but I don't merge what I can't explain.

Deep background in using Rails, Postgres, and Python to build SaaS products and B2C mobile products. I scale systems by helping development teams be kind to their databases.

### What I'm building

- **[athanor](https://github.com/matthull/athanor)** — Multi-agent orchestration on Claude Code. Supervisor and worker agents, goals that survive dead sessions, and independent review from fresh context before anything ships. I ran it daily against a production codebase for several months; my merged-PR throughput went up substantially and the work held up in normal code review. I'm not putting a multiplier on that — ask me and I'll walk you through what I tracked. Go.
- **[my-skills](https://github.com/matthull/my-skills)** — Claude Code skills on a plugin architecture I came up with: universal logic in the skill, project bindings and personal preferences injected as separate layers, so the same skills work across projects or teams.
- **[egregore-mcp](https://github.com/matthull/egregore-mcp)** — MCP server for session logging, meeting bots, and Slack integration: the context my agents need that isn't in the repo. FastMCP/Python.

### Key design decisions

- **Spec-driven.** I write specifications precise enough that a coding agent can execute them and a reviewing agent can check the result.
- **Fresh context as verification.** Accumulated builder context self-confirms. A fresh agent reviewing the same work catches what the builder rationalized away. This is structural, not a quality preference.

Ruby/Rails · Python · PostgreSQL · Go · Claude Code & MCP

[LinkedIn](https://www.linkedin.com/in/matt-hull)

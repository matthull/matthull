## Matt Hull

Software craftsman practicing agentic engineering. I harness LLM agents to implement robust software systems, carefully defining the boundary between agent autonomy and human judgment. Agents accelerate implementation, but I don't merge what I can't explain.

Deep background in using Rails, Postgres, and Python to build SaaS products and B2C mobile products. I scale systems by helping development teams be kind to their databases.

**Looking for:** remote senior backend · Rails or Python, Postgres-heavy SaaS · Central Time

### Track record

24 years shipping software. Principal Engineer at Coffee Meets Bagel (5 years — Postgres at scale for a dating app with millions of users), senior IC at UserEvidence (Rails/Postgres B2B SaaS), data engineering and architecture across healthcare (80+ hospitals) and industrial IoT. At CMB I owned data-tier architecture for all backend projects, trained the team on database access patterns that kept the system healthy under growth, and tuned the query plans when they stopped scaling. Most recent hard result: replaced keyword search with a hybrid pipeline, more than doubling relevance (NDCG 0.33 → 0.71 on a 92-query evaluation set).

### What I'm building

- **[athanor](https://github.com/matthull/athanor)** — Multi-agent orchestration on Claude Code. Supervisor and worker agents, goals that survive dead sessions, and independent review from fresh context before anything ships. I ran it daily against a production codebase for several months; my merged-PR throughput went up substantially and the work held up in normal code review. I'm not putting a multiplier on that — ask me and I'll walk you through what I tracked. Go.
- **[my-skills](https://github.com/matthull/my-skills)** — Claude Code skills on a plugin architecture I came up with: universal logic in the skill, project bindings and personal preferences injected as separate layers, so the same skills work across projects or teams.

### Key design decisions

- **Spec-driven.** I write specifications precise enough that a coding agent can execute them and a reviewing agent can check the result.
- **Fresh context as verification.** Accumulated builder context self-confirms. A fresh agent reviewing the same work catches what the builder rationalized away. This is structural, not a quality preference.

Ruby/Rails · Python · PostgreSQL · Go · Claude Code & MCP

[LinkedIn](https://www.linkedin.com/in/matt-hull)

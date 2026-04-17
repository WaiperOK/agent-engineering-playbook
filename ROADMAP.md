# Roadmap

This repository is intended to become a long-form series on practical AI agent engineering.

## Planned posts

Published:

- [Agent Security for Real Teams](./posts/agent-security-for-real-teams.md)

Upcoming:

1. **Prompt Injection Against Tool-Using Agents**
   How hostile docs, issues, web pages, and MCP sources hijack agent behavior.
2. **Secrets, Tokens, and Environment Isolation**
   How to stop agents from casually touching `.env`, cloud credentials, and production-adjacent systems.
3. **Safe MCP Design**
   Trust boundaries, narrow tools, allowlists, and how to avoid turning integrations into attack surfaces.
4. **Code Review for Agent Output**
   What humans should still review manually, what can be automated, and how to catch high-cost regressions early.
5. **When to Spawn More Agents and When Not To**
   The economics of parallelism, fan-out, and isolated contexts.
6. **Context Architecture**
   A deeper guide to `AGENTS.md`, `CLAUDE.md`, skills, hooks, imports, and cache-friendly prompt layout.
7. **Benchmarks That Actually Matter**
   Why teams should track merge quality, retries, clarification turns, and bug escape rate instead of vibes.

## Editorial direction

The style of this repo will stay practical:

- fewer slogans
- more workflow patterns
- more threat models
- more cost discipline
- more examples teams can copy

## Repo shape

The repository starts as a strong `README` because that is the fastest path to discoverability on GitHub.

Over time it can grow into:

- `/posts/` for standalone essays
- `/examples/` for sample `AGENTS.md`, `CLAUDE.md`, hooks, and skills
- `/checklists/` for operational hardening guides

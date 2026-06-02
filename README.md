# Aun Stack

Aun Stack is an enterprise AgentOps control plane for multi-agent AI workflows.

It is designed to let teams use the best AI agent for each job—Codex, Claude Code, Cursor, Gemini, Copilot, local agents, or future agents—while keeping context, decisions, permissions, handoffs, and audit trails in one controlled layer.

## Positioning

**Swap agents, not workflows.**

Aun Stack is not a single MCP server and not a replacement for coding agents. It is the operating layer around them.

- Use Codex for small PR implementation.
- Use Claude Code for design, review, hooks, and subagents.
- Use other agents where they fit.
- Keep project context, decisions, handoffs, permissions, and audit logs consistent.

## Core Value

**Small PR, continuous context.**

AI coding agents can make changes quickly, but teams need those changes to stay small, reviewable, and connected across PRs, agents, and sessions.

Aun Stack aims to preserve:

- Feature goals
- PR scope
- Decisions and assumptions
- Human approvals
- Pending tasks
- Review results
- Next PR handoffs
- Audit logs

## Modules

| Module | Role |
|---|---|
| Aun Relay | Human and agent coordination layer |
| Aun Router | Task-to-agent routing and agent selection |
| Aun Gate | Permissions, approvals, and audit gateway |
| Kusabi Memory | Decision, assumption, and context anchoring |
| Tasuki Handoff | Safe handoff and resume between agents/PRs |
| Shirube Structure | Feature, task, PR, and dependency structuring |
| Hibiki Context | Context aggregation and re-presentation |

## 2027 Exit Thesis

The target is not to sell a small tool. The target is to build a sellable AgentOps business by June 2027.

Aun Stack should become valuable to:

- AI implementation companies
- DX consulting companies
- software development companies
- SaaS companies
- SIers
- R&D companies
- field-industry software vendors

The initial target is to reach a state where the business could be sold for at least 100 million JPY, while keeping the option to retain, partially sell, or raise strategic capital if growth exceeds expectations.

## Current Strategic Focus

1. Build short-term revenue through AI second opinions, AI-driven development diagnosis, and weekly AI implementation lead work.
2. Use those engagements to discover real AgentOps requirements.
3. Build Aun Stack through internal use first.
4. Convert internal operation into productizable workflows.
5. Create case studies and buyer relationships before June 2027.

## First Internal Use Case

Aun Stack will first be used to manage its own development:

1. Define a Feature Goal.
2. Break it into small PRs.
3. Assign each PR to the best agent.
4. Capture decisions and assumptions.
5. Preserve context across PRs.
6. Review and approve changes.
7. Generate the next handoff packet.

## Working Principle

Build to sell. Operate to keep.

The business should be organized so it can be acquired, while also becoming profitable enough that selling is optional.

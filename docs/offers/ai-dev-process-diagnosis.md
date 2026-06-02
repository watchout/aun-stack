# Offer: AI-Driven Development Process Diagnosis

## One-Line Offer

We help development teams adopt AI coding agents without losing reviewability, context, permissions, or project continuity.

Japanese:

Codex / Claude Code / Cursor などのAI開発エージェントを使いながら、小さなPR・文脈維持・レビュー・権限管理・判断履歴を両立する開発運用を設計します。

## Target Customers

- software development companies
- SaaS companies
- AI development teams
- small SIers
- teams adopting Codex, Claude Code, Cursor, Gemini CLI, or similar tools
- DX companies with internal development teams

## Customer Pain

AI coding agents can speed up development, but teams often face:

- PRs become too large
- review quality drops
- context disappears between sessions
- agents repeat the same mistakes
- requirements drift
- decisions are not recorded
- human approval points are unclear
- multiple agents cannot hand off work cleanly
- GitHub issues and PRs are not structured for AI collaboration

## Price

- Light diagnosis: 200,000 JPY
- Standard diagnosis: 300,000 - 500,000 JPY
- Roadmap + templates: 500,000 JPY+

## Scope

### Included

- current workflow interview
- repository and GitHub workflow review
- current AI tool usage review
- small PR strategy design
- agent role mapping
- issue/PR template recommendations
- review workflow recommendations
- decision log / handoff recommendations
- 30-day AI development process roadmap

### Excluded

- full implementation of the development process
- ongoing engineering management
- production incident response
- unlimited code review
- responsibility for all AI-generated code

## Deliverables

1. Current Workflow Assessment
2. AI Agent Usage Map
3. Small PR Strategy
4. Review and Approval Flow
5. Handoff Packet Format
6. GitHub Issue / PR Template Drafts
7. 30-Day Improvement Roadmap

## Diagnosis Framework

### 1. Current Development Flow
- How are requirements defined?
- How are issues created?
- How are PRs reviewed?
- How are decisions recorded?
- How are releases managed?

### 2. AI Agent Usage
- Which agents are used?
- Which tasks are assigned to AI?
- How are outputs reviewed?
- How are prompts and context reused?
- What fails repeatedly?

### 3. PR Continuity
- Can one feature be split into small PRs?
- Is the overall feature goal preserved?
- Does each PR have a clear scope and out-of-scope section?
- Are next steps generated after review?

### 4. Human Control
- Which actions need approval?
- Which files or systems are sensitive?
- Which agent permissions should be limited?
- How should audit logs be kept?

### 5. Agent Fit
- Codex for small implementation PRs
- Claude Code for design, review, hooks, and subagents
- Cursor for IDE-based iteration
- Local agents for sensitive environments
- Other tools as needed

## Core Principle

**Small PR, continuous context.**

AI development should be fast, but each change must remain small, reviewable, and connected to the larger goal.

## Conversion Path

This offer can lead to:

- weekly AI implementation lead
- Aun Stack internal PoC
- PR Continuity implementation
- AgentOps roadmap
- ongoing advisory

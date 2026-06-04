# AGENTS.md

This repository is `watchout/aun-stack`.

Aun Stack is the product and implementation repository for the AgentOps control plane.

Rasen (`watchout/rasen`) is the growth and revenue orchestration repository.

## Repository Role

Use this separation:

```text
watchout/rasen
  = offer, growth, LP, content, lead magnets, sales scripts, campaigns, feedback loop

watchout/aun-stack
  = AgentOps product, implementation, product requirements, architecture, delivery assets
```

Do not duplicate all Rasen sales files here.

Instead, use `rasen.yaml` to connect this repo to Rasen.

## Current Commercial Direction

The current commercial wedge is:

```text
AI案件 受注前リスク診断
```

The productizable direction is:

```text
AI Deal OS / AI案件 収益化OS
```

This means Aun Stack should support AI implementation companies, DX companies, development companies, and related partners that want to sell and deliver AI projects without losing context, scope, decisions, approvals, and auditability.

## Files To Read First

When an agent works in this repository, read in this order:

1. `README.md`
2. `rasen.yaml`
3. `AGENTS.md`
4. Relevant files in `docs/`
5. If growth-side context is needed, read `watchout/rasen/AGENTS.md`
6. Then read `watchout/rasen/products/ai-risk-diagnosis/product.yaml`
7. Then read `watchout/rasen/products/ai-risk-diagnosis/offer.md`

## How To Use Rasen

If the task is about:

- offer design
- LP copy
- lead magnet
- X posts
- sales scripts
- campaigns
- weekly review
- pricing messages

then use Rasen as the source of truth.

If the task is about:

- architecture
- AgentOps modules
- feature requirements
- product implementation
- issue breakdown
- PR handoff
- approval flow
- audit logs
- context memory

then work in Aun Stack.

## Translating Rasen Into Aun Stack Work

When Rasen creates a sales-side requirement, convert it into product requirements here.

Example:

```text
Rasen says:
AI案件診断では、見積漏れ・追加質問・スコープ外を48時間で整理する。

Aun Stack should ask:
- What data model stores diagnosis items?
- What workflow captures assumptions and approvals?
- What template generates the diagnosis report?
- What audit trail proves how the recommendation was made?
- What handoff packet moves from sales review to implementation planning?
```

## Human Approval Gates

Do not finalize or publish the following without human approval:

- pricing
- guarantees
- legal language
- customer names
- sales proposals
- DM messages
- contracts
- invoices
- public case studies
- claims about verified results

## Current Productization Hypothesis

Aun Stack becomes valuable when it turns repeated AI second-opinion and AI implementation review work into productized workflows:

```text
AI案件 Intake
  ↓
Risk Review
  ↓
Scope Boundary
  ↓
Estimate Checklist
  ↓
Human Approval Gate
  ↓
Proposal Handoff
  ↓
Implementation Planning
  ↓
Delivery Audit Trail
```

## Do Not Do

- Do not turn Aun Stack into a generic AI consulting notes repo.
- Do not move Rasen's campaign files here.
- Do not make unverifiable claims.
- Do not automate client outreach from this repository.
- Do not implement MCP or SaaS features before the workflow is validated.

## Definition of Done For This Repo's Commercial Alignment

This repository is commercially aligned when:

- `rasen.yaml` exists
- Aun Stack has a documented AI Deal OS thesis
- AI案件診断 insights can become product requirements
- AgentOps modules map to sales-to-delivery workflows
- human approval and audit trail requirements are clear

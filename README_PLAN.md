# Black Signal Lab README Plan

## Purpose

This document plans the public README for `ThresholdOps/black-signal-lab`.

It defines the intended README structure, short public wording, examples section, reading path, and non-goals.

This is a planning artifact. It does not replace `README.md` by itself.

## README Objective

The README should quickly explain:

- what Black Signal Lab is,
- why it exists,
- what examples it contains,
- how to read the repository,
- what is intentionally out of scope,
- where human review and decision ownership sit.

The README should be clear for a first-time reader and precise enough not to overclaim.

## Target Reader

The README should work for:

- technology leaders,
- process governance readers,
- AI workflow reviewers,
- portfolio reviewers,
- people evaluating controlled AI-assisted work.

It should not assume that the reader already knows SAMAEL, The Daltons, NOESIS, or any private project context.

## Proposed README Structure

Recommended structure:

```text
# Black Signal Lab

1. Short public introduction
2. What this lab is
3. Why it exists
4. Core method statement
5. Repository reading path
6. Case studies / examples
7. Core documents
8. What is intentionally out of scope
9. Privacy and data boundary
10. Current status
```

## Draft Short Intro

Suggested public intro:

```text
Black Signal Lab is a public portfolio workspace for controlled AI-assisted work.

It shows how AI-supported workflows can be structured around reviewable artifacts, evidence, validation gates, source-of-truth boundaries, and human decision ownership.

The repository contains public-safe method documents, sanitized case studies, and example artifacts. It does not contain private project data, production configuration, or claims of autonomous decision-making.
```

## What This Lab Is

Suggested wording:

```text
Black Signal Lab is a public methodology and portfolio repository.

It demonstrates how messy inputs, AI-assisted outputs, system signals, and workflow decisions can be turned into reviewable artifacts with explicit boundaries.

The lab is focused on governance: what input is trusted, what output is provisional, what evidence supports a claim, who reviews, who decides, and what must remain private.
```

## Why It Exists

Suggested wording:

```text
AI work does not become trustworthy because a model produces fluent text.

In organizational work, the harder questions are operational: what artifact should be produced, what evidence supports it, who reviews it, who accepts responsibility, and where the source of truth lives.

Black Signal Lab exists to show public-safe patterns for answering those questions.
```

## Core Method Statement

Suggested wording:

```text
AI output is not truth.
AI output is not a decision.
AI output is review material.

Human reviewers own acceptance, rejection, escalation, and recorded decisions.
```

This statement should remain near the top of the README.

## Repository Reading Path

Recommended reading path:

1. `LAB_CHARTER.md` — lab purpose and boundaries.
2. `PUBLIC_POSITIONING.md` — public audience and value proposition.
3. `REPOSITORY_MAP.md` — structure and navigation.
4. `METHOD_PRINCIPLES.md` — method principles.
5. `ARTIFACT_LIFECYCLE.md` — how inputs become reviewable artifacts.
6. `REVIEW_MATERIAL_DOCTRINE.md` — why AI output remains review material.
7. `HUMAN_DECISION_GATE.md` — how review material becomes accepted, rejected, escalated, deferred, or recorded.
8. `GOVERNANCE_VOCABULARY.md` — core terms.
9. `EXAMPLE_CATALOG.md` — public-safe examples and method mapping.
10. `PORTFOLIO_BRIEF.md` — one-page overview.

The README should not become a full file inventory. `REPOSITORY_MAP.md` is responsible for detailed navigation.

## Examples Section

Suggested wording:

```text
The repository uses three public-safe case studies:

- SAMAEL — controlled AI-assisted task execution through task contracts, bounded work packets, validation gates, and human handoff.
- The Daltons — evidence-backed meeting and document analysis using source profiles, evidence maps, decision logs, open questions, validation, and human review.
- NOESIS — telemetry and interpretation governance using source-of-truth boundaries, event contracts, interpretation reports, observability gates, and human-readable reporting.
```

Each example should point to its case-study README, public boundary file, example artifacts, and `EXAMPLE_CATALOG.md`.

## Core Documents Section

Suggested grouping:

```text
Identity and scope:
- LAB_CHARTER.md
- PUBLIC_POSITIONING.md
- REPOSITORY_MAP.md

Method:
- METHOD_PRINCIPLES.md
- ARTIFACT_LIFECYCLE.md
- REVIEW_MATERIAL_DOCTRINE.md
- HUMAN_DECISION_GATE.md
- GOVERNANCE_VOCABULARY.md

Examples:
- EXAMPLE_CATALOG.md
- case-studies/samael/
- case-studies/the-daltons/
- case-studies/noesis/

Review and learning:
- reviews/
- training/critical-thinking-for-ai-workflows/
```

## Non-Goals Section

Suggested wording:

```text
Black Signal Lab is not:

- a production system,
- a software implementation reference,
- a SaaS product,
- a game-development backlog,
- an autonomous agent platform,
- a private project dump,
- a replacement for human review,
- a claim that AI can approve consequential work,
- a repository for confidential material.
```

This section should stay direct because it prevents scope drift.

## Privacy and Data Boundary Section

Suggested wording:

```text
This repository uses only public, synthetic, anonymized, or fully sanitized material.

It does not include personal data, confidential organizational data, real meeting transcripts, real project documents, real task logs, real runtime logs, internal locations, production configuration, or copied internal project files.
```

## Public-Safe Wording Rules

Prefer wording such as:

- reviewable artifacts,
- evidence-backed analysis,
- validation gates,
- human review,
- decision ownership,
- source-of-truth boundary,
- public-safe examples,
- sanitized case studies,
- controlled AI-assisted work.

Avoid wording such as:

- autonomous decision-making,
- production-ready system,
- AI-approved,
- verified by AI,
- official record without review,
- private implementation exposed,
- complete operational architecture.

## Suggested README Closing Status

Suggested wording:

```text
Current status: public portfolio baseline.

The repository demonstrates controlled AI-assisted work through public-safe method documents, case studies, and examples. It is not presented as a production system or autonomous decision platform.
```

## README Maintenance Rules

When updating the README:

- keep it shorter than the repository map,
- link deeper documents instead of duplicating them,
- keep the core method statement visible,
- keep examples short,
- keep non-goals explicit,
- do not introduce private project context,
- do not claim production readiness,
- do not imply autonomous authority,
- make the first-time reader path obvious.

## Acceptance Criteria

A README aligned with this plan should let a first-time reader answer:

- What is Black Signal Lab?
- Why does it exist?
- What method does it demonstrate?
- What examples are included?
- What should I read first?
- What is out of scope?
- What private material is excluded?
- Where does human decision ownership sit?

If the README cannot answer these questions quickly, it needs revision.

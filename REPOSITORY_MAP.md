# Black Signal Lab Repository Map

## Purpose

This document maps the public structure of the Black Signal Lab repository.

It explains how a first-time reader should navigate the repository, what each major area is for, and where the public/private boundary sits.

The map is a navigation and governance artifact. It is not a technical architecture document, implementation reference, or product roadmap.

## Repository Role

Black Signal Lab is a public methodology and portfolio repository for controlled AI-assisted work.

The repository demonstrates how AI-assisted workflows can be structured around artifacts, validation gates, source-of-truth boundaries, public-safe examples, human review, and human decision gates.

The repository does not contain private implementation details, production configuration, real operational logs, real project documents, or confidential material.

## Recommended Navigation

For a first-time reader, use this path:

1. `README.md` — main entry point and reading path.
2. `LAB_CHARTER.md` — lab purpose, boundaries, human review principle.
3. `PUBLIC_POSITIONING.md` — public audience, value proposition, project positioning.
4. `REPOSITORY_MAP.md` — repository structure, navigation paths, and boundary notes.
5. `METHOD_PRINCIPLES.md` — method principles for controlled AI-assisted work.
6. `ARTIFACT_LIFECYCLE.md` — how inputs become reviewable artifacts.
7. `REVIEW_MATERIAL_DOCTRINE.md` — why AI output remains review material.
8. `HUMAN_DECISION_GATE.md` — how review material becomes accepted, rejected, escalated, deferred, or recorded.
9. `GOVERNANCE_VOCABULARY.md` — core terms used across Black Signal Lab.
10. `EXAMPLE_CATALOG.md` — public-safe examples and method mapping.
11. `PORTFOLIO_BRIEF.md` — compact portfolio overview.
12. `frameworks/black-signal-governance-model.md` — shared governance model.
13. `case-studies/` — public-safe case studies and examples.
14. `diagrams/` — visual overview of the portfolio and workflows.
15. `training/critical-thinking-for-ai-workflows/` — workshop-style learning module.
16. `reviews/` — public-baseline review material.
17. `STATUS.md` — current baseline and development stance.

`README_PLAN.md` is a README maintenance planning artifact. It is useful when changing the README, but it is not required for first-time reading.

`GITHUB_HYGIENE_REVIEW.md` is a repository hygiene review artifact. It records review findings and cleanup actions, but it is not part of the core reading path.

`LICENSE_DECISION.md` records the current license posture and reuse boundary. It is important for reuse questions, but it is not a method primer.

## Top-Level Entry Points

### `README.md`

The main public entry point.

It explains what Black Signal Lab is, links to the core documents, summarizes the portfolio map, and states the privacy/data boundary.

### `README_PLAN.md`

The README planning artifact.

It defines the intended README structure, short public introduction, examples section, non-goals section, privacy wording, and README maintenance rules.

Use this document when changing the README. It is not a substitute for the README itself.

### `LICENSE_DECISION.md`

The license decision artifact.

It records that no public reuse license has been selected yet, explains no-license implications, compares high-level license options, and defines the current reuse boundary.

Use this document when answering reuse, contribution, or license-status questions.

### `LAB_CHARTER.md`

The lab charter.

It defines the purpose of Black Signal Lab, what it is and is not, the target audience, the human review principle, artifact principle, boundary principle, and public-safe scope.

### `PUBLIC_POSITIONING.md`

The public positioning document.

It explains audience, value proposition, project positioning, tone, non-goals, and public-safety boundary.

### `METHOD_PRINCIPLES.md`

The method principles document.

It defines Artifact, Review, Evidence, Human Decision, Boundary, and Anti-Overclaim principles.

### `ARTIFACT_LIFECYCLE.md`

The artifact lifecycle document.

It describes how messy inputs become reviewable artifacts and move through validation, review, decision, storage, and improvement.

### `REVIEW_MATERIAL_DOCTRINE.md`

The review material doctrine.

It defines the status of AI output, reviewer responsibility, human decision ownership, and what must not be automated.

### `HUMAN_DECISION_GATE.md`

The human decision gate.

It defines what AI may prepare, what AI must not decide, who reviews, who accepts responsibility, how decisions are recorded, and when escalation is required.

### `GOVERNANCE_VOCABULARY.md`

The governance vocabulary.

It defines the core terms used across Black Signal Lab: artifact, review material, evidence, decision, interpretation, source of truth, validation, human gate, and operating model.

### `EXAMPLE_CATALOG.md`

The example catalog.

It lists the public-safe examples used by Black Signal Lab and maps SAMAEL, The Daltons, and NOESIS to the method principles, artifact lifecycle, and public/private boundary.

### `GITHUB_HYGIENE_REVIEW.md`

The GitHub hygiene review.

It records the repository hygiene review, including README clarity, repository structure, public/private boundary, license status, placeholder review, sensitive-content limitation, and cleanup action list.

### `PORTFOLIO_BRIEF.md`

A short portfolio overview.

It summarizes what the repository demonstrates and introduces the three case studies.

### `STATUS.md`

The current public baseline status.

It states the repository baseline, current contents, what the repository is and is not, known hygiene notes, license/reuse status, and current development stance.

## Folder Map

```text
/
├── README.md
├── README_PLAN.md
├── LICENSE_DECISION.md
├── LAB_CHARTER.md
├── PUBLIC_POSITIONING.md
├── REPOSITORY_MAP.md
├── METHOD_PRINCIPLES.md
├── ARTIFACT_LIFECYCLE.md
├── REVIEW_MATERIAL_DOCTRINE.md
├── HUMAN_DECISION_GATE.md
├── GOVERNANCE_VOCABULARY.md
├── EXAMPLE_CATALOG.md
├── GITHUB_HYGIENE_REVIEW.md
├── PORTFOLIO_BRIEF.md
├── STATUS.md
│
├── frameworks/
│   └── black-signal-governance-model.md
│
├── case-studies/
│   ├── samael/
│   ├── the-daltons/
│   └── noesis/
│
├── diagrams/
├── training/
└── reviews/
```

This is a public-facing map, not a full file inventory.

## Folder Roles

### `frameworks/`

Shared governance models and conceptual patterns.

Current primary artifact:

- `black-signal-governance-model.md`

### `case-studies/`

Public-safe examples of the shared method in different workflow contexts.

Current case studies:

- `samael/` — bounded AI-assisted task execution.
- `the-daltons/` — meeting and document analysis with evidence mapping.
- `noesis/` — telemetry, interpretation, source-of-truth boundaries, and observability gates.

Each case study should keep a visible public/private boundary note.

### `diagrams/`

Public-safe Mermaid diagrams.

The diagrams are high-level governance views, not implementation diagrams.

### `training/`

Public-safe learning material.

Current module:

- `critical-thinking-for-ai-workflows/`

This is a workshop-style portfolio module, not an accredited course, certification, or official training program.

### `reviews/`

Public-baseline review material.

Reviews are used to check clarity, navigation, public safety, overclaiming risk, and baseline coherence.

## Public/Private Boundary

Black Signal Lab is a public repository.

It may include:

- public methodology,
- synthetic examples,
- anonymized or fully sanitized examples,
- public-safe case studies,
- conceptual frameworks,
- reviewable artifact patterns,
- governance and operating-model descriptions,
- high-level diagrams,
- public-facing planning artifacts that improve navigation or maintenance.

It must not include private project material, confidential organizational content, real operational records, production configuration, or sensitive account or infrastructure details.

The public repository shows the method, not the private machinery.

## License / Reuse Boundary

No public reuse license has been selected yet.

This repository is public for portfolio review and method inspection. Do not assume permission to copy, modify, redistribute, package, or commercially reuse its contents unless a license or written permission explicitly grants that right.

Use `LICENSE_DECISION.md` for license-status questions.

## What Belongs in This Repository

Add material only when it strengthens at least one of these public paths:

- lab identity and boundaries,
- public positioning,
- repository navigation,
- README planning and maintenance,
- license/reuse status clarity,
- method principles,
- artifact lifecycle,
- review doctrine,
- human decision gate,
- governance vocabulary,
- example catalog,
- governance model,
- case-study clarity,
- visual navigation,
- public-safe training,
- baseline review,
- public/private boundary discipline.

Good additions are small, reviewable, public-safe, and connected to an existing path.

## What Does Not Belong in This Repository

Do not add material that makes the repository look like:

- a production system,
- a software implementation reference,
- a SaaS product,
- a game-development backlog,
- an uncontrolled agent platform,
- a private project dump,
- a broad knowledge base without a clear reader path.

## Navigation Paths by Reader Need

### Fast overview

1. `README.md`
2. `PORTFOLIO_BRIEF.md`
3. `diagrams/README.md`

### Purpose and boundaries

1. `LAB_CHARTER.md`
2. `PUBLIC_POSITIONING.md`
3. `REPOSITORY_MAP.md`
4. `STATUS.md`

### Method and governance model

1. `METHOD_PRINCIPLES.md`
2. `ARTIFACT_LIFECYCLE.md`
3. `REVIEW_MATERIAL_DOCTRINE.md`
4. `HUMAN_DECISION_GATE.md`
5. `GOVERNANCE_VOCABULARY.md`
6. `EXAMPLE_CATALOG.md`
7. `frameworks/black-signal-governance-model.md`

### Concrete examples

1. `EXAMPLE_CATALOG.md`
2. `case-studies/samael/`
3. `case-studies/the-daltons/`
4. `case-studies/noesis/`

### README maintenance

1. `README_PLAN.md`
2. `REPOSITORY_MAP.md`
3. `STATUS.md`

### License / reuse questions

1. `LICENSE_DECISION.md`
2. `README.md`
3. `STATUS.md`

### Baseline review and quality control

1. `STATUS.md`
2. `GITHUB_HYGIENE_REVIEW.md`
3. `reviews/public-baseline-outsider-review-v0-1.md`
4. `REPOSITORY_MAP.md`

## Missing or Deferred Documents

Known follow-up candidates:

- publication boundary artifact if publication workflow needs its own explicit gate,
- dedicated sensitive-content review before wider external promotion,
- actual `LICENSE` file only if a later license decision explicitly approves one.

Do not add these by default.

## Maintenance Principle

The repository should remain small enough to inspect and structured enough to trust.

When adding or changing content, ask:

- Does this strengthen an existing navigation path?
- Is it public-safe?
- Does it avoid production-readiness claims?
- Does it preserve the distinction between reviewable signal and final authority?
- Does it make the repository easier to understand, not merely larger?

If the answer is unclear, do not add the material yet.

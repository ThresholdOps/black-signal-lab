# Black Signal Lab Repository Map

## Purpose

This document maps the public structure of the Black Signal Lab repository.

It explains how a first-time reader should navigate the repository, what each major area is for, and where the public/private, license/reuse, publication, closure, and portfolio-activation boundaries sit.

The map is a navigation and governance artifact. It is not a technical architecture document, implementation reference, or product roadmap.

## Repository Role

Black Signal Lab is a public methodology and active portfolio repository for controlled AI-assisted work.

The repository demonstrates how AI-assisted workflows can be structured around artifacts, validation gates, source-of-truth boundaries, public-safe examples, human review, and human decision gates.

The v0.1 method baseline is closed and frozen. Portfolio use is active under BSL-02.

The repository does not contain private implementation details, production configuration, real operational logs, real project documents, or confidential material.

## Recommended Navigation

For a first-time reader, use this path:

1. `README.md` — main entry point and active portfolio status.
2. `LAB_CHARTER.md` — lab purpose and boundaries.
3. `PUBLIC_POSITIONING.md` — audience and public value proposition.
4. `REPOSITORY_MAP.md` — repository structure and navigation.
5. `METHOD_PRINCIPLES.md` — method principles.
6. `ARTIFACT_LIFECYCLE.md` — movement from input to review, decision, and storage.
7. `REVIEW_MATERIAL_DOCTRINE.md` — status of AI output as review material.
8. `HUMAN_DECISION_GATE.md` — accountable human decision boundary.
9. `GOVERNANCE_VOCABULARY.md` — core terms.
10. `EXAMPLE_CATALOG.md` — public-safe examples and method mapping.
11. `PORTFOLIO_BRIEF.md` — compact overview.
12. `frameworks/black-signal-governance-model.md` — shared governance model.
13. `case-studies/` — SAMAEL, The Daltons, and NOESIS.
14. `diagrams/` — public-safe visual views.
15. `training/critical-thinking-for-ai-workflows/` — workshop-style learning material.
16. `STATUS.md` — current baseline and active portfolio state.

Supporting governance, maintenance, and activation artifacts:

- `README_PLAN.md`
- `GITHUB_HYGIENE_REVIEW.md`
- `LICENSE_DECISION.md`
- `SENSITIVE_CONTENT_REVIEW.md`
- `PUBLICATION_BOUNDARY.md`
- `BASELINE_CLOSURE_REVIEW.md`
- `PORTFOLIO_ACTIVATION.md`

These documents support maintenance, review, reuse questions, publication decisions, baseline closure, and active portfolio use. They are not required as the first method-reading path.

## Top-Level Entry Points

### `README.md`

The main public entry point.

It explains what Black Signal Lab is, links to the core documents, summarizes the case studies, and states the active portfolio, privacy, publication, and license/reuse boundaries.

### `LAB_CHARTER.md`

Defines the purpose of Black Signal Lab, what it is and is not, the target audience, the human review principle, artifact principle, boundary principle, and public-safe scope.

### `PUBLIC_POSITIONING.md`

Defines audience, value proposition, project positioning, tone, non-goals, and public-safety boundary.

### `METHOD_PRINCIPLES.md`

Defines Artifact, Review, Evidence, Human Decision, Boundary, and Anti-Overclaim principles.

### `ARTIFACT_LIFECYCLE.md`

Describes how inputs become reviewable artifacts and move through validation, human review, decision, storage, and improvement.

### `REVIEW_MATERIAL_DOCTRINE.md`

Defines the status of AI output, reviewer responsibility, human decision ownership, and what must not be automated.

### `HUMAN_DECISION_GATE.md`

Defines what AI may prepare, what AI must not decide, who reviews, who accepts responsibility, how decisions are recorded, and when escalation is required.

### `GOVERNANCE_VOCABULARY.md`

Defines artifact, review material, evidence, decision, interpretation, source of truth, validation, human gate, and operating model.

### `EXAMPLE_CATALOG.md`

Maps SAMAEL, The Daltons, and NOESIS to the method principles, lifecycle, and public/private boundaries.

### `PORTFOLIO_BRIEF.md`

Provides a short portfolio overview and introduces the three case studies.

### `README_PLAN.md`

Defines the intended README structure, public introduction, examples section, non-goals, privacy wording, and maintenance rules.

### `GITHUB_HYGIENE_REVIEW.md`

Records README clarity, repository structure, public/private boundary, license status, placeholder review, and cleanup actions.

### `LICENSE_DECISION.md`

Records that no public reuse license has been selected, explains the current reuse boundary, and identifies future decision triggers.

### `SENSITIVE_CONTENT_REVIEW.md`

Records the public repository sensitive-content review and its limitations.

### `PUBLICATION_BOUNDARY.md`

Defines active controlled portfolio publication surfaces, required caveats, claim boundaries, link context, and publication review gates.

### `BASELINE_CLOSURE_REVIEW.md`

Records the cross-document closure review and the decision to close and freeze public portfolio baseline v0.1.

### `PORTFOLIO_ACTIVATION.md`

Records the BSL-02 decision to activate the closed v0.1 baseline as a controlled public portfolio.

It contains approved portfolio framing, a reusable public launch note, suitable uses, remaining boundaries, and activation review gates.

### `STATUS.md`

States the current contents, frozen baseline state, active portfolio state, publication posture, license/reuse posture, and development stance.

## Folder Map

```text
/
├── README.md
├── README_PLAN.md
├── LAB_CHARTER.md
├── PUBLIC_POSITIONING.md
├── REPOSITORY_MAP.md
├── METHOD_PRINCIPLES.md
├── ARTIFACT_LIFECYCLE.md
├── REVIEW_MATERIAL_DOCTRINE.md
├── HUMAN_DECISION_GATE.md
├── GOVERNANCE_VOCABULARY.md
├── EXAMPLE_CATALOG.md
├── PORTFOLIO_BRIEF.md
├── GITHUB_HYGIENE_REVIEW.md
├── LICENSE_DECISION.md
├── SENSITIVE_CONTENT_REVIEW.md
├── PUBLICATION_BOUNDARY.md
├── BASELINE_CLOSURE_REVIEW.md
├── PORTFOLIO_ACTIVATION.md
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

Shared governance models and cross-case conceptual patterns.

### `case-studies/`

Public-safe examples of the shared method:

- `samael/` — bounded AI-assisted task execution.
- `the-daltons/` — meeting and document analysis with evidence mapping.
- `noesis/` — telemetry, interpretation, source-of-truth boundaries, and observability gates.

Each case study has a visible public-boundary document.

### `diagrams/`

Public-safe Mermaid diagrams. These are governance views, not implementation or infrastructure diagrams.

### `training/`

Public-safe learning material. The current module is workshop-style portfolio material, not an accredited course or official training program.

### `reviews/`

Public-baseline quality reviews used to check clarity, navigation, public safety, overclaiming risk, and coherence.

## Public/Private Boundary

The repository may include:

- public methodology,
- synthetic examples,
- anonymized or fully sanitized examples,
- public-safe case studies,
- conceptual frameworks,
- reviewable artifact patterns,
- governance and operating-model descriptions,
- high-level diagrams,
- public-facing review, maintenance, and activation artifacts.

It must not include private project material, confidential organizational content, real operational records, production configuration, or sensitive account and infrastructure details.

The public repository shows the method, not the private machinery.

## License / Reuse Boundary

No public reuse license has been selected.

The repository is public for portfolio review and method inspection. Do not assume permission to copy, modify, redistribute, package, or commercially reuse its contents unless a license or written permission explicitly grants that right.

Use `LICENSE_DECISION.md` for reuse questions.

## Publication Boundary

Active controlled public portfolio visibility is allowed.

Professional portfolio links and controlled public references are approved when `PORTFOLIO_ACTIVATION.md` and `PUBLICATION_BOUNDARY.md` framing is preserved.

Broad publication, contribution invitation, commercial packaging, or open-source/open-content framing is not approved.

## Baseline Closure Boundary

Public portfolio baseline v0.1 is closed and frozen.

Future baseline additions should be treated as:

- small baseline maintenance,
- a specifically approved public-safe improvement,
- or work for a new versioned baseline.

Use `BASELINE_CLOSURE_REVIEW.md` for the closure decision.

## Portfolio Activation Boundary

The closed v0.1 baseline is active as portfolio evidence.

Approved use includes:

- professional portfolio review,
- role-fit and hiring discussion,
- AI governance and process-governance discussion,
- controlled professional profile or post references,
- private professional conversations.

Activation does not approve product, training, open-source, contribution, commercial packaging, or autonomous-system claims.

Use `PORTFOLIO_ACTIVATION.md` for approved framing and launch wording.

## Navigation Paths by Reader Need

### Fast overview

1. `README.md`
2. `PORTFOLIO_BRIEF.md`
3. `diagrams/README.md`

### Method and governance

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

### Portfolio use

1. `PORTFOLIO_ACTIVATION.md`
2. `PUBLICATION_BOUNDARY.md`
3. `STATUS.md`
4. `README.md`

### License and publication questions

1. `LICENSE_DECISION.md`
2. `SENSITIVE_CONTENT_REVIEW.md`
3. `PUBLICATION_BOUNDARY.md`
4. `PORTFOLIO_ACTIVATION.md`
5. `STATUS.md`

### Baseline maintenance and closure

1. `README_PLAN.md`
2. `GITHUB_HYGIENE_REVIEW.md`
3. `BASELINE_CLOSURE_REVIEW.md`
4. `STATUS.md`
5. `REPOSITORY_MAP.md`

## Deferred Decisions

The following remain deferred unless explicitly approved:

- an actual `LICENSE` file,
- external contribution workflow,
- broad public release or campaign,
- commercial packaging,
- official training or certification framing,
- public portfolio baseline v0.2.

## Maintenance Principle

The repository should remain small enough to inspect and structured enough to trust.

After v0.1 closure, do not add a new baseline document without a new approved task and explicit reason.

BSL-02 portfolio-use artifacts may be added only when they support approved activation, maintenance, or publication decisions without reopening the frozen baseline.

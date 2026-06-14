# Black Signal Lab Repository Map

## Purpose

This document maps the public structure of the Black Signal Lab repository.

It explains what each major area is for, how the repository should be read, and where the public/private boundary sits.

The map is a navigation and governance artifact. It is not a technical architecture document, implementation reference, or product roadmap.

## Repository Role

Black Signal Lab is a public methodology and portfolio repository for controlled AI-assisted work.

The repository demonstrates how AI-assisted workflows can be structured around artifacts, validation gates, source-of-truth boundaries, public-safe examples, and human review.

The repository does not contain private implementation details, production configuration, real operational logs, real project documents, or confidential material.

## Recommended Navigation

For a first-time reader, use this path:

1. `README.md` — main entry point and reading path.
2. `LAB_CHARTER.md` — lab purpose, boundaries, human review principle.
3. `PUBLIC_POSITIONING.md` — public audience, value proposition, project positioning.
4. `REPOSITORY_MAP.md` — repository structure, navigation paths, public/private boundary notes.
5. `METHOD_PRINCIPLES.md` — method principles for controlled AI-assisted work.
6. `PORTFOLIO_BRIEF.md` — compact overview of the portfolio and case studies.
7. `frameworks/black-signal-governance-model.md` — shared governance model.
8. `diagrams/` — visual overview of the portfolio and workflows.
9. `case-studies/` — public-safe case studies and examples.
10. `training/critical-thinking-for-ai-workflows/` — workshop-style learning module.
11. `reviews/` — review notes and public-baseline quality checks.
12. `STATUS.md` — current baseline and development stance.

## Top-Level Entry Points

### `README.md`

The main public entry point.

It explains what Black Signal Lab is, links to the core documents, provides the recommended reading path, summarizes the portfolio map, and states the privacy/data boundary.

### `LAB_CHARTER.md`

The lab charter.

It defines the purpose of Black Signal Lab, what it is and is not, the target audience, the human review principle, artifact principle, boundary principle, and public-safe scope.

Use this document to understand the lab's identity and operating boundaries.

### `PUBLIC_POSITIONING.md`

The public positioning document.

It explains the public audience, value proposition, project positioning, personal operating model, tone, non-goals, and public-safety boundary.

Use this document to understand how the lab should be presented without overclaiming or making platform-specific claims.

### `REPOSITORY_MAP.md`

The repository map.

It explains the public repository structure, major folders, navigation paths, public/private boundary notes, and maintenance rules.

Use this document to understand where things belong and what should not be added.

### `METHOD_PRINCIPLES.md`

The method principles document.

It defines six method principles for controlled AI-assisted work: Artifact, Review, Evidence, Human Decision, Boundary, and Anti-Overclaim.

Use this document to understand how the Black Signal Governance Model should behave in practice.

### `PORTFOLIO_BRIEF.md`

A short portfolio overview.

It summarizes what the repository demonstrates and introduces the three case studies: SAMAEL, The Daltons, and NOESIS.

Use this document as the one-page executive overview.

### `STATUS.md`

The current public baseline status.

It states the repository baseline, current contents, what the repository is and is not, and the current development stance.

Use this document to prevent scope drift.

## Folder Map

```text
/
├── README.md
├── LAB_CHARTER.md
├── PUBLIC_POSITIONING.md
├── REPOSITORY_MAP.md
├── METHOD_PRINCIPLES.md
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
│   ├── README.md
│   ├── black-signal-lab-map.md
│   ├── samael-workflow.md
│   ├── the-daltons-workflow.md
│   └── noesis-workflow.md
│
├── training/
│   └── critical-thinking-for-ai-workflows/
│
└── reviews/
    └── public-baseline-outsider-review-v0-1.md
```

This is a public-facing map, not a full file inventory. It shows the major navigation areas and their intended roles.

## `frameworks/`

The `frameworks/` directory contains conceptual models shared across the repository.

Current primary artifact:

- `black-signal-governance-model.md`

This model connects the case studies through shared concepts such as input boundary, source of truth, structured artifact, validation gate, human review, approved handoff, evidence and traceability, and anti-overclaim boundary.

What belongs here:

- shared governance models,
- conceptual frameworks,
- cross-case patterns,
- public-safe operating-model descriptions.

What does not belong here:

- implementation instructions,
- private workflow details,
- production architecture,
- confidential process records,
- tool-specific operational configuration.

## `case-studies/`

The `case-studies/` directory contains public-safe examples of the shared method in different workflow contexts.

Current case studies:

- `samael/` — bounded AI-assisted task execution, task contracts, project memory, validation gates, human review.
- `the-daltons/` — meeting and document analysis, evidence mapping, JSON artifacts, validation gates, reviewable outputs.
- `noesis/` — telemetry, interpretation layers, source-of-truth boundaries, human-readable reporting, observability gates.

What belongs here:

- sanitized case-study descriptions,
- synthetic examples,
- public-safe patterns,
- reviewable artifacts,
- handoff notes,
- evidence and validation examples.

What does not belong here:

- real client or employer material,
- real meeting transcripts,
- real project documents,
- real operational logs,
- private agent instructions,
- internal task records,
- credentials, secrets, private URLs, or local paths.

## `diagrams/`

The `diagrams/` directory contains public-safe Mermaid diagrams.

The diagrams are high-level governance views, not implementation diagrams.

Current diagram set:

- `black-signal-lab-map.md`
- `samael-workflow.md`
- `the-daltons-workflow.md`
- `noesis-workflow.md`

What belongs here:

- high-level portfolio maps,
- workflow diagrams,
- governance diagrams,
- public-safe conceptual diagrams.

What does not belong here:

- infrastructure diagrams,
- production topology,
- private system dependencies,
- internal network or deployment details,
- diagrams containing confidential names, URLs, paths, or system identifiers.

## `training/`

The `training/` directory contains public-safe learning material.

Current module:

- `critical-thinking-for-ai-workflows/`

This is a workshop-style portfolio module, not an accredited course, certification, official training program, or production implementation guide.

What belongs here:

- public-safe workshop outlines,
- participant exercises,
- answer keys,
- synthetic examples,
- review checklists,
- learning material that reinforces the repository's core principles.

What does not belong here:

- official employer training material,
- accredited course claims,
- confidential examples,
- real project exercises,
- private operational procedures.

## `reviews/`

The `reviews/` directory contains public-baseline review material.

Current review:

- `public-baseline-outsider-review-v0-1.md`

Reviews are used to check clarity, navigation, public safety, overclaiming risk, and baseline coherence.

What belongs here:

- public-safe quality reviews,
- baseline checks,
- navigation reviews,
- public-safety checks,
- scope-drift observations.

What does not belong here:

- private review notes,
- internal decision logs,
- confidential critique,
- unpublished employer or client review material.

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
- high-level diagrams.

It must not include:

- personal data,
- company confidential data,
- real meeting transcripts,
- real project documents,
- real task logs,
- real runtime logs,
- internal URLs,
- private paths,
- credentials, tokens, or secrets,
- production configuration,
- private infrastructure details,
- private account names,
- copied internal project files.

The public repository shows the method, not the private machinery.

## What Belongs in This Repository

Add material only when it strengthens at least one of the existing public paths:

- lab identity and boundaries,
- public positioning,
- repository navigation,
- method principles,
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

Do not add new categories unless they are necessary for navigation, review, or public-safe explanation.

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
2. `frameworks/black-signal-governance-model.md`
3. `case-studies/samael/README.md`
4. `case-studies/the-daltons/README.md`
5. `case-studies/noesis/README.md`

### Concrete examples

1. `case-studies/the-daltons/walkthrough.md`
2. `case-studies/samael/examples/`
3. `case-studies/the-daltons/examples/`
4. `case-studies/noesis/examples/`

### Learning and workshop use

1. `training/critical-thinking-for-ai-workflows/README.md`
2. `training/critical-thinking-for-ai-workflows/facilitator-outline.md`
3. `training/critical-thinking-for-ai-workflows/participant-workbook.md`
4. `training/critical-thinking-for-ai-workflows/examples/`

### Baseline review and quality control

1. `STATUS.md`
2. `reviews/public-baseline-outsider-review-v0-1.md`
3. `REPOSITORY_MAP.md`

## Missing or Deferred Documents

The repository now has a map, charter, positioning document, method principles, portfolio brief, status file, governance model, diagrams, case studies, training module, and review material.

Potential future documents should be added only if they solve a concrete navigation or boundary problem.

Possible future candidates:

- `CONTRIBUTION_BOUNDARY.md` — only if external contribution or reuse becomes relevant.
- `PUBLICATION_BOUNDARY.md` — only if publication workflow needs its own explicit gate.
- compact top-level index — only if the repository grows beyond the current navigation model.

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

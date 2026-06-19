# Black Signal Lab License Decision

## Purpose

This document records the current license posture for Black Signal Lab.

The goal is to decide whether the repository should receive an open-source or open-content license now, or whether license selection should be deferred until reuse intent is clearer.

This is a public governance decision artifact. It is not legal advice.

## Current Decision

```text
Decision: DEFER ADDING A LICENSE FILE FOR NOW.
```

Black Signal Lab should remain publicly viewable as a portfolio and methodology repository, but not yet offered for general reuse, modification, redistribution, contribution, or commercial adaptation.

No `LICENSE` file should be added until the intended reuse model is explicitly approved.

## Decision Rationale

Black Signal Lab currently contains:

- public methodology documents,
- public-safe case studies,
- synthetic examples,
- governance patterns,
- training-style material,
- review and boundary documents,
- portfolio positioning.

This is not a software library, production framework, package, or product codebase.

The repository is public so that readers can inspect the method and portfolio. Public visibility is not the same as reuse permission.

## Reuse Intent

Current intended use:

- public viewing,
- portfolio review,
- discussion of the method,
- citation or reference with attribution in normal professional context,
- controlled evolution by the repository owner.

Not currently intended:

- unrestricted reuse,
- fork-and-adapt methodology packages,
- third-party redistribution,
- external contributions,
- commercial repackaging,
- treating the method as an open-source framework,
- treating examples as reusable templates without review.

## No-License Implication

If a public repository has no license, the safe default is that others should not assume permission to copy, modify, distribute, or reuse the work.

Public visibility allows inspection. It does not automatically grant reuse rights.

For Black Signal Lab, this means:

```text
public to read
not yet licensed for reuse
not yet open-source
not yet open-content
```

A visible no-license posture is preferable to accidentally granting rights before the project has a clear reuse strategy.

## High-Level License Options Considered

### Option 1: No License for Now

Description:
Keep the repository public but do not add a license file yet.

Pros:

- avoids premature reuse permissions,
- protects methodology while the portfolio baseline stabilizes,
- keeps publication separate from licensing,
- leaves room for a later deliberate license choice.

Cons:

- external readers may be unsure what they can reuse,
- collaboration is limited,
- not suitable for open-source contribution workflows,
- should be accompanied by visible license-status wording.

Decision fit:

```text
Best current fit.
```

### Option 2: MIT License

Description:
A short permissive software license commonly used for code repositories.

Pros:

- simple,
- familiar to software readers,
- allows broad reuse, modification, distribution, and commercial use with notice preservation.

Cons:

- too permissive for a methodology/portfolio repository at this stage,
- may imply open-source intent before that decision exists,
- does not distinguish clearly between software code and written method content.

Decision fit:

```text
Not recommended now.
```

### Option 3: Apache License 2.0

Description:
A permissive software license with explicit patent grant and additional notice/change requirements.

Pros:

- well-known for software projects,
- clearer patent posture than MIT,
- useful for code-heavy open-source projects.

Cons:

- heavier than needed for a public methodology/portfolio baseline,
- may suggest software/product orientation,
- not clearly aligned with current non-code repository purpose.

Decision fit:

```text
Not recommended now.
```

### Option 4: Creative Commons License

Description:
A family of licenses often used for written, educational, and creative content.

Pros:

- better fit for written methodology and training material than software licenses,
- can express attribution, share-alike, non-commercial, or no-derivatives conditions depending on variant.

Cons:

- requires a separate decision about whether adaptation and commercial reuse should be allowed,
- may conflict with future plans if method packaging or consulting use becomes important,
- should not be chosen casually.

Decision fit:

```text
Possible later candidate, not selected now.
```

## Recommended Public Wording

Until a license is selected, use this wording:

```text
License status: no public reuse license has been selected yet.

This repository is public for portfolio review and method inspection. Do not assume permission to copy, modify, redistribute, package, or commercially reuse its contents unless a license or written permission explicitly grants that right.
```

This wording should be added to a visible place before broad external promotion.

## Contribution Boundary

Because no license is currently selected, the repository should not invite external contributions yet.

Do not add:

- contribution guidelines,
- issue templates requesting outside improvements,
- pull request guidance,
- community contribution language,
- external reuse claims.

If contributions become desirable later, create a separate contribution boundary decision first.

## Future License Decision Trigger

Revisit licensing when at least one of these becomes true:

- the repository is promoted for broad external reuse,
- the method is packaged as a reusable toolkit,
- external contributions are invited,
- training material is intended for reuse outside the owner context,
- templates are intended to be copied by others,
- commercial/non-commercial reuse needs to be distinguished,
- public publication strategy requires a clearer reuse posture.

## Recommendation

Keep the repository public but unlicensed for reuse for now.

Do not add a `LICENSE` file in this task.

Add visible license-status wording later if the repository is promoted more broadly.

Create a future decision task if the desired posture changes to:

- open-source software,
- open-content methodology,
- Creative Commons content reuse,
- restricted commercial reuse,
- contribution-enabled public project.

## Decision Record

| Field | Value |
| --- | --- |
| Decision | Defer adding a license file |
| Current license file | None |
| Current reuse posture | Public to read; not licensed for reuse |
| External contributions | Not invited |
| Reuse permission | Not granted by default |
| Next review trigger | Before broad external promotion or reuse invitation |
| Recommended next action | Add visible license-status wording before wider promotion |

## Non-Actions

This task does not:

- add a `LICENSE` file,
- choose MIT, Apache, Creative Commons, or any other license,
- invite contributions,
- create open-source status,
- grant reuse permission,
- provide legal advice.

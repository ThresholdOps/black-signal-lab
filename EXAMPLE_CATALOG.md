# Black Signal Lab Example Catalog

## Purpose

This catalog lists the public-safe examples used by Black Signal Lab.

The examples show how the method appears in different workflow contexts without exposing private material or replacing the underlying projects.

Each example is a public demonstration of method behavior: boundaries, artifacts, validation, review, decision ownership, and public/private separation.

## Catalog Rule

Examples demonstrate the method.

Examples do not expose private machinery.

Examples are not production claims, implementation references, client records, employer records, or complete project histories.

## Example Index

| Example | Primary Domain | Main Demonstration | Public Boundary |
| --- | --- | --- | --- |
| SAMAEL | AI-assisted task execution | bounded execution, task contracts, validation gates, human handoff | public sanitized governance pattern only |
| The Daltons | meeting and document analysis | source preparation, evidence mapping, JSON artifacts, reviewable outputs | synthetic or sanitized analysis examples only |
| NOESIS | telemetry and interpretation governance | source-of-truth boundaries, event contracts, interpretation reports, observability gates | no private runtime logs, infrastructure, or production configuration |

## SAMAEL Example

### Short Description

SAMAEL is a public, sanitized case study about AI-assisted task orchestration, project memory, validation gates, and human-in-the-loop execution.

It demonstrates how agent-assisted work can be organized as bounded execution: clear task scope, explicit context, reviewable artifacts, validation before completion, and human approval before external action.

### What It Demonstrates

SAMAEL demonstrates controlled task execution.

The example shows how an AI-assisted workflow can be kept inside an explicit task boundary instead of drifting into uncontrolled autonomous work.

Key method elements:

- task contract,
- project memory,
- bounded execution,
- validation gate,
- human review,
- approved handoff,
- completion record.

### Method Mapping

| Method Area | SAMAEL Demonstration |
| --- | --- |
| Artifact Principle | task contracts, validation results, handoff notes |
| Review Principle | human review before completion, commit, publication, deployment, or external action |
| Evidence Principle | task context and validation evidence preserved as review material |
| Human Decision Principle | humans approve handoff and external action |
| Boundary Principle | task scope and exclusions constrain agent-assisted work |
| Anti-Overclaim Principle | agent output is not presented as approval or production authority |

### Lifecycle View

```text
task context -> task contract -> agent-assisted execution -> validation gate -> human review -> approved handoff -> repository/task update -> rule improvement
```

### Public/Private Boundary

This example may show public-safe task contracts, validation gates, handoff notes, and governance patterns.

It must not expose private agent instructions, private project memory records, internal task logs, private infrastructure, credentials, secrets, local paths, or operational implementation details.

For the detailed SAMAEL boundary, see [`case-studies/samael/public-boundary.md`](case-studies/samael/public-boundary.md).

## The Daltons Example

### Short Description

The Daltons is a public, sanitized case study about AI-assisted meeting and document analysis using structured artifacts, evidence mapping, validation gates, and human-in-the-loop review.

It demonstrates how unstructured source material can be converted into reviewable outputs without treating model output as final truth.

### What It Demonstrates

The Daltons demonstrates evidence-backed analysis.

The example shows how messy meeting or document material can be converted into structured artifacts while preserving gaps, assumptions, source references, and review status.

Key method elements:

- source profile,
- evidence map,
- structured JSON artifacts,
- validation result,
- open questions,
- decision log,
- handoff note,
- human review.

### Method Mapping

| Method Area | The Daltons Demonstration |
| --- | --- |
| Artifact Principle | source profiles, evidence maps, JSON artifacts, decision logs |
| Review Principle | validation gates prepare artifacts for human review but do not approve them |
| Evidence Principle | claims and decisions are connected back to source material |
| Human Decision Principle | a person decides what becomes an approved record or follow-up action |
| Boundary Principle | source preparation defines what may be analyzed and what must be excluded |
| Anti-Overclaim Principle | extracted analysis is not treated as final truth or management recommendation |

### Lifecycle View

```text
source material -> source profile -> extraction -> structured artifacts -> validation -> human review -> approved record / action handoff -> method improvement
```

### Public/Private Boundary

This example may show synthetic source notes, source profiles, evidence maps, validation results, handoff notes, and public-safe walkthroughs.

It must not expose real meeting transcripts, real project documents, employer/client records, confidential decisions, internal URLs, private paths, or copied internal material.

## NOESIS Example

### Short Description

NOESIS is a public, sanitized case study about telemetry, interpretation layers, source-of-truth boundaries, human-readable reporting, observability gates, and AI-readable system context.

It demonstrates how structured signals can support governance and operating-model review without exposing private runtime logs, infrastructure details, or production configuration.

### What It Demonstrates

NOESIS demonstrates interpretation governance.

The example shows how system signals can be structured and interpreted without allowing derived interpretation to replace authoritative state.

Key method elements:

- source-of-truth boundary,
- event contract,
- telemetry record,
- interpretation report,
- observability gate,
- human-readable report,
- human review.

### Method Mapping

| Method Area | NOESIS Demonstration |
| --- | --- |
| Artifact Principle | event contracts, telemetry records, interpretation reports, observability gates |
| Review Principle | interpretation is checked before escalation or operational conclusion |
| Evidence Principle | interpreted meaning remains connected to structured signals |
| Human Decision Principle | humans confirm status, escalation, or follow-up |
| Boundary Principle | authoritative state is separated from telemetry and derived interpretation |
| Anti-Overclaim Principle | interpretation is not presented as source of truth or confirmed root cause |

### Lifecycle View

```text
system signal -> event contract -> telemetry record -> interpretation report -> observability gate -> human review -> status / escalation / storage -> signal model improvement
```

### Public/Private Boundary

This example may show synthetic event contracts, telemetry examples, interpretation reports, observability gates, and public-safe reporting patterns.

It must not expose private runtime logs, real server paths, infrastructure details, production configuration, internal URLs, credentials, secrets, private account names, or operational system identifiers.

## Cross-Example Pattern

The three examples demonstrate one shared pattern in different domains:

```text
boundary -> artifact -> validation -> review -> decision -> handoff / storage -> improvement
```

The pattern changes shape depending on context:

- SAMAEL applies it to task execution.
- The Daltons applies it to meeting and document analysis.
- NOESIS applies it to system signals and interpretation.

The common rule remains the same:

```text
AI or system output is review material, not final authority.
```

## What the Catalog Demonstrates

The catalog demonstrates that Black Signal Lab is not a collection of disconnected examples.

Each case shows a different surface of the same method:

- SAMAEL: controlled execution.
- The Daltons: evidence-backed analysis.
- NOESIS: interpretation governance.

Together, they show how controlled AI-assisted work can be adapted across task work, knowledge work, and system-signal work.

## What the Catalog Does Not Claim

This catalog does not claim that the examples are production systems.

It does not claim that the examples are commercial products.

It does not claim that the examples include private project materials.

It does not claim that the examples are complete implementations.

It does not replace the underlying case-study documents.

The catalog is an index and method map.

## Public/Private Boundary Summary

All examples must remain public-safe.

Allowed:

- public methodology,
- synthetic examples,
- sanitized examples,
- public-safe case notes,
- general workflow patterns,
- reviewable artifact patterns,
- public-safe diagrams,
- boundary notes.

Not allowed:

- personal data,
- company confidential data,
- real meeting transcripts,
- real project documents,
- real task logs,
- real runtime logs,
- private agent instructions,
- internal URLs,
- private paths,
- credentials, tokens, or secrets,
- production configuration,
- copied internal project files.

The examples show the method.

They do not expose the private machinery.

## Reading Path

For each example, read in this order:

1. example summary in this catalog,
2. related case-study README,
3. example artifacts inside the case-study directory,
4. relevant lifecycle or doctrine document,
5. governance model comparison if needed.

Suggested sequence:

1. `METHOD_PRINCIPLES.md`
2. `ARTIFACT_LIFECYCLE.md`
3. `REVIEW_MATERIAL_DOCTRINE.md`
4. `EXAMPLE_CATALOG.md`
5. `case-studies/samael/README.md`
6. `case-studies/samael/public-boundary.md`
7. `case-studies/the-daltons/README.md`
8. `case-studies/noesis/README.md`

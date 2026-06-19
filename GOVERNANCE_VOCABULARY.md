# Black Signal Lab Governance Vocabulary

## Purpose

This document defines the core vocabulary used by Black Signal Lab.

The goal is not to create academic definitions. The goal is to make public artifacts easier to read, review, compare, and maintain.

These terms are used across the lab charter, method principles, artifact lifecycle, review material doctrine, example catalog, and case studies.

## Vocabulary Rule

Use terms consistently.

Do not let method words become decoration.

A term should help a reader understand what an artifact is, what it is allowed to mean, and where human review or decision ownership is required.

## Term Index

| Term | Short Meaning |
| --- | --- |
| artifact | a stable, inspectable work product |
| review material | output prepared for inspection, not final truth |
| evidence | support that connects a claim to a source, signal, or observation |
| decision | a human-owned acceptance of consequence |
| interpretation | meaning derived from source material, signals, or context |
| source of truth | the authoritative place or record for a given fact, state, or decision |
| validation | a check that an artifact meets structure, boundary, or readiness criteria |
| human gate | a required human review or approval point before consequence |
| operating model | the way work, roles, artifacts, tools, and decisions are organized |

## Artifact

An artifact is a stable, inspectable work product.

It may be a document, JSON file, note, diagram, checklist, validation result, handoff note, task contract, evidence map, interpretation report, or public case note.

An artifact should be easier to inspect than an open conversation.

A useful artifact has:

- purpose,
- scope,
- input boundary,
- status,
- owner or reviewer when relevant,
- known limitations,
- intended next use.

### Examples

- SAMAEL: task contract, validation gate, handoff note.
- The Daltons: source profile, evidence map, decision log.
- NOESIS: event contract, telemetry record, interpretation report.

### Non-example

A model response floating in chat with no status, source boundary, or review path is not yet a governed artifact.

## Review Material

Review material is output prepared for inspection.

It may be useful, structured, and directionally correct, but it is not final truth and not an approved decision.

Review material becomes trusted only when a human reviewer accepts, corrects, rejects, defers, or escalates it.

Default status:

```text
AI output = review material
```

### Examples

- A candidate summary of meeting decisions.
- A draft interpretation of telemetry.
- A proposed task handoff note.
- A validation result that says an artifact is ready for review.

### Non-example

A generated summary that is treated as an official record without review is not properly handled review material. It is an overclaim.

## Evidence

Evidence is support that connects a claim to a source, signal, observation, or prior artifact.

Evidence does not automatically prove truth. It gives reviewers something to inspect.

Good evidence makes it possible to ask:

- where did this claim come from?
- what supports it?
- what is missing?
- what is inferred?
- what should be checked by a human?

### Examples

- The Daltons: source references connected to claims in an evidence map.
- SAMAEL: task context and validation findings connected to a handoff note.
- NOESIS: structured telemetry fields connected to an interpretation report.

### Non-example

A confident statement without visible support is not evidence.

## Decision

A decision is a human-owned acceptance of consequence.

A decision may use AI-assisted material, but the decision is not made true by the model.

A decision should make clear:

- what was decided,
- who decided,
- what was accepted,
- what remains uncertain,
- what action or record follows,
- what consequence is being carried.

### Examples

- Accepting a task handoff after review.
- Approving a meeting-derived decision log as a project record.
- Escalating a NOESIS interpretation after human review.

### Non-example

A model recommendation is not a decision unless a human decision owner accepts it.

## Interpretation

Interpretation is meaning derived from source material, signals, or context.

Interpretation is useful because raw material is often incomplete, noisy, fragmented, or difficult to use directly.

Interpretation must remain distinguishable from source material and source of truth.

### Examples

- The Daltons: extracting a likely risk from meeting notes.
- NOESIS: turning telemetry into a candidate status report.
- SAMAEL: summarizing what a task execution appears to have completed.

### Non-example

An interpretation presented as confirmed truth without evidence or review is an overclaim.

## Source of Truth

A source of truth is the authoritative place or record for a given fact, state, or decision.

Different things can have different sources of truth.

A public case study can describe a pattern, but it is not the source of truth for a private implementation, live system, real meeting, or real project.

### Examples

- A task system may be the source of truth for task status.
- A project decision log may be the source of truth for approved decisions.
- A live system may be the source of truth for current system state.

### Non-example

A public sanitized case note is not the source of truth for private operational reality.

## Validation

Validation is a check that an artifact meets structure, boundary, or readiness criteria.

Validation may check completeness, consistency, required fields, source references, public/private boundaries, or readiness for review.

Validation does not make an artifact true.

Validation answers a narrower question:

```text
Is this artifact structured, bounded, and ready for review?
```

### Examples

- Checking whether a source profile has required fields.
- Checking whether an evidence map links claims to sources.
- Checking whether an interpretation report separates signal from conclusion.
- Checking whether a public artifact avoids private material.

### Non-example

A validation pass is not the same as human acceptance.

## Human Gate

A human gate is a required human review or approval point before consequence.

A human gate is needed when output may affect publication, record keeping, project action, escalation, operational conclusion, or responsibility.

Human gates prevent review material from silently becoming authority.

### Examples

- Human approval before publishing a public artifact.
- Human review before accepting a task handoff.
- Human review before treating meeting analysis as an approved record.
- Human review before escalating a system interpretation.

### Non-example

A fully automated workflow that approves its own consequential output has removed the human gate.

## Operating Model

An operating model is the way work, roles, artifacts, tools, review points, decisions, and handoffs are organized.

In Black Signal Lab, the operating model matters because AI work is not only prompt generation. It is a system of responsibility.

An operating model answers:

- who asks?
- what input is allowed?
- what artifact is produced?
- who reviews?
- what is validated?
- who decides?
- where is the source of truth?
- what is stored?
- what improves next time?

### Examples

- SAMAEL: task contract -> execution -> validation -> human handoff.
- The Daltons: source material -> evidence-linked artifacts -> validation -> review.
- NOESIS: telemetry -> interpretation -> observability gate -> human status or escalation.

### Non-example

A collection of prompts without review, ownership, storage, or decision boundaries is not an operating model.

## Cross-Term Relationships

These terms are connected.

```text
source material / signal -> artifact -> validation -> review material -> human gate -> decision -> source of truth / handoff / storage
```

Important distinctions:

| Distinction | Meaning |
| --- | --- |
| artifact vs review material | an artifact is the work product; review material is its provisional status before acceptance |
| evidence vs interpretation | evidence supports; interpretation derives meaning |
| validation vs decision | validation checks readiness; decision accepts consequence |
| source of truth vs report | source of truth is authoritative; report is a representation or interpretation |
| human gate vs automation | automation may prepare; a human gate accepts consequence |
| operating model vs workflow | a workflow shows steps; an operating model includes roles, boundaries, tools, artifacts, and decisions |

## Public Clarity Rules

When writing public Black Signal Lab material:

- Use `artifact` when something is stable enough to inspect.
- Use `review material` when output is not yet accepted.
- Use `evidence` only when support is visible or traceable.
- Use `decision` only when a human owner is implied or explicit.
- Use `interpretation` when meaning is derived rather than directly authoritative.
- Use `source of truth` only for authoritative records or states.
- Use `validation` for readiness or boundary checks, not proof of truth.
- Use `human gate` for consequential review points.
- Use `operating model` when discussing how work, roles, artifacts, tools, and decisions fit together.

## What This Vocabulary Prevents

This vocabulary helps prevent:

- treating AI output as final truth,
- treating validation as approval,
- treating interpretation as source of truth,
- treating summaries as records,
- treating automation as accountability,
- treating public examples as private implementation details,
- treating workflow steps as a full operating model.

The vocabulary is a control surface.

It keeps the method legible.

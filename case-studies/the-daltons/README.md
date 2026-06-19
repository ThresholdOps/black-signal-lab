# The Daltons

## Summary

The Daltons is a public, sanitized case study about AI-assisted meeting and document analysis using structured artifacts, evidence mapping, validation gates, and human-in-the-loop review.

It demonstrates how unstructured source material can be converted into reviewable outputs without treating model output as final truth.

## Problem

Meeting-heavy and document-heavy operating environments often lose decisions, assumptions, risks, dependencies, open questions, ownership gaps, and follow-up actions across fragmented notes and informal communication.

The Daltons addresses this as a process governance problem: how to prepare sources, extract structured meaning, preserve evidence links, validate outputs, and keep human judgment responsible for approval.

## Public-Safe Workflow Model

At a high level, the workflow uses five public-safe concepts:

1. **Structured source preparation** - describe each input before analysis, including type, scope, sensitivity, and intended use.
2. **Evidence mapping** - connect extracted claims, decisions, risks, and actions back to source references.
3. **JSON artifacts** - represent intermediate outputs in a consistent, reviewable format.
4. **Validation gates** - check completeness, consistency, data boundaries, and evidence coverage.
5. **Human review** - approve, correct, reject, or escalate outputs before downstream use.

This case study is governance-oriented. It does not publish private implementation details and does not claim production readiness.

## Role of Structured Source Preparation

Source preparation makes the input boundary explicit before AI-assisted analysis begins. A source profile records what kind of material is being analyzed, what it may be used for, what should be excluded, and what review constraints apply.

See [source-profile.example.json](examples/source-profile.example.json) for a synthetic example.

## Role of Evidence Mapping

Evidence mapping keeps extracted outputs connected to the material that supports them. This helps reviewers distinguish between source-backed statements, uncertain interpretations, and items requiring clarification.

See [evidence-map.example.json](examples/evidence-map.example.json) for a synthetic example.

## Role of JSON Artifacts

JSON artifacts make AI-assisted outputs easier to validate, compare, hand off, and integrate into governance workflows. They also make missing fields, weak evidence, and review status more visible than free-form summaries alone.

## Role of Validation Gates

Validation gates check whether the structured artifacts are complete, consistent, public-safe, and ready for human review. They do not make the output true; they make review requirements explicit.

See [validation-result.example.json](examples/validation-result.example.json) for a synthetic example.

## Role of Human Review

Human-in-the-loop review remains the control point for decisions, publication, escalation, and downstream action. The workflow produces reviewable outputs; a person remains responsible for accepting or correcting them.

See [handoff-note.example.md](examples/handoff-note.example.md) for a synthetic example.

## What This Demonstrates

The Daltons demonstrates AI transformation, process governance, and operating model improvement patterns:

- turning unstructured inputs into structured artifacts
- preserving evidence links for review
- separating extraction from approval
- making validation gates explicit
- improving traceability across meetings, documents, decisions, and actions

## Example Artifacts

- [Source profile example](examples/source-profile.example.json)
- [Evidence map example](examples/evidence-map.example.json)
- [Validation result example](examples/validation-result.example.json)
- [Handoff note example](examples/handoff-note.example.md)

## Further Reading

- [The Daltons public boundary](public-boundary.md)
- [Synthetic evidence-to-decision walkthrough](walkthrough.md)
- [Evidence-to-decision pattern](evidence-to-decision-pattern.md)

## Data Boundary

This case study contains only public, synthetic, anonymized, or fully sanitized material.

It does not include personal data, company confidential data, real meeting transcripts, real project documents, internal URLs, private paths, credentials, tokens, secrets, private infrastructure details, private account names, local paths, production configuration, or copied internal project files.

# Black Signal Lab Human Decision Gate

## Purpose

This document defines the human decision gate used by Black Signal Lab.

A human decision gate is the point where review material stops being only prepared output and becomes accepted, rejected, escalated, deferred, or recorded by a human decision owner.

The gate exists to prevent AI-assisted material from silently becoming authority.

## Decision Rule

```text
AI may prepare review material.
Human reviewers own acceptance, rejection, escalation, and recorded decisions.
```

AI can help create structure.

AI can help surface evidence.

AI can help identify gaps.

AI can help prepare candidate options.

AI must not accept consequence.

## What AI Can Prepare

AI-assisted workflows may prepare:

- summaries,
- draft artifacts,
- source profiles,
- evidence maps,
- decision-log candidates,
- risk notes,
- open questions,
- validation results,
- interpretation reports,
- handoff notes,
- public-safe wording candidates,
- comparison tables,
- escalation candidates,
- draft recommendations for review.

These outputs remain review material until a human reviewer acts on them.

## What AI Must Not Decide

AI must not independently decide:

- final approval,
- acceptance of consequence,
- publication of boundary-risk material,
- whether private material is safe to expose,
- whether a source is authoritative,
- whether a claim is officially true,
- whether an interpretation is an operational conclusion,
- whether a meeting summary is an official record,
- whether a project decision is accepted,
- whether an issue should be escalated without human review,
- whether a public artifact is production-ready,
- whether accountability has been transferred.

Automation may support preparation, checking, and routing.

It must not replace accountable judgment.

## Gate Definition

A human decision gate has five parts:

1. **Artifact under review** — what is being judged.
2. **Review basis** — what evidence, source boundary, validation result, or context supports review.
3. **Reviewer role** — who inspects the material.
4. **Decision owner** — who accepts consequence.
5. **Recorded outcome** — what status is assigned and what happens next.

A gate is incomplete if any of these parts are missing.

## Reviewer Role

A reviewer inspects review material before it is accepted, rejected, escalated, deferred, published, stored as approved, or used downstream.

The reviewer checks:

- whether the input boundary is clear,
- whether the artifact is complete enough to review,
- whether evidence is visible,
- whether assumptions are marked,
- whether open questions remain visible,
- whether validation checks passed or failed,
- whether the artifact exposes private material,
- whether the artifact overclaims,
- whether a decision owner is explicit,
- whether escalation is required.

The reviewer does not merely read.

The reviewer determines whether the artifact is fit for a decision.

## Decision Owner Role

The decision owner accepts responsibility for what happens after review.

The reviewer and decision owner may be the same person in low-risk work.

They should be separate when the consequence is high, public, operational, compliance-related, or organizationally sensitive.

The decision owner decides whether to:

- accept,
- accept with correction,
- reject,
- defer,
- escalate,
- store as draft,
- store as approved artifact,
- approve for handoff,
- approve for publication,
- approve for downstream action.

## Decision Record

A decision should be recorded when review material changes status or may affect another person, artifact, process, system, publication, or action.

A minimal decision record should include:

- artifact name,
- artifact type,
- date or version,
- review material status,
- reviewer,
- decision owner,
- decision outcome,
- evidence or validation basis,
- known limitations,
- required corrections if any,
- escalation path if any,
- next allowed use.

A decision record does not need to be heavy.

It needs to be explicit enough that a future reader can understand what was accepted, by whom, and under what boundary.

## Decision Outcomes

Use explicit decision outcomes.

```text
accept
accept with correction
reject
defer
escalate
store as draft
store as approved artifact
approve for handoff
approve for publication
approve for downstream action
```

Do not use vague status language when consequence exists.

Avoid:

- looks good,
- probably fine,
- approved by AI,
- validated therefore true,
- no issues found,
- ready without review.

## Escalation Cases

Escalation is required when review material involves:

- public publication risk,
- private or sensitive material,
- unclear source-of-truth boundary,
- legal, compliance, or policy exposure,
- real organizational consequence,
- operational or system-state conclusions,
- security-sensitive context,
- reputational risk,
- unresolved evidence gaps,
- conflicting source material,
- ambiguous decision ownership,
- high-impact recommendation,
- material that could be mistaken for an official record.

Escalation does not mean the artifact is wrong.

It means the decision should not be owned at the current level.

## Gate Pattern by Case Study

### SAMAEL

```text
task contract / handoff note -> validation gate -> human review -> accept, correct, reject, or escalate -> completion record
```

The gate prevents agent-assisted work from approving its own completion, publication, deployment, or external action.

### The Daltons

```text
evidence-linked artifact -> validation result -> human review -> approved record, correction, open question, or escalation
```

The gate prevents AI-generated summaries or structured extracts from becoming official records without review.

### NOESIS

```text
telemetry / interpretation report -> observability gate -> human review -> status, escalation, storage, or rejection
```

The gate prevents interpretation from being mistaken for authoritative system state.

## Public-Safe Gate Checklist

Before a public artifact is published or treated as accepted, check:

- Is the artifact clearly identified?
- Is its status clear?
- Is the source boundary visible?
- Is it synthetic, sanitized, or public-safe?
- Are evidence and assumptions distinguishable?
- Are open questions preserved?
- Has validation checked structure and boundary?
- Has a human reviewed it?
- Is the decision owner explicit?
- Is the decision outcome recorded?
- Is escalation required?
- Is the next allowed use clear?

If the answer is unclear, the gate has not passed.

## Relationship to Other Method Documents

This document works with:

- `METHOD_PRINCIPLES.md` — defines the principles.
- `ARTIFACT_LIFECYCLE.md` — shows how artifacts move from input to decision and storage.
- `REVIEW_MATERIAL_DOCTRINE.md` — defines review material status.
- `GOVERNANCE_VOCABULARY.md` — defines terms such as decision, validation, human gate, and source of truth.
- `EXAMPLE_CATALOG.md` — shows how the pattern appears across case studies.

The human decision gate is where the method becomes accountable.

## Anti-Overclaim Rule

Do not say that AI approved, verified, accepted, or decided consequential work.

Say what happened:

- AI prepared review material.
- Validation checked structure and boundary.
- A human reviewed the artifact.
- A decision owner accepted or rejected consequence.
- The decision outcome was recorded.

This keeps authority where it belongs.

## Summary

The human decision gate is not a bureaucratic decoration.

It is the boundary between generated material and accountable use.

AI may prepare the signal.

Validation may check the artifact.

A human decision owner carries the consequence.

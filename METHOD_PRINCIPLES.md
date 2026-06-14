# Black Signal Lab Method Principles

## Purpose

This document defines method principles for controlled AI-assisted work.

The principles are aligned with the Black Signal Governance Model, but they do not present Black Signal Lab as a packaged commercial framework.

They describe how AI-assisted work should be structured when the output must remain reviewable, bounded, evidence-aware, and accountable to human judgment.

## Core Statement

AI output is not truth.

AI output is not a decision.

AI output is review material.

The method begins from that boundary.

## Principle List

1. Artifact Principle
2. Review Principle
3. Evidence Principle
4. Human Decision Principle
5. Boundary Principle
6. Anti-Overclaim Principle

## 1. Artifact Principle

AI-assisted work should produce artifacts, not disposable answers.

A prompt can start the work, but the useful unit is the artifact that remains after the answer appears.

A good artifact has:

- a clear purpose,
- defined input,
- visible assumptions,
- traceable claims,
- known limits,
- review status,
- an owner or reviewer,
- a defined next use.

The artifact is the object that can be inspected, challenged, corrected, reused, rejected, or handed off.

If an AI output cannot become a reviewable artifact, it should not be treated as reliable work product.

## 2. Review Principle

AI-assisted output remains provisional until it is reviewed.

Review is not decorative approval. It is the control point where someone checks whether the artifact is complete, bounded, coherent, and safe enough for its intended use.

A review should ask:

- Does this artifact match its purpose?
- Are the inputs clear?
- Are claims separated from assumptions?
- Are important gaps visible?
- Are boundaries respected?
- Is the next use allowed?
- Who accepts or rejects the artifact?

Validation can support review, but validation is not review.

A validation gate may check structure, completeness, consistency, or boundary conditions. It does not decide truth, relevance, ownership, or consequence.

## 3. Evidence Principle

Claims should remain connected to their evidence.

AI-assisted work becomes dangerous when fluent interpretation hides weak support. The method therefore separates source-backed statements from interpretations, assumptions, risks, decisions, and open questions.

An evidence-aware artifact should show:

- what source material was used,
- which claims are directly supported,
- which points are interpretations,
- which assumptions need confirmation,
- which gaps remain open,
- where confidence is limited,
- what cannot be concluded from the available material.

Evidence mapping does not guarantee truth.

It improves inspectability.

## 4. Human Decision Principle

AI can prepare decision material, but it does not make accountable decisions.

A decision requires a human or authorized body to accept consequence.

The method separates:

- generated output,
- structured artifact,
- review result,
- approved decision,
- follow-up action.

A model may help summarize, compare, structure, classify, or surface possible risks. It does not own the decision, approve the action, or carry the consequence.

Whenever an AI-assisted artifact may influence a record, commitment, escalation, publication, deployment, or operational action, a human decision point must be explicit.

## 5. Boundary Principle

Controlled AI-assisted work requires explicit boundaries.

A boundary defines what may be used, what must be excluded, and where the output may go next.

Boundaries should cover:

- input scope,
- source sensitivity,
- public/private separation,
- allowed context,
- excluded material,
- intended use,
- downstream handoff,
- publication limits,
- data and confidentiality constraints.

Without boundaries, AI-assisted work expands until it becomes unclear what was used, what was inferred, and what is safe to rely on.

A useful boundary is not bureaucracy.

It is containment.

## 6. Anti-Overclaim Principle

Do not present AI-assisted output as more certain, complete, authoritative, or production-ready than it is.

Overclaiming happens when:

- a draft is presented as an approved record,
- an interpretation is presented as fact,
- a validation pass is presented as truth,
- a synthetic example is presented as real evidence,
- a portfolio pattern is presented as production implementation,
- a reviewable signal is presented as final authority.

The method requires explicit status language.

Use words like:

- draft,
- review material,
- candidate interpretation,
- source-backed claim,
- assumption,
- open question,
- validation result,
- approved decision,
- rejected output,
- deferred item.

The goal is not to sound less confident.

The goal is to be precise about what the artifact is allowed to mean.

## Working Sequence

A controlled AI-assisted workflow should usually move through this sequence:

```text
input boundary -> AI-assisted structuring -> artifact -> validation gate -> human review -> decision or handoff
```

Not every workflow needs a heavy process.

Every meaningful workflow does need to know where the boundary, artifact, review, evidence, and decision points are.

## What This Method Avoids

The method is designed to avoid common failure modes:

- treating model output as final truth,
- treating validation as approval,
- mixing facts, assumptions, interpretations, and decisions,
- losing evidence links,
- hiding uncertainty inside fluent prose,
- allowing uncontrolled context expansion,
- publishing private or sensitive material,
- turning portfolio examples into production claims,
- assigning ownership without human acceptance,
- acting on review material before review happens.

## Minimum Viable Artifact

For small work, a minimum viable artifact should state:

- purpose,
- input used,
- output summary,
- key claims,
- assumptions,
- open questions,
- review status,
- human decision point,
- next action or handoff.

This is not a template requirement for every document.

It is a discipline check: if these elements are missing, the output may be fluent but not yet controlled.

## When to Use These Principles

Use these principles when AI-assisted output may influence:

- project decisions,
- process governance,
- data governance,
- operating-model design,
- documentation,
- analysis handoff,
- risk review,
- stakeholder communication,
- public artifacts,
- training or workshop material.

The more consequence an output carries, the more explicit the principles should become.

## When Not to Overbuild

Do not turn every small AI interaction into a process ceremony.

If the output is private, low-risk, temporary, and not reused, a lightweight review may be enough.

The method is not meant to slow thinking down.

It is meant to prevent uncontrolled output from becoming trusted work by accident.

## Relationship to the Black Signal Governance Model

The Black Signal Governance Model defines the shared concepts used across the repository: input boundary, source of truth, structured artifact, validation gate, human review, approved handoff, evidence and traceability, and anti-overclaim boundary.

These method principles explain how those concepts should behave in practice.

The model describes the structure.

The principles describe the discipline.

# The Daltons Evidence-to-Decision Pattern

## Summary

The Daltons is a public-safe pattern for turning unstructured source material into evidence-backed, reviewable analysis artifacts. The pattern does not treat AI output as final truth. It uses structured artifacts, evidence links, validation gates, and human review to move from source material toward decision readiness.

Decision readiness means the material is organized well enough for a responsible person to review, approve, reject, correct, or escalate. It does not mean the model has made the decision.

## Why Evidence Mapping Matters

Evidence mapping prevents extracted statements from floating free of their source material. A claim, risk, open question, or decision candidate is more reviewable when a reviewer can see what source reference supports it, what is missing, and what remains uncertain.

Without evidence mapping, AI-assisted analysis can become a polished summary with unclear grounding. That creates risk: assumptions may look like facts, open questions may look resolved, and suggested actions may appear more authoritative than the source material supports.

Evidence mapping makes the review conversation more precise:

- What was explicitly stated?
- What was inferred?
- What is still missing?
- Which artifact depends on which source reference?
- What requires human confirmation before it becomes an approved record or action?

## Distinguishing Review Categories

The pattern separates different kinds of review output instead of collapsing them into a single narrative.

**Source-backed fact** is a statement directly supported by source material. It should point back to a source reference or evidence identifier.

**Interpretation** is a reasoned reading of source material. It may be useful, but it should remain visibly distinct from a directly supported fact.

**Assumption** is a working belief used to make sense of incomplete material. It should be labeled as an assumption and reviewed before downstream use.

**Open question** is something the material does not answer. The workflow should preserve the question rather than invent an answer.

**Risk** is a possible negative condition, issue, dependency, or exposure suggested by the material. A risk artifact should not become a mitigation plan unless a human review process approves that next step.

**Decision** is an explicit or review-confirmed choice. A decision should not be inferred from vague wording unless it is marked as provisional, unclear, or requiring confirmation.

**Follow-up action** is work someone may need to do. It should not be assigned to an owner unless the source material or human reviewer supports that assignment.

These distinctions help prevent model fluency from turning uncertainty into false certainty.

## How Structured JSON Artifacts Support Reviewability

Structured JSON artifacts make review easier because they force the analysis into visible fields: source references, confidence, status, open questions, evidence gaps, owner fields, limitations, and review flags.

Compared with a free-form summary, structured artifacts make it easier to see:

- whether required sections are present
- whether evidence links exist
- whether confidence and status are explicit
- whether open questions remain unresolved
- whether ownership or approval is missing
- whether the artifact stays within its role
- whether the output is safe to hand off for human review

The value is not the JSON format by itself. The value is that structure makes missing context, weak evidence, and review boundaries easier to inspect.

## Validation Gates Do Not Make Output True

Validation gates can check whether an artifact is complete, well-formed, consistent, and within scope. They can flag missing evidence, malformed fields, unsupported conclusions, or boundary violations.

They do not prove that the content is true.

A validation gate improves reviewability. It does not replace source verification, human judgment, approval authority, or accountability. A clean validation result means the artifact is better prepared for review, not that it is approved.

## Human Review Turns Artifacts Into Records or Actions

Human review is the approval boundary. A reviewer can accept, correct, reject, escalate, or defer an artifact. Only that review process can turn a reviewable output into an approved record, decision, or action.

This boundary matters because AI-assisted extraction can organize material quickly, but it cannot own business accountability. The workflow is designed to prepare evidence-backed artifacts for review, not to bypass governance.

## Ownership Gaps and Open Questions

Ownership gaps should remain visible. If the source material does not identify an owner, approver, or responsible role, the artifact should record that gap instead of assigning accountability.

Open questions should also remain visible. If the source material does not answer a question, the workflow should preserve the question, its evidence context, and its possible impact on downstream review.

This helps reviewers distinguish between:

- confirmed ownership
- missing ownership
- unclear approval status
- unresolved dependencies
- questions that block interpretation
- questions that can be carried forward without blocking review

Preserving gaps is a feature, not a failure. It prevents premature closure.

## Anti-Patterns Avoided

This model is designed to avoid common failure modes in AI-assisted analysis:

- treating a polished summary as final truth
- mixing source-backed facts with assumptions
- answering unresolved questions without evidence
- converting risks into recommendations too early
- creating action registers without approval
- assigning owners without source support
- hiding evidence gaps in prose
- treating validation as approval
- copying private or real business material into public artifacts
- presenting synthetic examples as real project evidence

## What This Demonstrates

For process governance, the pattern shows how source material can move through explicit review stages before becoming approved records or actions.

For AI-assisted analysis, it shows how model outputs can be shaped into reviewable artifacts without granting the model decision authority.

For operating model improvement, it demonstrates how teams can separate extraction, evidence mapping, validation, human review, and approval. That separation makes analysis more traceable and reduces the risk of confusing speed with governance.

The broader lesson is that AI transformation depends on review architecture, not only prompting. Evidence-backed artifacts, validation gates, and human approval boundaries make AI-assisted work easier to inspect, challenge, and improve.

## Data Boundary

This note is public-safe and conceptual. It does not include personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, private infrastructure details, private account names, local paths, or copied internal project files.

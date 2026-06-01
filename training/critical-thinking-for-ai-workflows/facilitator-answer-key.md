# Facilitator Answer Key

This answer key supports the worked AI output review exercise. It is intended for public-safe facilitation and does not represent an official training program, certification, production process, or real approval workflow.

## Exercise Reference

- [Worked AI Output Review](examples/worked-ai-output-review.md)
- [Decision Readiness Checklist](examples/decision-readiness-checklist.md)
- [AI Output Review Gate](examples/ai-output-review-gate.md)

## Expected Classifications

| Item | Expected Classification | Facilitator Notes |
| --- | --- | --- |
| The pilot will start with one sample team. | Source-backed fact | Supported by the source notes, though the wider pilot remains conditional. |
| The group approved the intake pilot for next month. | Invented decision | The source only supports a conditional intent to test. Approval is not established. |
| The process owner was assigned to maintain the checklist. | Unsupported owner assignment / follow-up action error | The source says no checklist owner was confirmed. |
| The request form is too long. | Unsupported overclaim | The source says the form may be too long. |
| The form must be replaced with a shorter checklist. | Risk converted into recommendation too early | The source includes a suggestion, not an approved recommendation. |
| A shorter checklist might reduce confusion. | Interpretation | It is plausible but not proven. |
| Reporting expectations have been resolved. | Open question treated as resolved | The source says reporting expectations remain unclear. |
| Users may avoid the form. | Risk | This is supported as a possible adverse outcome. |
| The pilot depends on confirming owner capacity next month. | Condition / assumption requiring confirmation | This should remain visible until confirmed by a human reviewer or owner. |

## Issues That Should Block Approval

The flawed summary should not be approved because it:

- Invents a decision.
- Assigns ownership without evidence.
- Converts a risk into an action recommendation.
- Treats an unresolved reporting question as resolved.
- Converts uncertain language into certainty.
- Collapses reviewable signals into decision language.

These issues are material because they could create false records, premature actions, or misleading governance evidence.

## Items That Can Remain as Reviewable Draft

The following items can remain if correctly labeled:

- The pilot discussion involving one sample team.
- The conditional dependency on owner capacity.
- The risk that the request form may discourage completion.
- The interpretation that a shorter checklist might reduce confusion.
- The open question around reporting expectations.
- The ownership gap for checklist maintenance.
- The proposed follow-up to ask the process owner about pilot scope.

These items are useful because they preserve uncertainty and help a reviewer decide what evidence or approval is still needed.

## Validation Does Not Equal Approval

A structural validation gate could confirm that the summary has sections, categories, and readable formatting. It could also identify missing fields or obvious boundary problems.

Validation cannot prove that:

- the pilot was approved
- the owner assignment is real
- the recommendation is appropriate
- the open question is resolved
- the summary is safe to use as a record

Approval requires an accountable human reviewer to decide what is accepted, rejected, deferred, or returned for rework.

## Decision-Readiness Guidance

The corrected output should be treated as `READY_WITH_WARNINGS` if:

- it clearly separates facts, interpretations, risks, questions, and ownership gaps
- it preserves the conditional nature of the pilot
- it avoids recommendations and invented approvals
- it identifies what needs human confirmation

It should remain `NOT_READY` if it still presents approval, ownership, recommendation, or reporting resolution without evidence.

## Connection to The Daltons

The Daltons case study focuses on turning unstructured notes into reviewable artifacts without treating model output as final truth. This exercise demonstrates the same pattern at training scale:

- source material is separated from model interpretation
- evidence-backed items are labeled
- open questions remain open
- ownership gaps stay visible
- decisions require human approval

## Connection to the Black Signal Governance Model

This exercise maps directly to the shared governance model:

| Governance Concept | Exercise Application |
| --- | --- |
| Input boundary | The exercise uses synthetic source notes only. |
| Source of truth | The source notes control what can be claimed. |
| Structured artifact | The classification table makes the output reviewable. |
| Validation gate | The review gate classifies the flawed summary as fail. |
| Human review | A reviewer decides what is accepted, corrected, or rejected. |
| Approved handoff | Only corrected and reviewed items can become approved records or actions. |
| Anti-overclaim boundary | The exercise blocks invented decisions, recommendations, and certainty. |

## Public-Safe Boundary

Use this answer key only with synthetic or sanitized examples. Do not introduce personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, or private infrastructure details.

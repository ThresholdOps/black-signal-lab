# The Daltons Synthetic Evidence-to-Decision Walkthrough

## Summary

This walkthrough shows how a short fictional source note can move through The Daltons public-safe workflow: source preparation, evidence mapping, validation, handoff, human review, and an approved summary/action record.

It demonstrates the Black Signal Governance Model principle that AI-assisted or system-generated output is a reviewable signal, not final authority.

This walkthrough is synthetic. It does not include real meeting transcripts, real project documents, personal data, company confidential data, internal URLs, private paths, credentials, tokens, secrets, production configuration, or copied internal project files.

## Walkthrough Flow

1. Synthetic source notes.
2. Source profile.
3. Evidence map.
4. Validation result.
5. Handoff note.
6. Human review decision.
7. Approved summary / action record.

## 1. Synthetic Source Notes

The walkthrough starts with short fictional notes:

- [synthetic-source-notes.example.md](examples/synthetic-source-notes.example.md)

The source notes include:

- one apparent decision
- one risk
- one follow-up action
- one ownership gap
- one open question
- one ambiguous assumption

At this stage, nothing is approved. The notes are source material only.

## 2. Source Profile

The source profile describes what the source is, what it may be used for, and what must be excluded:

- [source-profile.example.json](examples/source-profile.example.json)

The source profile helps establish the input boundary. It confirms that the material is synthetic and public-safe, and that outputs must not be treated as factual meeting records, automated decisions, performance evaluations, or production operations.

## 3. Evidence Map

The evidence map turns source material into reviewable items:

- [evidence-map.example.json](examples/evidence-map.example.json)

It separates extracted items from the source notes and links them back to source references. This makes it easier to see what is source-backed and what still requires human review.

In this walkthrough:

- the apparent decision is source-backed but still requires review
- the risk is source-backed and reviewable
- the follow-up action is source-backed but not yet approved
- the open question remains unresolved

The evidence map should not be read as an approved decision log or action register.

## 4. Validation Result

The validation result checks whether the evidence map is complete, public-safe, and ready for review:

- [validation-result.example.json](examples/validation-result.example.json)

Validation can check structure, scope, evidence coverage, and review status. It cannot make the output true.

In this example, validation shows that the artifact is reviewable but not approved. The decision-readiness check fails because a human reviewer must still accept, correct, or reject the extracted items.

## 5. Handoff Note

The handoff note explains what was prepared and what needs review:

- [handoff-note.example.md](examples/handoff-note.example.md)

The handoff makes the review boundary explicit. It tells the reviewer that the source profile, evidence map, and validation result are ready to inspect, but not approved.

## 6. Human Review Decision

Human review is where a reviewable artifact becomes an approved record, a corrected artifact, a rejected interpretation, or an escalated question.

The reviewer should distinguish:

- source-backed facts from interpretation
- apparent decisions from approved decisions
- assumptions from confirmed rules
- risks from recommendations
- follow-up actions from assigned work
- open questions from resolved answers

In this walkthrough, the fictional reviewer:

- approves the apparent decision as a synthetic decision record
- accepts the follow-up action as a demonstration item
- leaves the open question unresolved
- keeps the ownership gap visible
- defers the ambiguous assumption instead of treating it as a rule

## 7. Approved Summary / Action Record

The approved summary shows how a human-reviewed record can look after review:

- [approved-summary.example.md](examples/approved-summary.example.md)

The approved summary is not model output treated as truth. It exists only after a human review decision in the synthetic example.

It distinguishes:

- approved decision
- accepted action
- unresolved open question
- ownership gap requiring clarification
- deferred interpretation

## Source-Backed, Interpretation, Open Question, and Human Review

This walkthrough separates review categories:

| Category | Example in walkthrough | Review status |
| --- | --- | --- |
| Source-backed item | Apparent decision to document intake criteria | Reviewable before approval |
| Interpretation | Assumption that all future examples remain synthetic | Deferred, not approved as a rule |
| Open question | How to handle low-confidence interpretations | Preserved unresolved |
| Risk | Outputs may be mistaken for approved records | Source-backed, requires review |
| Follow-up action | Create validation checklist | Accepted only after human review |
| Ownership gap | Reviewer role needed but owner not named | Preserved as clarification need |

## Why Validation Does Not Mean Approval

Validation checks whether the artifact is ready to review. It can show that required fields exist, evidence links are present, and data boundaries are respected.

Validation does not decide whether a decision is real, whether an action should happen, or who owns the work.

Approval requires human review.

## What This Demonstrates

This walkthrough demonstrates:

- process governance through explicit input and review boundaries
- AI-assisted analysis without treating model output as final truth
- evidence-backed traceability from source notes to review artifacts
- validation as a review aid, not approval
- human judgment as the boundary for approved summaries and actions
- operating model improvement through clearer artifacts, handoffs, and accountability gaps

## Data Boundary

This walkthrough is public-safe and synthetic. It does not include personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, private infrastructure details, private account names, local paths, or copied internal project files.

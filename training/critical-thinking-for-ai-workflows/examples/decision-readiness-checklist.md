# Example: Decision Readiness Checklist

This checklist helps reviewers decide whether an AI-assisted artifact is ready for human approval, needs rework, or should remain a reviewable draft.

It is a public-safe template and does not represent a real project, approval process, or production workflow.

## Artifact Identity

| Field | Placeholder |
| --- | --- |
| Artifact name | `[artifact name]` |
| Source material | `[synthetic or approved source reference]` |
| Reviewer | `[reviewer role or placeholder]` |
| Review date | `[date placeholder]` |
| Intended use | `[record / decision support / action review / other]` |

## Readiness Checks

| Check | Pass / Warning / Fail | Notes |
| --- | --- | --- |
| Input boundary is clear. | `[status]` | `[notes]` |
| Source-backed facts are traceable to supplied material. | `[status]` | `[notes]` |
| Interpretations are labeled as interpretations. | `[status]` | `[notes]` |
| Assumptions are separated from facts. | `[status]` | `[notes]` |
| Open questions are preserved, not answered by invention. | `[status]` | `[notes]` |
| Risks are described without becoming recommendations. | `[status]` | `[notes]` |
| Decisions are supported by explicit approval evidence. | `[status]` | `[notes]` |
| Follow-up actions have accepted owner, scope, and next step. | `[status]` | `[notes]` |
| Validation result is recorded separately from approval. | `[status]` | `[notes]` |
| Human review outcome is recorded. | `[status]` | `[notes]` |

## Decision Readiness Outcome

Choose one:

- `READY_FOR_HUMAN_APPROVAL` - the artifact is structured and reviewable enough for an accountable reviewer.
- `READY_WITH_WARNINGS` - the artifact is useful but has unresolved gaps that must remain visible.
- `NOT_READY` - the artifact contains unsupported claims, missing evidence, unclear boundaries, or unsafe action language.

## Approval Boundary

Passing this checklist does not approve the content. It only indicates whether the artifact is ready to be reviewed for approval.

An approved record or action requires a human reviewer to accept the relevant decision, action, or summary.

## Public-Safe Boundary

Do not use this checklist with personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, or private infrastructure details inside this public repository.

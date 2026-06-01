# Example: AI Output Review Gate

This gate supports human review of AI-assisted artifacts before they are used as records, decision inputs, or action inputs.

It is a public-safe template. It does not approve content by itself.

## Gate Principle

Validation makes output easier to inspect. Human review decides whether it can be trusted, accepted, or acted on.

## Review Context

| Field | Placeholder |
| --- | --- |
| Artifact type | `[source profile / evidence map / decision log / open questions / other]` |
| Input source | `[synthetic or approved source reference]` |
| Output location | `[approved review location placeholder]` |
| Reviewer | `[reviewer role or placeholder]` |
| Review status | `[draft / reviewed / approved / rejected / deferred]` |

## Boundary Checks

- Input material is allowed for this review.
- Output does not include personal data or confidential data.
- Output does not introduce unsupported facts.
- Output does not cite sources that were not supplied.
- Output does not invent ownership, approval, or accountability.
- Output does not treat validation as approval.

## Category Checks

| Category | Review Prompt |
| --- | --- |
| Source-backed fact | Is the fact traceable to supplied material? |
| Interpretation | Is it labeled as interpretation rather than fact? |
| Assumption | Is confirmation evidence identified? |
| Open question | Is the question preserved rather than answered by invention? |
| Risk | Is the risk descriptive, not a hidden recommendation? |
| Decision | Is there explicit approval evidence? |
| Follow-up action | Is the owner and next step accepted by a human reviewer? |

## Validation Result

Choose one:

- `PASS` - structurally reviewable and within boundary.
- `PASS_WITH_WARNINGS` - usable for review but contains visible uncertainty or minor structure issues.
- `FAIL` - unsafe, unsupported, incomplete, or not reviewable.

## Human Review Result

Choose one:

- `APPROVED_RECORD` - accepted as an approved record.
- `APPROVED_ACTION` - accepted as an approved follow-up action.
- `REVIEWABLE_DRAFT` - useful but not approved.
- `RETURN_FOR_REWORK` - needs correction before review can continue.
- `REJECTED` - not suitable for use.

## Anti-Overclaim Checks

- The artifact does not claim production readiness.
- The artifact does not claim final truth.
- The artifact does not convert uncertainty into certainty.
- The artifact does not convert risk into instruction.
- The artifact does not convert open questions into answers.
- The artifact does not convert model output into approved decision language.

## Public-Safe Boundary

Do not use this gate to store personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, or private infrastructure details inside this public repository.

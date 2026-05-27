# Validation Gate Example

## Gate Name

Public Portfolio Readiness Gate

## Purpose

Check whether an AI-assisted workflow artifact is ready for human review as a public portfolio item.

## Checks

| Check | Pass Criteria | Status |
| --- | --- | --- |
| Scope | Artifact matches the approved task contract. | Pending review |
| Public safety | No personal data, confidential data, private paths, internal URLs, credentials, tokens, secrets, or production configuration. | Pending review |
| Governance framing | Artifact emphasizes AI-assisted workflow governance rather than implementation detail. | Pending review |
| Bounded execution | Artifact describes clear limits, exclusions, and review points. | Pending review |
| Human-in-the-loop control | Artifact states that a person approves publication or external action. | Pending review |
| Evidence quality | Claims are high-level, supportable, and do not overstate production readiness. | Pending review |

## Result Options

- **Pass** - ready for human review.
- **Revise** - changes required before human review.
- **Reject** - artifact is outside scope or contains restricted material.

## Example Result

Result: Revise

Reason: The artifact is structurally complete, but the reviewer should confirm that all examples are synthetic and that no private operational details are implied.

## Next Step

Human reviewer decides whether to approve, revise, or discard the artifact.

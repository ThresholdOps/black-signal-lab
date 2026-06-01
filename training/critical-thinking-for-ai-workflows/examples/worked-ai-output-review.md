# Worked Exercise: AI Output Review

This worked exercise shows how to review a flawed AI-assisted summary using critical-thinking categories, a decision-readiness checklist, and an AI output review gate.

The scenario is fictional and public-safe. It does not describe a real organization, person, project, meeting, or operational environment.

## 1. Synthetic Source Notes

A review group discussed a draft request intake process for a small internal pilot. The notes state:

- The group wants to test the draft process with one sample team before using it more widely.
- The pilot is conditional on confirming whether a process owner has capacity next month.
- One participant said the request form may be too long and could discourage completion.
- Another participant suggested a shorter checklist might reduce confusion.
- No owner was confirmed for maintaining the checklist.
- Reporting expectations for the pilot remain unclear.
- A follow-up was proposed to ask the process owner whether the pilot scope is acceptable.

## 2. Flawed AI-Assisted Summary

> The review group approved the intake pilot for next month and assigned the process owner to maintain the new checklist. The request form is too long and must be replaced with a shorter checklist to reduce confusion. Reporting expectations have been resolved because the pilot will use the new checklist. The group identified a risk that users may avoid the form, so the recommendation is to launch the shorter checklist immediately. The pilot will start with one sample team.

## 3. Review Task

Review the flawed summary and identify:

- What is source-backed.
- What is interpretation.
- What is assumption.
- What remains an open question.
- What is a risk.
- What is presented as a decision without enough evidence.
- What is presented as a follow-up action without enough evidence.
- What is an unsupported overclaim.

Then decide whether the output should pass, pass with warnings, or fail the review gate.

## 4. Classification Table

| Flawed Summary Item | Classification | Review Finding |
| --- | --- | --- |
| The pilot will start with one sample team. | Source-backed fact | The source notes state that the group wants to test the draft process with one sample team. |
| The group approved the intake pilot for next month. | Invented decision | The source says the pilot is conditional on capacity confirmation. Approval is not established. |
| The process owner was assigned to maintain the checklist. | Follow-up action / owner assignment without evidence | The source says no owner was confirmed for checklist maintenance. |
| The request form is too long. | Unsupported overclaim | The source says the form may be too long, not that this is confirmed. |
| The form must be replaced with a shorter checklist. | Risk converted into recommendation too early | The source includes a concern and a suggestion, but no approved recommendation. |
| A shorter checklist might reduce confusion. | Interpretation | The source includes this as a suggestion, not a proven outcome. |
| Reporting expectations have been resolved. | Open question treated as resolved | The source says reporting expectations remain unclear. |
| Users may avoid the form. | Risk | This is supported as a concern based on the note that the form may discourage completion. |
| The pilot depends on confirming owner capacity next month. | Assumption / condition requiring confirmation | The source states this condition; it should remain visible until confirmed. |

## 5. Review Gate Result

**Result: FAIL**

Reasons:

- The summary invents approval for a conditional pilot.
- It assigns ownership without source evidence.
- It turns a risk into a recommendation before human review.
- It treats an open question as resolved.
- It overstates an uncertain concern as a confirmed fact.
- It includes one valid source-backed item, but the boundary failures are material.

This output should not become an approved record or action. It can be used as a teaching example or returned for correction.

## 6. Corrected Reviewable Output

| Category | Reviewable Output |
| --- | --- |
| Source-backed fact | The group discussed testing the draft request intake process with one sample team. |
| Conditional item | The pilot depends on confirming whether a process owner has capacity next month. |
| Risk | The request form may be too long and may discourage completion. |
| Interpretation | A shorter checklist might reduce confusion, but this has not been validated. |
| Open question | Reporting expectations for the pilot remain unclear. |
| Ownership gap | No owner was confirmed for maintaining the checklist. |
| Follow-up action candidate | Ask the process owner whether the pilot scope is acceptable. |
| Decision status | No final approval is established in the source notes. |

## 7. What Changed and Why

- The corrected output separates source-backed facts from interpretation.
- Conditional approval language was removed because approval was not supported.
- The owner assignment was converted into an ownership gap.
- The recommendation to launch the checklist was removed because the source only contains a suggestion.
- The reporting item was restored as an open question.
- The risk remains visible without becoming an action.
- The follow-up remains a candidate until a human reviewer accepts it.

## 8. Privacy / Data Boundary

This exercise uses synthetic notes only. It does not include personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, or private infrastructure details.

Do not use real business material in this public exercise. Real review artifacts should remain in an approved business environment and require accountable human review before becoming approved records or actions.

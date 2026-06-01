# From Evidence to Decision: Critical Thinking for AI-Assisted Analysis and Process Governance

This public training outline introduces a practical critical-thinking model for AI-assisted analysis, evidence mapping, decision readiness, validation gates, and human review.

It is designed as a workshop-style portfolio module, not as an accredited course, certification, official training program, or production implementation guide.

## Purpose

AI-assisted workflows can produce useful structure quickly, but speed does not make an output true, complete, or approved. This module teaches participants to inspect AI-assisted outputs before those outputs influence records, decisions, or follow-up work.

The core principle is simple:

> AI output is a reviewable signal, not final authority.

## Learning Goals

Participants should be able to:

- Distinguish source-backed facts, interpretations, assumptions, open questions, risks, decisions, and follow-up actions.
- Explain why evidence mapping matters for reviewability and traceability.
- Identify where validation checks help and where they stop.
- Review AI-assisted output before using it as a record, decision aid, or action input.
- Explain how human review turns reviewable output into an approved record or action.
- Recognize common anti-patterns in AI-assisted analysis and process governance.

## Module Contents

- [Facilitator Outline](facilitator-outline.md) - suggested structure for running a public-safe workshop or discussion session.
- [Participant Workbook](participant-workbook.md) - participant-facing exercises and reflection prompts.
- [Facilitator Answer Key](facilitator-answer-key.md) - expected classifications and review guidance for the worked exercise.
- [Evidence vs Interpretation Example](examples/evidence-vs-interpretation.md) - synthetic classification exercise.
- [Decision Readiness Checklist](examples/decision-readiness-checklist.md) - review checklist for deciding whether an artifact is ready for approval.
- [AI Output Review Gate](examples/ai-output-review-gate.md) - gate template for reviewing AI-assisted artifacts before handoff.
- [Worked AI Output Review](examples/worked-ai-output-review.md) - worked exercise showing how to review a flawed AI-assisted summary.

## Core Distinctions

| Category | Meaning | Review Question |
| --- | --- | --- |
| Source-backed fact | Directly supported by supplied material. | What source evidence supports it? |
| Interpretation | A reasoned reading of the source material. | Is it clearly labeled as interpretation? |
| Assumption | A statement treated as plausible but not proven. | What would confirm or reject it? |
| Open question | A gap that still needs an answer. | Who can answer it, and what evidence is needed? |
| Risk | A possible adverse outcome or uncertainty. | What evidence shows exposure or impact? |
| Decision | A choice approved by an accountable reviewer or body. | Who approved it, and where is that approval recorded? |
| Follow-up action | Work that should happen after review. | Who owns it, and what is the accepted next step? |

## Why Evidence Mapping Matters

Evidence mapping separates what the source says from what a reviewer or model infers. It helps teams avoid treating a fluent summary as a verified record. It also makes later review easier because claims, gaps, questions, and decisions can be traced back to the material that produced them.

Evidence mapping does not guarantee truth. It improves inspectability.

## Validation Does Not Equal Approval

A validation gate can check whether an artifact has required fields, follows a structure, avoids obvious boundary violations, or preserves required categories. It cannot decide whether the content is true, complete, appropriate, or approved for action.

Approval requires human review by an accountable person or group.

## Case Study Connections

- **The Daltons** shows how unstructured notes can be converted into evidence-backed review artifacts without treating model output as final truth.
- **SAMAEL** shows how bounded execution, validation gates, and human handoff can keep agent-assisted work inspectable.
- **NOESIS** shows how telemetry and structured signals can support interpretation without replacing source-of-truth boundaries.
- **Black Signal Governance Model** provides the shared pattern: input boundary, structured artifact, validation gate, human review, and approved handoff.

## Public-Safe Boundary

This module uses synthetic and generalized examples only. It does not include personal data, company confidential data, real meeting transcripts, real project documents, real task logs, internal URLs, private paths, credentials, tokens, secrets, production configuration, or private infrastructure details.

# SAMAEL

## Summary

SAMAEL is a public, sanitized case study about AI-assisted task orchestration, project memory, validation gates, and human-in-the-loop execution.

It demonstrates how agent-assisted work can be organized as bounded execution: clear task scope, explicit context, reviewable artifacts, validation before completion, and human approval before external action.

## Problem

AI-assisted workflows can accelerate analysis and execution, but unmanaged agent behavior creates governance risk. Common failure modes include unclear objectives, lost context between sessions, weak evidence trails, missing review points, and model output being treated as final without human judgment.

SAMAEL addresses this by framing AI work as a governed workflow rather than an open-ended automation system.

## Public-Safe Workflow Model

At a high level, the workflow uses five public-safe concepts:

1. **Task contract** - defines the objective, scope, exclusions, expected artifacts, and review requirements.
2. **Project memory** - preserves relevant decisions, constraints, and context so work does not depend only on chat history.
3. **Bounded execution** - keeps agent-assisted work inside the approved task scope.
4. **Validation gates** - check outputs against explicit criteria before completion or escalation.
5. **Human review** - keeps responsibility for approval, publication, deployment, and external action with a person.

This model is intentionally governance-oriented. It is not presented as uncontrolled autonomous AI or as a production-readiness claim.

## Role of Task Contracts

Task contracts make the work inspectable before execution begins. A contract states what the agent-assisted workflow is expected to do, what it must not do, what artifacts it should produce, and where human review is required.

See [task-contract.example.md](examples/task-contract.example.md) for a sanitized example.

## Role of Project Memory

Project memory provides durable context for recurring work: known constraints, prior decisions, terminology, open questions, and review boundaries. The purpose is to reduce drift and repeated rediscovery while keeping sensitive material out of public artifacts.

In this public case study, project memory is described only as a governance pattern. No private memory records, internal logs, or operational details are included.

## Role of Validation Gates

Validation gates convert review expectations into explicit checks. They can cover scope, artifact completeness, privacy boundaries, evidence quality, and readiness for human review.

See [validation-gate.example.md](examples/validation-gate.example.md) for a sanitized example.

## Role of Human Review

Human review is the control point for decisions that matter: accepting outputs, publishing artifacts, changing systems, escalating issues, or committing work. The agent-assisted workflow prepares evidence and drafts; it does not replace accountable judgment.

See [handoff-note.example.md](examples/handoff-note.example.md) for a sanitized example.

## What This Demonstrates

SAMAEL demonstrates AI transformation and workflow governance patterns that are useful beyond a single tool:

- structuring AI-assisted work around contracts and artifacts
- preserving context without exposing sensitive data
- using validation gates to reduce unchecked model output
- separating draft generation from human approval
- making agent-assisted workflows easier to audit, review, and improve

## Example Artifacts

- [Task contract example](examples/task-contract.example.md)
- [Validation gate example](examples/validation-gate.example.md)
- [Handoff note example](examples/handoff-note.example.md)

## Further Reading

- [SAMAEL public boundary](public-boundary.md)
- [SAMAEL governance pattern](governance-pattern.md)

## Data Boundary

This case study contains only public, synthetic, anonymized, or fully sanitized material.

It does not include personal data, company confidential data, real task logs, real meeting transcripts, internal URLs, private paths, credentials, tokens, secrets, private infrastructure details, private account names, local paths, production configuration, or copied internal project files.

# NOESIS Workflow

This public-safe diagram shows NOESIS as a governance-oriented observability model. It separates authoritative system state from telemetry, interpretation, and human-readable or AI-readable context.

```mermaid
flowchart LR
    State[Authoritative system state]
    Contract[Telemetry event contract]
    Record[Telemetry record]
    Layer[Interpretation layer]
    Gate[Observability gate]
    Human[Human-readable system context]
    AI[AI-readable system context]

    State --> Contract
    Contract --> Record
    Record --> Layer
    Layer --> Gate
    Gate --> Human
    Gate --> AI
    Human --> Review[Human review]
    AI --> Review
    Review --> Decision[Governance decision]
    Decision -. may confirm or trigger controlled update .-> State
```

## What This Demonstrates

NOESIS demonstrates how telemetry and structured signals can support interpretation without replacing the source of truth. Observability gates help keep reporting bounded, reviewable, and suitable for both human review and AI-assisted system context.

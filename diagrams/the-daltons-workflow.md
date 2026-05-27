# The Daltons Workflow

This public-safe diagram shows The Daltons as a structured analysis workflow for meeting or document material. It emphasizes evidence mapping, JSON artifacts, validation gates, and reviewable outputs.

```mermaid
flowchart LR
    Source[Source profile]
    Evidence[Evidence mapping]
    JSON[JSON artifacts]
    Validation[Validation result]
    Review[Human review]
    Approved[Approved summary or action record]

    Source --> Evidence
    Evidence --> JSON
    JSON --> Validation
    Validation --> Review
    Review --> Approved
    Review --> Clarify[Clarification or correction]
    Clarify --> Evidence
```

## What This Demonstrates

The Daltons demonstrates how unstructured inputs can become structured artifacts without treating model output as final truth. Evidence mapping and validation results make the output easier to inspect before a human approves any summary or action record.

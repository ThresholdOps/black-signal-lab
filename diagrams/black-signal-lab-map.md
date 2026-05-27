# Black Signal Lab Portfolio Map

This public-safe diagram shows how the three case studies relate to the shared portfolio themes: validation gates, human-in-the-loop review, structured artifacts, and source-of-truth boundaries.

```mermaid
flowchart TB
    Lab[Black Signal Lab]

    Samael[SAMAEL: AI-assisted task orchestration]
    Daltons[The Daltons: structured meeting and document analysis]
    Noesis[NOESIS: telemetry and interpretation layer]

    Gates[Validation gates]
    Review[Human-in-the-loop review]
    Artifacts[Structured artifacts]
    Truth[Source-of-truth boundaries]

    Lab --> Samael
    Lab --> Daltons
    Lab --> Noesis

    Samael --> Gates
    Samael --> Review
    Samael --> Artifacts
    Samael --> Truth

    Daltons --> Gates
    Daltons --> Review
    Daltons --> Artifacts
    Daltons --> Truth

    Noesis --> Gates
    Noesis --> Review
    Noesis --> Truth
    Noesis --> Artifacts
```

## What This Demonstrates

The portfolio is organized around governance and operating-model patterns rather than isolated tools. Each case study shows a different way to make AI-assisted or system-supported work more explicit, reviewable, and bounded.

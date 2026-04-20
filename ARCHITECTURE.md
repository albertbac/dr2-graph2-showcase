# Architecture

## High-level architecture
- Classification: ADJACENT SYSTEM
- Category: adjacent-system
- Confidence: MEDIUM
- Exposure risk: MEDIUM

```mermaid
    flowchart LR
        A[Portal layer]
    B[Visualization engines]
    C[Narrative layer]
    D[Data preparation service]
    E[Report surface]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Portal layer
- Visualization engines
- Narrative layer
- Data preparation service
- Report surface

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.

# TARS
Ai chat agent experiment to help and assist with everything and anything.

# TARS

AI chat agent experiment to help and assist with everything and anything.

```mermaid
flowchart LR
    A[Messaging Adapters<br/>WhatsApp · CLI · Web · API]
    B[Event Router<br/>who said what, where]
    C[Agent Kernel<br/><b>THE CORE</b><br/>Intent Detection · Planning · Tool Selection · Safety Checks]
    D[Runtime<br/>Skills / Actions · Permissions · Sandboxing]
    E[System<br/>Short-term Context · Long-term Memory - Vector Store]
    F[LLM]

    A --> B --> C --> D --> E --> F

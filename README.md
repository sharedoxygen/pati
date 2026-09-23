<div align="center">

# PATi

### Private Algorithmic Trading

A self-hosted desk for **equities, options, and crypto**.  
Research, decisions, and history stay on **your** infrastructure.

</div>

```mermaid
%%{init: {"theme": "base", "flowchart": {"htmlLabels": false, "curve": "basis", "padding": 8, "nodeSpacing": 16, "rankSpacing": 16}}}%%
flowchart LR
  A(["Self-hosted"])
  B(["Equities · Options · Crypto"])
  C(["International"])
  D(["September 2026"])
  A ~~~ B ~~~ C ~~~ D

  style A fill:#4F46E5,stroke:#312E81,stroke-width:2px,color:#F8FAFC
  style B fill:#0F766E,stroke:#134E4A,stroke-width:2px,color:#F0FDFA
  style C fill:#0369A1,stroke:#0C4A6E,stroke-width:2px,color:#F0F9FF
  style D fill:#C2410C,stroke:#7C2D12,stroke-width:2px,color:#FFF7ED
```

---

## Where it sits

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "basis"}}}%%
flowchart LR
  subgraph yours ["Your infrastructure"]
    direction LR
    desk["Operator desk"]
    core["PATi"]
    desk <--> core
  end
  outside["Brokers and data<br/>you entitle"]
  core --> outside

  style yours fill:#EEF2FF,stroke:#4F46E5,stroke-width:2px,color:#1E1B4B
  style desk fill:#4F46E5,stroke:#312E81,stroke-width:2px,color:#F8FAFC
  style core fill:#7C3AED,stroke:#5B21B6,stroke-width:2px,color:#F5F3FF
  style outside fill:#0F766E,stroke:#134E4A,stroke-width:2px,color:#F0FDFA
```

You keep the desk. Venues stay connections you choose. Intelligence can run beside it, on your hardware.

---

## How a decision moves

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "basis"}}}%%
flowchart LR
  S["Specialist roles"] --> C["Consensus"]
  C --> R{"Risk"}
  R -->|Clear| G["Proceed"]
  R -->|Veto| N["Stop and record"]

  style S fill:#7C3AED,stroke:#5B21B6,stroke-width:2px,color:#F5F3FF
  style C fill:#2563EB,stroke:#1E3A8A,stroke-width:2px,color:#EFF6FF
  style R fill:#D97706,stroke:#92400E,stroke-width:2px,color:#1C1917
  style G fill:#059669,stroke:#065F46,stroke-width:2px,color:#ECFDF5
  style N fill:#E11D48,stroke:#9F1239,stroke-width:2px,color:#FFF1F2
```

Ideas and permission are separate. Risk can say no.

---

## How a session moves

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "basis"}}}%%
flowchart LR
  P["Prepare"] --> D["Decide"] --> M["Manage"] --> X["Close"]
  X -.-> P

  style P fill:#F59E0B,stroke:#B45309,stroke-width:2px,color:#1C1917
  style D fill:#38BDF8,stroke:#0369A1,stroke-width:2px,color:#082F49
  style M fill:#A78BFA,stroke:#5B21B6,stroke-width:2px,color:#1E1B4B
  style X fill:#FB7185,stroke:#9F1239,stroke-width:2px,color:#4C0519
```

One rhythm, across sessions: prepare, decide, manage, close.

---

## What you operate

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "basis"}}}%%
flowchart TB
  D["Dashboard<br/>capital at a glance"]
  O["Operations<br/>the live desk"]
  W["Session Watchlist<br/>names for this session"]
  L["Analytics and learning<br/>what the session taught"]

  D --- O --- W
  O --- L

  style D fill:#4F46E5,stroke:#312E81,stroke-width:2px,color:#F8FAFC
  style O fill:#7C3AED,stroke:#5B21B6,stroke-width:2px,color:#F5F3FF
  style W fill:#0284C7,stroke:#075985,stroke-width:2px,color:#F0F9FF
  style L fill:#0F766E,stroke:#134E4A,stroke-width:2px,color:#F0FDFA
```

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "basis"}}}%%
flowchart LR
  P["Posture"] --- B["Book"] --- K["Brokers"] --- M["Markets"] --- A["Automation"] --- H["Health"] --- Q["Quality"]

  style P fill:#4F46E5,stroke:#312E81,stroke-width:2px,color:#F8FAFC
  style B fill:#7C3AED,stroke:#5B21B6,stroke-width:2px,color:#F5F3FF
  style K fill:#0F766E,stroke:#134E4A,stroke-width:2px,color:#F0FDFA
  style M fill:#0284C7,stroke:#075985,stroke-width:2px,color:#F0F9FF
  style A fill:#D97706,stroke:#92400E,stroke-width:2px,color:#1C1917
  style H fill:#E11D48,stroke:#9F1239,stroke-width:2px,color:#FFF1F2
  style Q fill:#0EA5E9,stroke:#0369A1,stroke-width:2px,color:#082F49
```

The book holds equities, options, and crypto. Ask PATi what is true on the desk right now.

| | |
| --- | --- |
| **Custody** | Your machines. Your history. |
| **Governance** | Specialists propose. Risk can veto. |
| **Rhythm** | A full session, not a one-off alert. |
| **Evidence** | Blocks and fills leave a trail. |

PATi does not promise returns.

---

<div align="center">

Trading can lose money. You own compliance, market-data rights, and broker terms.<br/>
This page is not investment advice.

**Shared Oxygen, LLC** · September 2026

</div>

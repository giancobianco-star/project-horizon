# PROJECT HORIZON

**Strategic Foresight Radar — Prototype v0.1**

Project Horizon is a lightweight executive intelligence dashboard designed to turn external signals into decision-relevant strategic foresight.

The prototype is deliberately **not** a news aggregator. Each signal is structured around:

- What changed?
- Why could it matter?
- What is the potential impact?
- What is the probability and velocity?
- How relevant is it to the Panama Canal context?
- What should be watched next?
- Is the signal a threat, opportunity, or both?
- How strong is the evidence?

## Prototype architecture

```text
project-horizon/
├── index.html              Executive dashboard
├── styles.css              Interface system
├── app.js                  Rendering and filters
├── data/
│   └── signals.json        Structured intelligence signals
└── README.md
```

## Verification model

Signals should be checked across five layers whenever applicable:

1. **Primary / official** — authorities, regulators, official datasets and direct notices.
2. **High-trust independent** — Reuters, AP, Bloomberg and equivalent sources.
3. **Specialized / data** — maritime, climate, markets and sector-specific intelligence sources.
4. **Panama narrative layer** — local media and public conversation used to understand perception, not as automatic proof of fact.
5. **ACP Comunicación Internacional cross-check** — internal human validation layer when available. This prototype does not have direct access to internal ACP systems.

Every signal carries a confidence level and should keep **fact**, **interpretation**, and **hypothesis** conceptually separate.

## Scoring model — prototype

The current 0–100 score is an analyst score intended to be replaced by a calculated model combining:

`impact × probability × velocity × ACP relevance × confidence`

Prototype bands:

- 0–39: Green — monitor
- 40–59: Yellow — watch
- 60–79: Orange — elevated attention
- 80–100: Red — immediate executive attention

Scores in v0.1 are analytical estimates, not objective measurements.

## Core radar

- Water & Climate
- Maritime & Trade
- Panama Watch
- Geopolitics
- Macro & Markets
- Energy
- Infrastructure & Logistics
- Technology
- Institutional & Regulatory
- Reputation
- Security
- Emerging / Weak Signals

## v0.1 sample data

The initial dashboard is seeded with timestamped public signals from September 1, 2026. The goal is to test the **decision interface and analytical discipline**, not yet to claim autonomous continuous monitoring.

## Roadmap

**v0.2 — Signal engine**
- source registry
- calculated scoring
- trajectories and status changes
- fact / hypothesis / interpretation fields
- evidence conflicts and confidence penalties

**v0.3 — Briefing layer**
- 60-second executive brief
- morning / noon / close / evening pulses
- weekly intelligence report
- scenario cards and indicators to watch

**v0.4 — Automation**
- scheduled ingestion
- alert thresholds
- historical signal store
- change detection
- analyst feedback loop

**v1.0 — Strategic operating system**
- integrated foresight workflows
- scenario history
- institutional memory
- executive decision log
- training prompts that challenge the analyst before revealing the system assessment

---

Project Horizon is a prototype strategic foresight tool. It is not an official Panama Canal Authority product and should not be presented as one.
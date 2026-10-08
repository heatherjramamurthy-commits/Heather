# District AI Roadmap

A single-file planning dashboard for a two-year AI roadmap at a wastewater special district. It covers the treatment plant, the collection system, engineering, permitting, the lab, compliance and administration.

Open `ai-roadmap-dashboard.html` in any browser. There's no build step and no server. Edits are saved in your browser, and the **Brief & save** tab exports a scenario as text you can share or reload.

## How it works

- **Portfolio:** the one list of use cases (51 seeded) and the source of truth for everything else.
- **Roadmap:** calculated, not hand-drawn. Each in-scope item starts at the earliest quarter where:
  - its prerequisites are done,
  - its readiness gates are met, using today's scores plus the lift from finished foundations,
  - procurement lead time has passed, and
  - team capacity is free.

  The reason for every delay is shown.
- **Readiness & guardrails:** six readiness scores, planning assumptions, gate rules and the non-negotiables (no AI writes to SCADA, a human certifies regulatory submissions, and so on).
- **Budget:** costs follow the schedule and are split by fiscal year against an annual envelope. Also shows the recurring run-rate that continues after the window.
- **Horizon scan:** an adopt/pilot/watch/hold view of developments relevant to wastewater utilities, with sources (researched October 2026).

## Origin

This replaces two GovAI-built prototypes (`index_6_dashboard_assumption_driven.html` and `index_6_dashboard_governance_flags_sync_fixed.html`). It merges the following into one model:

- their four separate entry points (library, custom tab, supplemental form, market research wizard),
- their three cost rollups, and
- their phase recommendations.

All costs are directional planning ranges, not quotes.

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
- **Budget:** costs follow the schedule and are split by fiscal year against an annual envelope, with one editable table of every project's cost ranges. Also shows the recurring run-rate that continues after the window.
- **Buying guide:** a vendor-neutral selection framework: purchase type, business requirements marked Must/Should/Nice, category weights, a scoring matrix you fill with options as you evaluate them, and standard vendor questions.
- **Horizon scan:** an adopt/pilot/watch/hold view of developments relevant to wastewater utilities, with sources (researched October 2026).

## Standing principles

- **Vendor-neutral.** The dashboard recommends criteria and a selection process, not products. Vendors are added in the Buying guide as the District evaluates them. The page was drafted with Claude (Anthropic), which also holds California's CDT agreement, and it discloses that wherever that agreement is mentioned.
- **The assistant decision is separate from SharePoint.** A general-purpose assistant can launch while the Varonis-assisted SharePoint/Teams cleanup continues. M365 Copilot stays gated on the cleanup and starts as a small pilot on cleaned sites.
- **Decisions have owners, deadlines and defaults.** When no one decides, the documented default applies.

## Origin

This replaces two GovAI-built prototypes (`index_6_dashboard_assumption_driven.html` and `index_6_dashboard_governance_flags_sync_fixed.html`). It merges the following into one model:

- their four separate entry points (library, custom tab, supplemental form, market research wizard),
- their three cost rollups, and
- their phase recommendations.

All costs are directional planning ranges, not quotes.

# Anthropic Economic Index — Learning Curves (March 2026 report)

**Author(s):** Anthropic Economic Research team
**Year:** March 2026 (third Economic Index release)
**Venue:** Anthropic research publications
**URL:** https://www.anthropic.com/research/economic-index-march-2026-report
**Primary or secondary:** Primary research (Anthropic-internal cohort analysis of Claude.ai + API usage)

## Why this matters to the research

First empirical signal in the wiki that **individual sustained AI use compounds**. Reports that users active on Claude for **6+ months show a 10% higher success rate** in conversations, controlling for task type and difficulty. This is the user-level analogue of the McElheran J-curve documented at the firm level in [[ai-productivity-firm-level]]: just as firms cross the J trough through complementary investment, individual users cross a personal learning curve through prompting skill accumulation.

Two additional load-bearing findings:

- **Augmentation share rising, automation share falling** between November 2025 and February 2026 (in Claude.ai), with the inverse pattern in 1P API data. Direct empirical pressure on the canonical [[autonomy-slider]] framing — augmentation may be the durable equilibrium for knowledge-work deployments, automation the durable equilibrium for embedded-API enterprise use.
- **Reliability-adjusted productivity estimate roughly halves the headline** from 1.8 pp to ~1.0 pp annual labour-productivity growth over the next decade. Crucial reconciliation between [[task-based-framework]]'s pessimistic <0.71% TFP cap and the 0.2–1.3 pp OECD G7 projection — when reliability adjustments are applied, the two converge much closer than the unadjusted headlines suggest.

Anthropic's role as both the source of the measurement and the vendor whose deployments are being measured is itself an open question (parallel to the [[massenkoff-mccrory-labor-market-impacts-2026]] case). Should be flagged on ingest.

## Wiki pages likely affected

- [[ai-productivity-firm-level]] — user-level learning curve as complement to firm-level J-curve.
- [[autonomy-slider]] — automation-vs-augmentation share data as direct empirical update.
- [[task-based-framework]] — reliability-adjusted estimate as reconciliation point with the <0.71% TFP cap.
- [[continual-learning-paradigm]] — adjacent: the 10% success-rate compounding is the human-side mirror of the model-side continual-learning argument.
- [[theoretical-vs-observed-capability-gap]] — direct successor measurement using the same Anthropic methodology family.
- Potentially a new data page in `wiki/data/` for the 10% success-rate-after-6-months figure and the reliability-adjusted 1.0 pp.

## Suggested by

EnomisExcell — 2026-05-27 — surfaced via `/discover` pass on individual-level sustained-use evidence. Companion to the firm-level Stanford 51-deployment stub and the user-level developer-productivity arxiv stub in the same PR.

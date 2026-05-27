---
title: Measurement as Causal Upstream of AI Deployment Success
status: draft
tags:
  - concept
  - measurement
  - scaling-gap
  - empirical
  - causality
last-updated: 2026-05-27
contributors: EnomisExcell
---

# Measurement as Causal Upstream of AI Deployment Success

The [[scaling-gap]] is conventionally read three ways (managerial, bear-structural, middle-dies). A fourth reading is empirically tighter than the existing three: **layered measurement, instrumented before deploy, is causally upstream of success — not correlated with it, not a consequence of it, upstream of it**. The 74% that struggle and the 16% that scale separate primarily on whether five-layer measurement was built before the AI was switched on.

## What it is

The wiki's [[scaling-gap]] concept page documents the 74% / 16% BCG / Accenture artefact and notes "the survey reports the gap but not its mechanism." The McKinsey QuantumBlack five-layer measurement framework ([[mckinsey-five-layer-ai-measurement-framework]]) supplies the missing mechanism, and MIT NANDA's 2025 dataset ([[mit-nanda-state-of-ai-business-2025]]) provides the causal-direction evidence: *"Organizations with systematic monitoring report significantly better outcomes than those with ad-hoc review processes."*

The five layers — technical telemetry, operational KPIs, business KPIs, financial impact, strategic outcomes — are distinct stakeholder views: ML engineers measure layer 1, function leads measure layer 2, the CFO measures layer 4, the CEO measures layer 5. Firms that build all five before deploy can localise the failure mode when the J-curve does not exit; firms that build none can only see the bill at the end of the quarter and abandon. The 42% abandonment rate in 2025 (up from 17% in 2024) is the visible tip of the population that never built the layers.

This reframes [[foundational-enablers]]: the WEF six-enabler list (ecosystem, trust, self-governance, talent, cybersecurity, digital core) is operationally six items of equal weight, but layered measurement maturity is the prerequisite that gates the other six. Without it, the other enablers cannot be diagnosed when they fail.

## Evidence

- MIT NANDA 2025: vendor solutions succeed ~67% of the time vs ~33% for internal builds, and successful deployments allocate 50–70% of timeline and budget to data readiness ([[mit-nanda-state-of-ai-business-2025]]).
- McKinsey: a deployment is *scaled* when AI shifts from initiative to business-as-usual with sustained adoption and structurally improved operational KPIs ([[mckinsey-five-layer-ai-measurement-framework]]).
- Polimi 2025: only 54% of large Italian GenAI-using firms attempt to measure benefits ([[osservatorio-polimi-ai-italia-2025]]).

## Tensions

If measurement is causally upstream, then the managerial reading of [[scaling-gap]] is right *in direction* (the gap is closeable) but wrong on *instrument* (it is closed by measurement layers, not by general "enabler maturity"). The bear reading is right *in scale* (most deployments fail) but wrong on *cause* (they fail for absence of instrumentation, not absence of value). The middle-dies reading collapses into [[doubly-squeezed-middle]].

## Open questions

- Is the causal direction reversible? Can firms install layered measurement *after* a failed pilot and recover, or is the cost of retrofitting structurally prohibitive?
- Where on the [[oecd-sme-adopter-taxonomy]] quadrant does measurement maturity start to differentiate outcomes — Novice, Optimiser, or only Explorer / Champion?

## Related

- [[scaling-gap]] — the artefact this concept supplies a mechanism for.
- [[foundational-enablers]] — the framework this concept reorders.
- [[doubly-squeezed-middle]] — sibling concept on the middle-layer manifestation.
- [[ml-monitoring-quality-cycle]] — engineering-side vocabulary alongside McKinsey's management-side view.
- [[mit-nanda-state-of-ai-business-2025]] — primary empirical anchor.
- [[mckinsey-five-layer-ai-measurement-framework]] — operational framework.

---
title: The Doubly Squeezed Middle
status: draft
tags:
  - concept
  - u-curve
  - middle-layer
  - measurement
  - moat
last-updated: 2026-05-27
contributors: EnomisExcell
---

# The Doubly Squeezed Middle

The middle of [[H2_u-curve-of-value]] is compressed not only by commoditisation from above and below, but by a second structural force the wiki has not named: **the absence of built-in measurement infrastructure**. Firms in the squeezed middle die twice — once because their margins are eaten by the commoditising frontier and substrate, once because they ship without the telemetry that the top-of-U platforms get as a by-product of owning distribution.

## What it is

The current wiki framing of the middle ([[H2_u-curve-of-value]] §"Why this might be wrong", [[middle-layer-defensibility]]) treats the middle as compressed primarily by margin dynamics: frontier labs commoditise capability above, hyperscalers commoditise compute below, and generic wrappers between them cannot defend a position. This is correct but incomplete.

The MIT NANDA 2025 dataset adds a second mechanism. Top-of-U platforms (Cursor, Windsurf, Perplexity, vertical orchestrators) own the direct user relationship, and therefore accumulate continuous, structured behavioural telemetry — retention dashboards, engagement metrics, A/B substrate, churn signals — *as a by-product* of the [[distribution-moat]] they hold. Middle-layer firms do not own the user relationship; they do not get the telemetry as a by-product; they would have to build instrumentation as a deliberate, costly investment under cash pressure. Most do not. Without telemetry, the firm cannot diagnose decay or iterate against retention, and slides toward the 95% pilot-failure population [[mit-nanda-state-of-ai-business-2025]] documents.

The result is structural: the [[middle-layer-defensibility]] argument that sophisticated orchestrators (LangGraph) can survive holds *because LangGraph has observability built in*, not because graph-based orchestration is inherently defensible. Observability is the load-bearing variable; orchestration is the surface.

## Evidence

- MIT NANDA: organisations with systematic monitoring report significantly better outcomes than those with ad-hoc review ([[mit-nanda-state-of-ai-business-2025]]).
- [[where-value-lands-2026]] explicitly classifies LangGraph as "enterprise infrastructure" because of HITL, time-travel debugging, and observability — not because of orchestration logic alone.
- [[scaling-gap]] (74% / 16%) is the empirical artefact: firms that cannot scale cannot measure decay.

## Tensions

Complicates the strong form of [[middle-layer-defensibility]] without contradicting it: the page's empirical anchors (Cursor, LangGraph) remain valid, but the structural reason becomes telemetry rather than orchestration sophistication. If true, the prescription for any middle-layer entrant is *build observability before features* — a different commercial discipline than the wiki currently implies.

## Open questions

- Can a middle-layer firm bolt on measurement after the fact and survive, or is it categorically too late once the firm has shipped without it?
- Does the same "doubly squeezed" pattern recur in non-software verticals where [[vertical-ai-orchestration]] is the middle?

## Related

- [[H2_u-curve-of-value]] — the U this sharpens.
- [[middle-layer-defensibility]] — the page this concept complements.
- [[distribution-moat]] — the mechanism by which top-of-U firms acquire telemetry as by-product.
- [[scaling-gap]] — empirical artefact of measurement absence at scale.
- [[mit-nanda-state-of-ai-business-2025]] — primary empirical anchor.
- [[ml-monitoring-quality-cycle]] — the operational vocabulary of what the middle fails to build.

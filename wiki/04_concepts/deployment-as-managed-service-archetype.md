---
title: Deployment-as-Managed-Service — The Fifth Weber Archetype
status: draft
tags:
  - concept
  - weber
  - archetype
  - middle-layer
  - managed-service
last-updated: 2026-05-27
contributors: EnomisExcell
---

# Deployment-as-Managed-Service — The Fifth Weber Archetype

[[ai-development-facilitator]] (Weber Pattern 2) is the squeezed middle: SDKs, APIs, no-code workbenches sold to other firms that build AI. MIT NANDA's 2025 dataset documents that **vendor solutions succeed ~67% of the time versus ~33% for internal builds**. The two-to-one success gap creates a sub-archetype Weber's 2021 taxonomy does not see: a firm that does not sell tools *to* builders, but sells finished deployments *to* buyers. This is the structural shape the wiki's open-question file ([[05_open-questions]] §"Business archetype taxonomy") has been pointing toward as a candidate fifth archetype but has not specified.

## What it is

Weber's Pattern 2 dies because the population of builders it serves fails 2:1 against the population of buyers who buy completed solutions. The economic logic flips at the boundary. A firm that re-bundles its SDK offering as a *managed deployment service* — same engineering substrate, but delivered as a working AI system integrated into the buyer's workflow with measurement and SLA — recaptures the surplus that the squeeze of [[H2_u-curve-of-value]] is otherwise extracting.

The structural marker that distinguishes the fifth archetype from Pattern 2 is **who absorbs the integration risk**. Pattern 2 sells capability and externalises integration to the buyer (who then fails 2 of 3 times). The fifth archetype sells integration and internalises it. The buyer pays a higher per-unit price than for an SDK and a lower aggregate risk-adjusted price than for a do-it-yourself build. The seller earns higher per-engagement margin than an SDK vendor and carries delivery risk that an SDK vendor escapes.

The fifth archetype is operationally close to a vertical [[vertical-ai-orchestration]] for industrial verticals, but the generalisation is not limited to industry — finance shared services, legal contract review, HR talent acquisition, customer success, all sit naturally inside the fifth archetype when sold as managed deployment rather than as tooling. The contributor's [[ey-fpa-ai-transformation-2025]] stub anchors the FP&A version of this; the [[mit-nanda-state-of-ai-business-2025]] vendor-vs-internal split is the cross-functional empirical anchor.

## Evidence

- MIT NANDA: vendor solutions outperform internal builds 67% vs 33% ([[mit-nanda-state-of-ai-business-2025]]).
- The "agentic-workflow fifth archetype" candidate flagged in [[weber-taxonomy-2026-gaps]] is the structural cousin of this concept; managed-service is the GTM-motion specification of that candidate.
- EY FP&A practitioner data on bimodal outcomes is consistent with the prediction that managed deployments outperform internal builds at the functional level ([[ey-fpa-ai-transformation-2025]]).

## Tensions

Does not contradict [[ai-development-facilitator]] dying — it confirms it, then specifies the survivor sub-pattern. Where the wiki currently allows two survival modes for Pattern 2 (agent frameworks and [[rl-apis]]), this concept adds a third: managed deployment as a service. The three survivor modes are not mutually exclusive — a vendor can offer SDKs, RL APIs, and managed deployments concurrently — but they are commercially distinct and capture surplus at different scales.

## Open questions

- Is the fifth archetype durable through frontier-lab consolidation, or does a hyperscaler bundling managed AI deployment (Microsoft, Google, AWS managed AI services) compress it from above the way Pattern 2 was compressed?
- How does the fifth archetype interact with [[H4_rl-specialization-value-pocket]] — is RL-fine-tuned managed deployment a sub-case, or a parallel archetype?

## Related

- [[ai-development-facilitator]] — Weber Pattern 2 the fifth archetype emerges from.
- [[ai-startup-business-archetypes-weber]] — the parent taxonomy.
- [[weber-taxonomy-2026-gaps]] — the page this concept partially closes.
- [[H2_u-curve-of-value]] — managed-service as a top-of-U position the SDK form could not reach.
- [[middle-layer-defensibility]] — the structural argument this concept operationalises.
- [[vertical-ai-orchestration]] — industrial parallel of the same shape.
- [[mit-nanda-state-of-ai-business-2025]] — primary empirical anchor.

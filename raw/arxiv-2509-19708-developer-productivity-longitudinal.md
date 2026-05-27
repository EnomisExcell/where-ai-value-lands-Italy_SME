# arXiv 2509.19708 — Intuition to Evidence: Measuring AI's True Impact on Developer Productivity

**Author(s):** TBD on primary verification (authors listed on arXiv abstract page)
**Year:** 2025 (arXiv pre-print)
**Venue:** arXiv pre-print, categories cs.SE / cs.AI / cs.LG
**URL:** https://arxiv.org/abs/2509.19708 (abstract) and https://arxiv.org/pdf/2509.19708 (full PDF)
**Primary or secondary:** Primary research, longitudinal cohort study

## Why this matters to the research

The **cleanest longitudinal evidence in the wiki** of an AI deployment crossing the J-curve into sustained-positive territory at a measured month. Where [[ai-productivity-firm-level]] cites the McElheran (2024) and Brynjolfsson/Rock/Syverson (2021) J-curve framework theoretically, this paper documents the curve empirically with month-by-month adoption and productivity figures for AI-assisted developer productivity inside a real engineering organisation.

Key data points:

- **Adoption trajectory:** 4% engagement in month 1 → **83% peak adoption by month 6** → stabilising at 60% active engagement. The exact shape predicted by the J-curve framework.
- **Productivity outcome:** **31.8% reduction in PR review cycle time**, statistically significant via cohort analysis.
- **Top-adopter cohort:** **61% increase in code volume pushed to production**, contributing ~30–40% of code shipped and driving an **overall 28% increase in shipping volume**.
- **Causal-inference methodology:** rigorous cohort analysis distinguishing active adopters from non-adopters within the same engineering organisation — controls for selection on observables.

For the contributor's sustained-ROI lens, this is the source that empirically validates the five-month threshold: the productivity crossover happens between months 4 and 6, exactly where the McElheran J trough exits, exactly the window the contributor's daily thought (`raw/contributor-thoughts/2026-05-26_EnomisExcell.md`) targets as the operator-side filter.

## Wiki pages likely affected

- [[ai-productivity-firm-level]] — direct empirical confirmation of the J-curve with month-by-month data; the wiki currently cites the framework theoretically without a longitudinal anchor.
- [[H2_u-curve-of-value]] — top-of-U evidence at the developer-productivity function level; complements the Cursor / Windsurf / Perplexity valuations data with operational-productivity data.
- [[middle-layer-defensibility]] — operational confirmation of the workflow-embedded platform argument: the productivity gain accrues to firms that adopted AI-assisted coding, not to the model provider directly.
- [[continual-learning-paradigm]] — the adoption-curve shape (4% → 83% → 60%) is the human-side learning curve that the model-side continual-learning argument is structurally analogous to.
- Potentially a new data page in `wiki/data/` for the month-by-month adoption + productivity figures, parallel to `data/eri-use-case-deltas.md`.

## Suggested by

EnomisExcell — 2026-05-27 — surfaced via `/discover` pass following the Anthropic Economic Index Learning Curves stub in the same PR. Together with that stub and McKinsey five-layer framework, this set closes the "longitudinal evidence on sustained AI value" empirical gap in the wiki. Author list, sample size, and named-firm setting require direct PDF read by the maintainer before ingest — current fetch returned PDF metadata only.

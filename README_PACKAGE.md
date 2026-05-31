# Agentic AI in SE website package (revised)

This package contains a revised version of the supporting website for the IEEE TSE manuscript "Agentic AI in Software Engineering: Tools or Team Members?".

## Main changes in this revision

- The site now clearly separates:
  1. description of the work and construction process,
  2. final outcomes of the work, especially the final taxonomy and risk-benefit analysis,
  3. additional construction and validation material, including the extended McLuhan Tetrad, scoping literature files, and expert validation material.
- The site describes the 11-paper scoping corpus from the first iteration and distinguishes it from the broader second-iteration source base used for the Tetrad construction.
- The extended Tetrad page explains that the Tetrad and risk-benefit synthesis draw on broader literature surveyed during the second iteration.
- The evidence-map and trust-calibration pages were removed to avoid adding noise or suggesting independent results not present in the paper.
- The manuscript PDF is not included.

## Entry point

Open `index.html` in a browser.

## Folder structure

- `index.html`: overview and explanation of the site structure.
- `method.html`: construction of the work and three Design Science iterations.
- `taxonomy.html`: final taxonomy and boundary-case rationale.
- `extended-tetrad.html`: detailed McLuhan Tetrad construction material plus first-iteration scoping review files.
- `validation.html`: expert elicitation and taxonomy refinement.
- `research-agenda.html`: open questions and testable research questions.
- `materials.html`: downloadable material.
- `data/`: core replication files.
- `web-materials/`: structured online-appendix data.

Update: the final taxonomy page now includes the risk-benefit analysis, and `risk_benefit_analysis.csv` is included in both `web-materials/` and `data/web-materials/`.

Tetrad traceability update:
- web-materials/tetrad_source_traceability.csv
- web-materials/tetrad_source_summary.json
These quantify and document the source base used in the extended McLuhan Tetrad construction.

DOI: https://doi.org/10.5281/zenodo.19686209

# Bounded Criticality in Power Systems — 4-in-1 Reproducibility Package

This is a compact, paper-grade reproducibility package for the bounded-criticality study on IEEE-39, IEEE-118, IEEE-300, and IEEE-2383 benchmark systems.

## Included

* `data/real\_data.csv`
* `scripts/generate\_figures.py`
* `docs/figure\_mapping.md`
* `CITATION.cff`
* `.zenodo.json`

## Reproduce figures

```bash
python run\_all.py
```

Outputs:

* `paper/figures/fig1\_ieee118\_submission.png`
* `paper/figures/fig3\_ieee300\_submission.png`
* `paper/figures/fig4\_width\_empirical\_submission.png`
* `paper/figures/fig5\_peak\_susceptibility\_submission.png`

## Framework Relation

This repository is part of the bounded-criticality research stack and should be read alongside the UVP framework repository:

https://github.com/Z139-Lab/uvp-v2-framework

## Reproducibility

Install dependencies and run the included scripts to regenerate figures and tables from the packaged data.

## Framework Relation



This repository should be read alongside the UVP framework repository:



https://github.com/Z139-Lab/uvp-v2-framework



The UVP framework is used for criticality-oriented analysis and reproducibility support across the broader bounded-criticality research stack.


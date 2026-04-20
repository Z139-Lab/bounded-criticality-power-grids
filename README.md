# Bounded Criticality in Power Systems — 4-in-1 Reproducibility Package

This is a compact, paper-grade reproducibility package for the bounded-criticality study on IEEE-39, IEEE-118, IEEE-300, and IEEE-2383 benchmark systems.

## Included
- `data/real_data.csv`
- `scripts/generate_figures.py`
- `docs/figure_mapping.md`
- `CITATION.cff`
- `.zenodo.json`

## Reproduce figures
```bash
python run_all.py
```

Outputs:
- `paper/figures/fig1_ieee118_submission.png`
- `paper/figures/fig3_ieee300_submission.png`
- `paper/figures/fig4_width_empirical_submission.png`
- `paper/figures/fig5_peak_susceptibility_submission.png`

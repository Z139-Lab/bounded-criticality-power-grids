<<<<<<< HEAD
DOI: https://doi.org/10.5281/zenodo.19686209

# \# Bounded Criticality in Power Systems

# 

# A reproducible research repository for finite-width critical bands, suppression of cascading failure, and scale-dependent transition structure across IEEE-39, IEEE-118, IEEE-300, and IEEE-2383 benchmark systems.

# 

# Live research portal:  

# https://z139-lab.github.io/bounded-criticality-portal/

# 

# \---

# 

# \## Overview

# 

# This repository studies \*\*bounded criticality\*\* in realistic power-grid systems under stochastic loading.

# 

# Unlike classical sharp critical-point pictures, the results here support a \*\*finite-width critical regime\*\*:

# a bounded transition region in which collapse probability changes continuously and control effectiveness becomes maximal.

# 

# The repository integrates evidence across four benchmark systems:

# 

# \- \*\*IEEE-39\*\* — proof-of-concept suppression regime

# \- \*\*IEEE-118\*\* — emergence of a finite-width critical band

# \- \*\*IEEE-300\*\* — structured critical regime with stronger peak suppression

# \- \*\*IEEE-2383\*\* — near-discontinuous critical edge

# 

# \---

# 

# \## Key Findings

# 

# \- \*\*Finite-width critical band\*\* is observed in realistic power grids rather than a single sharp threshold.

# \- \*\*IEEE-118\*\* shows a critical band around \*\*30–50 MW\*\*, with memory-dependent suppression near \*\*40 MW\*\*.

# \- \*\*IEEE-300\*\* shows stronger suppression, with peak \*\*Δ ≈ 0.332\*\* near \*\*126 MW\*\*.

# \- \*\*IEEE-2383\*\* exhibits a near-discontinuous edge, with a narrow transition around \*\*29.05–29.10 MW\*\* and extreme suppression.

# \- \*\*Peak susceptibility does not diverge\*\*, supporting a bounded rather than classically divergent critical regime.

# \- The empirical width of the critical band decreases with system size, but \*\*no scaling law is claimed\*\* from the limited width points.

# 

# \---

# 

# \## Research Object

# 

# \- \*\*Domain:\*\* Power systems / cascading failure

# \- \*\*Phenomenon:\*\* Bounded criticality

# \- \*\*Systems:\*\* IEEE-39, IEEE-118, IEEE-300, IEEE-2383

# \- \*\*Mechanism:\*\* Logistic softening with memory feedback

# \- \*\*Observables:\*\* Collapse probability, suppression Δ, empirical band width, peak susceptibility

# \- \*\*Goal:\*\* Identify and compare bounded transition structure across system size

# 

# \---

# 

# \## Reproducibility

# 

# Clone the repository:

# 

# ```bash

# git clone https://github.com/Z139-Lab/bounded-criticality-power-grids.git

# cd bounded-criticality-power-grids

# 

# Install dependencies:

# 

# pip install -r requirements.txt

# 

# Generate the main paper figures:

# 

# python run\_all.py

# 

# Main compact dataset:

# 

# data/real\_data.csv

# 

# Figure-to-data mapping:

# 

# docs/figure\_mapping.md

# Figures

# Figure 1 — IEEE-118 critical band + memory ablation

# 

# Generated from IEEE-118 rows in data/real\_data.csv.

# 

# Figure 3 — IEEE-300 finite-width band

# 

# Shows baseline, controlled collapse probability, and suppression Δ across the critical regime.

# 

# Figure 4 — Empirical critical band width

# 

# Uses the compact width points for IEEE-118, IEEE-300, and IEEE-2383.

# No power-law fit is used.

# 

# Figure 5 — Peak susceptibility

# 

# Shows non-divergent peak susceptibility across system size.

# 

# Repository Structure

# data/                    compact paper dataset

# docs/                    figure mapping and notes

# paper/                   manuscript and generated figures

# scripts/                 figure generation scripts

# case\_studies/ieee39/     proof-of-concept case

# Related Repositories

# Research portal: https://github.com/Z139-Lab/bounded-criticality-portal

# IEEE-2383 extreme-case repo: https://github.com/Z139-Lab/ieee-2383-critical-edge

# UVP v2 framework: https://github.com/Z139-Lab/uvp-v2-framework

# Keywords

# 

# bounded criticality, finite-width critical band, cascading failure, power grid stability, memory feedback, IEEE benchmark systems, complex systems, critical phenomena, reproducible research

# 

# Citation

# 

# Please use the repository citation metadata in CITATION.cff.

# 

# Author

# 

# Juan Adam

# Independent Research


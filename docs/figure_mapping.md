# Figure Mapping

## Source file
- `data/real_data.csv`

## Figure 1 — IEEE-118 critical band + memory ablation
Uses rows where `type == "ieee118"`:
- `(ieee118, 30, 0.067, 0.067)`
- `(ieee118, 31, 0.133, 0.133)`
- `(ieee118, 32, 0.167, 0.167)`
- `(ieee118, 39, 0.570, 0.476)`
- `(ieee118, 40, 0.588, 0.491)`

Right-panel bars:
- Baseline = `0.588` from `(ieee118, 40, 0.588, 0.491)`
- With memory = `0.491` from `(ieee118, 40, 0.588, 0.491)`
- No memory = fixed paper ablation value at 40 MW = `0.588`

## Figure 3 — IEEE-300 finite-width band
Uses rows where `type == "ieee300"`:
- 115 MW → baseline `0.476`, controlled `0.296`, Δ `0.180`
- 120 MW → baseline `0.552`, controlled `0.296`, Δ `0.256`
- 122 MW → baseline `0.580`, controlled `0.296`, Δ `0.284`
- 124 MW → baseline `0.608`, controlled `0.296`, Δ `0.312`
- 125 MW → baseline `0.620`, controlled `0.296`, Δ `0.324`
- 126 MW → baseline `0.628`, controlled `0.296`, Δ `0.332`
- 128 MW → baseline `0.636`, controlled `0.328`, Δ `0.308`
- 130 MW → baseline `0.640`, controlled `0.484`, Δ `0.156`

Peak suppression:
- `126 MW`, `Δ = 0.332`

## Figure 4 — Empirical critical band width vs system size
Uses rows where `type == "bandwidth"`:
- `(bandwidth, 118, 20, 0)`
- `(bandwidth, 300, 15, 0)`
- `(bandwidth, 2383, 0.05, 0)`

Interpretation:
- x-axis = system size from `load`
- y-axis = empirical band width from `baseline`
- no power-law fit in this package

## Figure 5 — Peak susceptibility vs system size
Uses rows where `type == "chi"`:
- `(chi, 118, 0.42, 0)`
- `(chi, 300, 0.41, 0)`
- `(chi, 2383, 0.34, 0)`

Interpretation:
- x-axis = system size from `load`
- y-axis = `chi_peak` from `baseline`

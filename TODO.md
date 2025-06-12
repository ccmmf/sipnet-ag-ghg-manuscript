# TODO: SIPNET Sensitivity and Uncertainty Analysis

## Analyses

- [ ] Further prior constraint
  - [ ] Meta-analysis
  - [ ] Expert knowledge
- [ ] Calibration

- [ ] Extend parameter perturbation and sensitivity analysis to include additional PFTs:
  - Vines
  - Vegetables
  - Grains
  - Forage crops

- [ ] Add and analyze greenhouse gas outputs:
  - Methane (CH₄)
  - Nitrous oxide (N₂O)

- [ ] Compare sensitivity results across sites and PFTs to identify patterns and anomalies
- [ ] Identify priority traits for further prior constraint or calibration:
  - Photosynthetic capacity (Amax, AmaxFrac)
  - Leaf economic traits (SLA, leaf growth)
  - Turnover rates (root, leaf, wood)
  - Allocation fractions

## Visualizations

- [ ] Heatmaps of elasticity and variance contributions by parameter and output
- [ ] Interactive figures (e.g., Shiny or Quarto) for exploring 
  - [ ] sensitivity plots (parameter-output relationships)
  - [ ] prior distributions
- [ ] Perhaps a bump plot to visualize rank [CV, elasticity, variance contribution] like https://github.com/cct-datascience/state_organic_ag/blob/48a60e946ef168c96b27d67850b01c974a13f156/code/practices_challenges.R#L84? https://raw.githubusercontent.com/cct-datascience/state_organic_ag/refs/heads/main/figures/Fig4_practices_dotted.png? At least to aid in interpretation.

## Writing

- [ ] model description and parameter definitions (highlight parameters in analysis + include sipnet docs as appendix?)
- [ ] Determine manuscript scope (and other related manuscripts)
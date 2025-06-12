## Sensitivity and Uncertainty [Draft]

These patterns provide a foundation for planned extensions:
- New PFTs: vines, vegetables, grains, forage systems.
- New outputs: CH₄ and N2O fluxes.
- Sensitivity / uncertainty w.r.t. initial conditions, drivers [met, ag management].

Results presented here are preliminary and will be updated with new sites and outputs. Core sensitivity patterns are expected to remain robust.


### Methods 
We performed a univariate sensitivity and variance decomposition analysis of 28 SIPNET parameters across _n_[TK] sites and _m_[TK] plant functional types (PFTs): annual herbaceous (grass) and temperate deciduous (orchard analog). 
The focus was on five model outputs including two carbon pools: Aboveground Biomass(AGB) and Soil Carbon (SOC) and three fluxes including plant growth (NPP) and GHG emissions CH4 and N2O. 
Each parameter was perturbed across values corresponding to the +/-0,1,2,3 sd quantiles of a standard-normal distribution.  and model output sensitivity was characterized using:

- Coefficient of Variation (CV): SD normalized by median to indicate prior uncertainty in each parameter.
- Elasticity: $\frac{\partial y}{\partial x} \cdot \frac{x}{y} $ is normalized sensitivity of model output to parameter value at the parameter median.
- Variance Contribution: Contribution of parameter to output uncertainty, combining prior uncertainty and elasticity.

### Patterns in Parameter Influence

#### Aboveground Biomass (AGB)

AGB was most sensitive to photosynthetic and allocation traits. Specifically, the parameters with the highest elasticities included:
- Controls on photosynthesis including Maximum Photosynthetic Rate (Amax), Optimal Temperature for Photosynthesis (psnTOpt), and Minimum Temperature for Photosynthesis (Vmax_min_temp), leaf_respiration_rate.
- Wood Allocation Fraction, Leaf Growth, and Specific Leaf Area (SLA) were key drivers of variance.
Differences between grass and orchard systems reflect differences in functional traits: ... photosynthetic parameters while woody plants  structural allocation.
Differences across sites ... 

#### Net Primary Productivity (NPP)

NPP was similarly governed by photosynthetic traits, with high sensitivity to:
- Maximum Photosynthetic Rate, Amax Fraction, Leaf Turnover Rate, and Water Use Efficiency Constant.
- Elasticities were strongest in grasses, suggesting sharper physiological thresholds.
Variance was also driven by SLA and Leaf Growth, linking productivity to leaf economics.

Differences among PFTs: [TK]
Differences across sites: [TK] 

#### Total Soil Carbon (SOC)

SOC responses were primarily influenced by turnover and litter input parameters:
- Key contributors included Root Turnover Rate, Leaf Turnover Rate, Wood Turnover Rate, and Growth Respiration Fraction.
- Variance contributions were more diffuse, indicating long-term integration across multiple processes.
Differences between PFTs suggest ...[TK]
Differences across sites: [TK]


### Discussion

- Qle and soil moisture, while not the focus, exhibited sensitivity patterns consistent with carbon-water tradeoffs (e.g., WUE parameters influencing both NPP and Qle).
- Model sensitivity in grasses was sharper and more site-variable, while orchard systems showed broader parameter contributions.
- Among parameters that contributed most to output uncertainty:
  - Poorly constrained parameters (high CV and low elasticity) (e.g., belowground respiration rates) may reflect either model structural insensitivity 
    - [e.g. how does this compare to what has been observed] 
    - or underrepresented processes.
    - These are targets for constraint on priors or inverse parameter estimation (calibration)
  - Parameters with low CV and high elasticity: photosynthetic traits; reflect well constrained parameters that exert strong physiological control over ecosystem functioning.
  - Parameters with high CV but low elasticity (e.g., belowground respiration rates) may reflect structural insensitivity or underrepresented processes.


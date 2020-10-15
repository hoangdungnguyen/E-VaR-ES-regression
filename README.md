# Learning conditional expectation, value-at-risk, and expected shortfall
Authors: Hoang-Dung Nguyen under supervision of Prof. Stéphane Crépey with crucial support from Marc Chataigner and Bouazza Saadeddine.

## Description
with the motive of analysing XVA metrics (i.e. counterparty risk for banks), we state the two main objectives of this work: 
- We look for stable and accurate conditional VaR and ES estimation
- Given that these risk measures must be reevaluated at each valuation steps in XVA framework, it is essential to accelerate the computational paradigm of these metrics (as well as of conditional expectation, corresponding to future prices in the financial application, in the first place).


## Git repository structure
- File `report.pdf` is our completed report
	- `ES_from_VaR_NN.ipynb` is a new well-working methodology (Thank for Bouazza's idea) which is the fastest and the most accurate way to learn VaR and ES. The efficiency of this methodology can be explained by our upper bound of ES estimates developed in our report, but the numerical result is not yet added in the report.
- Folder `Report code` contains documented jupyter notebooks serving two simulation problems in the report: Pricing problem (i.e. Conditional expectation) and VaR ES case study (i.e. Conditional VaR and ES)
- Folder `Draft` contains some codes, algorithms which did not work yet, but may be useful for future work (e.g. Quantile regression via interior point, Jacobian, Hessian function implemented on PyTorch, etc.). They are not yet documented.
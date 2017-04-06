# Systemic Risk

I created this project in 2015 for my Master of Science thesis at Università Cattolica del Sacro Cuore (Milan, Italy).
It can calculate and analyse the following systemic risk indicators:
* CoVaR (Conditional Value-at-Risk) proposed by Adrian & Brunnermeier (2009);
* ΔCoVaR (Delta Conditional Value-at-Risk) proposed by Adrian & Brunnermeier (2009);
* MES (Marginal Expected Shortfall) proposed by Acharya et al. (2010);
* Network Measures proposed by Billio et al. (2011);
* SRISK (Conditional Capital Shortfall Index) proposed by Brownlees & Engle (2014).

## Notes

The dataset file must be structured like the one included in the root directory of this project (`dataset.xlsx`). The financial time series must have been previously validated and preprocessed:
* there are enough observations to run consistent calculations;
* - illiquid series with too many zeroes have been discarded;
* - outliers have been detected and removed; % - rows with NaNs have been removed or filled with interpolation;
* - etc...

## Contributions

If you want to start a discussion about the project, just open an issue.
Contributions are more than welcome, fork and create pull requests as needed.

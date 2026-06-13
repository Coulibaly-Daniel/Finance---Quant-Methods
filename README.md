#  Quantitative Finance Models (Python)

## Project Overview

This project includes several quantitative finance models implemented in Python:

- Asset pricing models (CAPM and Fama-French 3-factor model)
- Derivatives pricing
   . using Monte Carlo simulation for implementing TARN
   . for graphically representation of Volatility surface

The objective is to analyze financial data and implement numerical methods used in quantitative finance.


## Asset Pricing

- CAPM regression analysis
- Fama-French 3-factor model
- Statistical interpretation of factors (beta, alpha, R²)


##  Derivatives Pricing

- Monte Carlo simulation of asset paths
- Pricing of a Target Redemption Note (TARN)
- Path-dependent payoff modeling
- implicite volatility surface

## Installation

pip install -r requirements.txt

##  Tools & Libraries

- Python
- NumPy
- Pandas
- Statsmodels
- Matplotlib
- mpl_toolkits


##  Project Structure

- `asset_pricing/` → CAPM & Fama-French analysis
- `derivatives/` → TARN Monte Carlo pricing,
                 → Implicitevolatility surface

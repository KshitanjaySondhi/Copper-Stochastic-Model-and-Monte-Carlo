# Copper-Stochastic-Model-and-Monte-Carlo
Stochastic pricing framework for copper using Ornstein-Uhlenbeck mean-reversion and Markov regime-switching, with sovereign debt implications for African copper producers.
Mean Reversion or Structural Break? A Framework for Copper in the Age of Electrification
Author: Kshitanjay Sondhi
,Affiliation: ICRIER (Indian Council for Research on International Economic Relations), ex-S&P Global, London School of Economics and Political Science
,Date: April 2026
,SSRN: [link when uploaded]
,Contact: kshitanjaysondhi@gmail.com


Overview: 
This repository contains the full replication code for the paper "Mean Reversion or Structural Break? A Stochastic Framework for Copper in the Age of Electrification."
The analysis builds a stochastic pricing framework for LME copper using 34 years of monthly price data (1992–2026). It tests formally for a structural break driven by the energy transition, estimates a Hamilton (1989) Markov Regime-Switching model to identify latent demand regimes, and runs Monte Carlo simulations of copper price paths to 2036 under three scenarios. The final section links the price scenarios to Zambia's debt-to-GDP trajectory using a calibrated debt dynamics model.
Key finding: A statistically confirmed structural break at June 2020 (Chow F=3.34, p=0.036) shifted the long-run mean to which copper prices revert by 71.7% — from $5,888/t to $10,112/t. Standard models calibrated on pre-2020 data systematically underestimate copper prices. The Bear scenario median price in 2036 is $10,093/t — 50% above the pre-transition historical mean.

copper-stochastic-pricing/
│
├── CopperPrices.ipynb          # Main notebook — full analysis, all figures
├── Copper_Prices.xlsx          # LME copper monthly data 1992–2026 (World Bank)
├── requirements.txt            # Python dependencies
├── README.md                   # This file
│
└── output/
    ├── chart_00_raw_prices.png
    ├── chart_01_ou_model.png
    ├── chart_02_regime.png
    ├── chart_03_monte_carlo.png
    ├── chart_04_production.png
    └── chart_05_zambia.png

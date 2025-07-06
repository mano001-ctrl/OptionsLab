# OptionsLab: Interactive Options Analytics and Visualizations

**OptionsLab** is a curated collection of Jupyter Notebooks aimed at exploring option pricing models, payoff diagrams, volatility analysis, and advanced strategies. Whether you're learning the fundamentals or building quantitative trading tools, OptionsLab offers hands-on experiments and visual guides.

## Repository Structure

```
OptionsLab/
├── Pricing_Models/                          # Analytical pricing and risk frameworks
│   ├── Black_Scholes_and_Put_Call_Parity.ipynb
│   ├── Binomial_Option_Pricing_Model.ipynb
│   └── Using_the_ARCH_Model_to_Predict_Volatility_A_Comprehensive_Guide.ipynb
│
├── Payoff_Diagrams/                          # Profit & loss visualizations at expiration
│   ├── Bull_Call_Spread_Payoff_Diagram.ipynb
│   ├── Butterfly_Spread_Payoff_Diagram.ipynb
│   ├── Covered_Calls_with_Greeks.ipynb
│   ├── Iron_Condor_Strategy.ipynb
│   ├── Long_Strangle_Payoff_Diagram.ipynb
│   └── ... (other payoff notebooks)
│
├── Volatility_Analysis/                      # Term structures, heatmaps, and models
│   ├── Implied_Volatility_Term_Structure.ipynb
│   ├── Implied_Volatility_vs_Historical_Volatility.ipynb
│   ├── Skew_Index_Basic_Visualization_and_Explaination.ipynb
│   └── ... (other vol analysis notebooks)
│
├── Strategy_Backtests/                       # Backtests and Monte Carlo experiments
│   ├── Monte_Carlo_Basics.ipynb
│   ├── Straddle_Strategy_Backtest.ipynb
│   ├── Volatility_Arbitrage_A_Comprehensive_Overview.ipynb
│   └── Pairs_Trading_with_Options.ipynb
│
├── Risk_Metrics_Heatmaps/                    # Risk and sector analytics
│   ├── Risk_Return_Sharpe_Ratio_Drawdown_Heatmap_for_S&P_500_Sectors_(1_Year).ipynb
│   ├── Sector_Correlation_Heatmap_(S&P_500).ipynb
│   └── Sector_Performance_Calendar_Heatmap_(Real_Data).ipynb
│
├── Data/                                     # Sample CSV datasets
│   └── put_call_parity_results.csv
│
├── README.md
└── requirements.txt                          # Python dependencies
```

> **Note:** A few notebook filenames are abbreviated in this listing for brevity—browse the folders for the full set.

## Getting Started

### Prerequisites

* Python 3.7+
* Jupyter Notebook or JupyterLab
* Install required packages listed in `requirements.txt`:

  ```bash
  pip install -r requirements.txt
  ```

### Running the Notebooks

1. Clone the repository:

   ```bash
   git clone https://github.com/mano001-ctrl/OptionsLab.git
   cd OptionsLab
   ```
2. Launch Jupyter:

   ```bash
   jupyter lab   # or jupyter notebook
   ```
3. Navigate the directory tree to open any notebook and run cells interactively.

## Highlights

* **Core Pricing Models:** Black-Scholes, binomial trees, ARCH/GARCH volatility forecasting.
* **Payoff Diagrams:** Visual guides for spreads, straddles, strangles, condors, butterflies.
* **Volatility Term Structures:** Compare implied vs. historical vol, skew, heatmaps of realized vol.
* **Advanced Strategies:** Gamma scalping, volatility arbitrage, pairs trading with options.
* **Risk Analytics:** Sector heatmaps, Sharpe ratio, drawdown visualizations.

## Contributing

Contributions and suggestions are welcome:

* Open issues to propose new notebooks or report bugs.
* Submit pull requests for enhancements, additional models, or strategy implementations.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or feedback, open an issue or reach out to the maintainer on GitHub.

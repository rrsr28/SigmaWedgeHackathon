# SigmaWedgeHackathon

# Algorithmic Trading Strategies with QuantRocket - README

## Overview

This repository contains code and analysis for a project focused on developing and optimizing algorithmic trading strategies using QuantRocket. The project incorporates two main strategies: a Three-State Model based on Transition Probability Matrix (TPM) and a Moving Average (MA) strategy. The strategies are applied to historical price data of a selected US stock, primarily focusing on AAPL.

## Project Structure

The project is organized into several key components:

1. **QuantRocket Setup:**
   - The `quantrocket_setup.ipynb` notebook activates the QuantRocket license key and creates a US stock database ("usstock-free-1d") for daily bars.

2. **Universe Creation:**
   - The `universe_creation.ipynb` notebook establishes two universes: "usstock-free" based on security identifiers (sids) and "usstock-free-active" by filtering out delisted securities.

3. **AAPL Historical Data:**
   - The `aapl_historical_data.ipynb` notebook collects historical price data for AAPL, and the resulting DataFrame is saved to a CSV file ("aapl_history.csv").

4. **Three-State Model:**
   - The `three_state_model.ipynb` notebook implements the Three-State Model, optimizing the portfolio value using the Transition Probability Matrix (TPM).

5. **Moving Average (MA) Strategy:**
   - The `moving_average_strategy.ipynb` notebook applies a Moving Average strategy with a 15-day window, predicting prices and visualizing buy/sell decisions.

6. **Analysis and Reporting:**
   - The `report_generation.ipynb` notebook generates a comprehensive project report, including insights, challenges, and recommendations.

## Usage

1. Ensure QuantRocket is properly installed and configured.
2. Execute the notebooks in the specified order to set up QuantRocket, create universes, collect historical data, and implement trading strategies.
3. Review the generated reports for insights and recommendations.

## Dependencies

- QuantRocket
- pandas
- numpy
- matplotlib
- statsmodels

## Note

This README provides a high-level overview. For detailed explanations, findings, and insights, refer to the individual notebooks in the repository.

**Disclaimer:** This project is for educational and informational purposes only. Algorithmic trading involves risks, and strategies should be thoroughly tested and validated before deployment.

**Author:** [Your Name]

Feel free to contribute, improve, or customize the code based on your requirements. Happy trading!

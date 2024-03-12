# SigmaWedgeHackathon

## Algorithmic Trading Strategies with QuantRocket

## Overview

This repository contains code and analysis for a project focused on developing and optimizing algorithmic trading strategies using QuantRocket. The project incorporates two main strategies: a Three-State Model based on Transition Probability Matrix (TPM) and a Moving Average (MA) strategy. The strategies are applied to historical price data of a selected US stock, primarily focusing on AAPL.

## Project Structure

The project is organized into several key components:

1. **QuantRocket Setup:**
2. **Universe Creation:**
3. **AAPL Historical Data:**
4. **Three-State Model:**
5. **Moving Average (MA) Strategy:**
6. **Analysis and Reporting:**

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

<hr>


# Solution

## Considering return as percentage : (when range is [-0.01, 0.01])
#### Considering Losses :
* Portfolio - 2
* Optimal BuyIndices - [ 78, 92 ]
#### Not Considering Losses :
* Portfolio - 2
* Optimal BuyIndices - [ 78, 92 ]

## Considering return as fraction :  (when range is [-0.01, 0.01])
#### Considering Losses :
* Portfolio - 17
* Optimal BuyIndices - [5, 7, 11, 15, 20, 27, 29, 32, 35, 38, 40, 44, 49, 51, 56, 58, 60, 63, 65, 68, 78, 84, 87, 93, 96, 99, 102, 107, 109, 112, 116, 119, 122, 127, 132, 135, 141, 144, 146, 153, 155, 159, 163, 168, 172, 176, 178, 182, 186, 190, 195, 200, 203, 206, 208, 211, 215, 217, 231, 233, 235, 237, 242]
#### Not Considering Losses :
* Portfolio - 40
* Optimal BuyIndices - [5, 7, 11, 15, 20, 27, 29, 40, 49, 51, 58, 60, 68, 78, 84, 87, 93, 99, 102, 107, 109, 112, 116, 119, 122, 132, 141, 159, 163, 176, 186, 190, 206, 208, 211, 215, 217, 231, 233, 237]

## Considering return as percentage :  (when range is [-0.1, 0.1])
#### Considering Losses :
* Portfolio - 0
* Optimal BuyIndices - []

#### Not Considering Losses :
* Portfolio - 0
* Optimal BuyIndices - []

## Considering return as fraction :  (when range is [-0.1, 0.1])
#### Considering with Losses :
* Portfolio - 5
* Optimal BuyIndices - [7, 11, 71, 78, 81, 86, 92, 95, 102, 115, 132, 152, 197, 202, 221, 226, 239, 244, 247]

#### Considering without Losses :
* Portfolio - 12
* Optimal BuyIndices - [7, 11, 71, 78, 92, 102, 132, 152, 202, 221, 226, 247]


<hr>


## Note

This README provides a high-level overview. For detailed explanations, findings, and insights, refer to the individual notebooks in the repository.

**Disclaimer:** This project is for educational and informational purposes only. Algorithmic trading involves risks, and strategies should be thoroughly tested and validated before deployment.

**Author:** Sanjay Ram R R

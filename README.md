# Stock Valuation Calculator

## Description

This Python program automates the process of valuing a stock based on forecasted dividends and a terminal growth rate. The program queries the user for necessary information such as the stock ticker, forecasted dividends, and growth rates, and then computes the estimated intrinsic value of the stock. It compares this intrinsic value with the current market price to make a buy, sell, or hold recommendation. The program also incorporates appropriate error-handling procedures to ensure accurate inputs.

## Key Features
- **User Input**: Prompts the user for the stock ticker, forecasted dividends, terminal growth rate, and either a custom discount rate or the use of a CAPM model.
- **Intrinsic Value Calculation**: Computes the present value of forecasted dividends and the terminal value to estimate the stock's intrinsic value.
- **Recommendation**: Compares the intrinsic value with the current market price and provides a buy, sell, or hold recommendation.
- **Error Handling**: Ensures valid numeric inputs and appropriate user choices for discount rate options.

## How It Works
1. **User Input**: 
    - Prompts for the stock ticker and current market price.
    - Collects forecasted dividends for the specified number of years.
    - Queries for the terminal growth rate.
    - Offers a choice between entering a custom discount rate or using a CAPM model.
2. **Calculation**: 
    - Computes the present value of each forecasted dividend.
    - Calculates the terminal value based on the last forecasted dividend and terminal growth rate.
    - Sums the present values of the dividends and terminal value to get the intrinsic value.
3. **Output**: 
    - Displays the intrinsic value per share.
    - Compares the intrinsic value with the current market price and gives a buy, sell, or hold recommendation.
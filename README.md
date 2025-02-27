# Algo-Pricing

Stock analysis and Portfolio management system

Overview

This project provides a comprehensive system for analyzing stock data and managing a portfolio of assets. 
It includes functionalities for calculating various stock metrics and performing Monte Carlo simulations.


Features

Stock metrics calculation : Calculate metrics such as Simple Moving Average (SMA), Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD) and more.
Monte Carlo simulation : Predict future stock prices using Monte Carlo simulations.
Portfolio management : Add assets to a portfolio track transactions and calculate the total portfolio value.
Risk metrics : Calculate Value at Risk (VaR) and Conditional Value at Risk (CVaR).
Visualization : Plot stock metrics and simulation results for better insights.


Installation

Clone the repository :
git clone httpsgithubcomyour-usernamyour-repo.git
cd your-repo

Create a virtual environment :
python -m venv venv
source venvbinactivate  On Windows use venvScriptsactivate

Install dependencies :
pip install -r requirements.txt


Usage

Prepare stock data :
Place stock data CSV files in the data/ directory. Ensure the CSV files contain at least "Date" and "Close" columns.

Run the main script :
python main.ipynb

Interact with the system :
Follow the prompts to add stocks to your portfolio buysell assets and view portfolio summaries and metrics


Project structure

notebooks/ : Contains Jupyter Notebooks for detailed analysis and visualizations.
data/ : Store your stock data CSV files here.
README.txt : Project documentation.
requirements.txt : List of Python dependencies.
main.ipynb : Main script to run the portfolio management system.


Copyright

All rights reserved. This project may be used without the written permission of the author. This project may not be copied, modified, or distributed without the written permission of the author.


Contact

For any questions or suggestions feel free to reach out to Alexandre TAMAIN-GLOZ at atamainglozprogmail.com.

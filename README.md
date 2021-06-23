{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# USD/JPY FORECAST CHART ANALYSIS"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Background"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Hedge funds and the financial departments of large companies often deal with foreign currency transactions while doing international business. They are always looking for a better understanding of the future direction and risk of various currencies. They utilize algorithms and other financial forecasting tools to give them a consistent edge in predicting currency movements. In this homework assignment, I tested the Time Series Forecasting and Linear Regression Model to predict future movements in the value of the Japanese yen versus the U.S. dollar."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Time Series Forcasting"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "In this notebook, I uploaded historical Dollar-Yen exchange rate futures data and applied time series analysis and modeling to determine whether there was any predictable behavior. I completed the following tasks:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).\n",
    "- Forecasting Returns using an ARMA Model.\n",
    "- Forecasting the Settle Price using an ARIMA Model.\n",
    "- Forecasting Volatility with GARCH.\n",
    "- Use the results of the time series analysis and modeling to answer the following questions:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The analysis indicated it's risky to buy the yen as the risk is expected to increase."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Linear Regression Forcasting"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "In this notebook, I built a Scikit-Learn linear regression model to predict Yen futures (\"settle\") returns with lagged Yen futures returns and categorical calendar seasonal effects. I completed the following:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)\n",
    "- Fitting a Linear Regression Model.\n",
    "- Making predictions using the testing data.\n",
    "- Out-of-sample performance.\n",
    "- In-sample performance.\n",
    "- Use the results of the linear regression analysis and modeling to answer the following question:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "It indicated the out-of-sample data model performed better compared to in-sample data. The model worked better with data that it has not worked with before."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Conclusions"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Based on the model evaluations, I feel confident in using these models for trading."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}

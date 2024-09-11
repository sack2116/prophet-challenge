# Forecasting with Net Prophet-challenge
Project to as a Growth Analysist try to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock

## Overview

This project involves analyzing and forecasting trends in Google search traffic for a specific company using the Prophet library. The notebook explores how search traffic correlates with key financial events and forecasts future traffic based on historical data.

The task is structured to find patterns, especially during periods of significant corporate events, and to build a time-series forecasting model using Prophet.

### Requirements

- **Prophet:** Time series forecasting library.
- **Pandas:** Data handling and analysis.
- **Matplotlib:** Visualization of time-series data.

### Dataset

The dataset used includes Google search traffic for the company, with hourly data for the year 2020. The project focuses on identifying and predicting unusual traffic patterns during key company events.

### Objectives

1. **Identify Unusual Patterns:**
   - Analyze hourly search traffic for unusual patterns in May 2020.
   - Compare the total search traffic for May against the monthly median across all months.

2. **Forecast Search Traffic:**
   - Create a time-series forecast of Google search traffic using the Prophet library.
   - Analyze the accuracy of the forecast model by comparing it with actual search traffic.

### Returns
    -None
- **Search Traffic Insights:**
  - Identifies whether search traffic spikes during significant corporate events, particularly when financial results are released.

- **Forecast Model:**
  - A Prophet model for time-series forecasting of future search trends based on historical data.

## PseudoCode

### Step 1: Identify Patterns in Search Traffic

1. **Data Preparation:**
   - Load Google search traffic data for 2020 into a DataFrame.
   - Slice the data for May 2020, when the company released quarterly financial results.
   - Visualize the search traffic and compare it with the monthly median traffic.

2. **Unusual Patterns:**
   - Analyze whether search traffic increases significantly during May compared to the other months.

### Step 2: Forecast Search Traffic with Prophet

1. **Data Preparation for Forecasting:**
   - Preprocess the time-series data for Prophet, ensuring proper date-time formatting.

2. **Build the Prophet Model:**
   - Initialize and train the Prophet model on the historical search traffic data.
   - Forecast search traffic for the remainder of 2020 and visualize the forecast.

3. **Analyze Forecast Results:**
   - Evaluate the model’s performance by comparing forecasted values with actual search traffic.
   - Visualize the forecast results with confidence intervals.

## Setup

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/sack2116/prophet-challenge.git
2. Copy prophet-challenge into one Drive 
3. Ensure Google Colab is Installed/Setup 
3. Open forecasting_net_prophet.ipynb with Colab
## How to Run the Notebook

1. **Environment Setup:**
   - Ensure all required libraries are installed, including `prophet`, `pandas`, and `matplotlib`.
   - Load the search traffic dataset into the notebook into Google Colab or Jupyter.

2. **Follow the Steps:**
   - Execute the cells in the notebook sequentially to replicate the analysis and forecasting.
   - The notebook is designed to guide you through the entire analysis, from data loading to building the forecast model.



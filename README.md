# Dynamic-Profitability-Simulator-for-Subscription-Models
Python - Prophet+Arima Time-Series Analysis along with Cohort Analysis

## Project Overview
  This notebook, Dynamic Profitability Simulator for Subscription Models, is something I put together to study how subscription-based businesses make money and how different factors can change profitability over time.The idea is to take into account things like customer acquisition, churn, pricing models, and subscription lengths and see how they affect revenue and profit when they play out in the long run.

## What it does
1. Simulates different growth and churn scenarios – so you can see how changes in customer numbers impact the business.
2. Forecasts trends – I’ve used Prophet and ARIMA to get future projections for revenue and customer base.
3. Cohort analysis – this part looks into customer lifetime value (LTV) and retention over time.
4. Tracks profitability – keeping an eye on revenue, costs, and margins in a dynamic way.
5. Visual outputs – most of the results are easy to follow because of the plots (made with Plotly and Matplotlib).

## 🛠️ Requirements

Download the CSV File and Install dependencies before running the notebook:

```bash
pip install pandas numpy matplotlib plotly lifelines prophet pmdarima dateparser polars pyarrow

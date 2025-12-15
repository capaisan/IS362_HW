# IS 362 Final Project Proposal
## The Affordability Crisis: Why Americans Feel Squeezed Despite 'Strong' GDP

**Student Name:** [Your Name]
**Date:** December 2025

---

## Project Overview

Despite positive GDP growth and low unemployment, many Americans report feeling financially squeezed. This project investigates the disconnect between macroeconomic indicators and lived economic experience by comparing real wage growth to the rising costs of essential goods and services from 2000 to 2025.

## Research Question

How has the purchasing power of median American households changed relative to the cost of everyday necessities, and why do people feel economically squeezed despite positive GDP growth?

## Data Sources

Using data from the Federal Reserve Economic Data (FRED) API, I will analyze:

- **Income Metrics:**
  - Median household income (annual)
  - Average hourly earnings (monthly)

- **Price Indices:**
  - Consumer Price Index (CPI) - overall inflation
  - CPI by category:
    - Food prices
    - Energy costs (gas, utilities)
    - Housing/shelter costs
    - Healthcare costs

- **Economic Context:**
  - Real GDP (inflation-adjusted) for comparison

All data will be accessed via the FRED API, which provides reliable, official economic statistics maintained by the Federal Reserve Bank of St. Louis.

## Methodology

1. **Data Acquisition:** Fetch time series data from FRED API for the period 2000-2025
2. **Data Cleaning:** Resample to consistent annual frequency, handle missing values, standardize column names
3. **Transformations:**
   - Index all metrics to base year 2000 = 100 for easy comparison
   - Calculate real (inflation-adjusted) wages
   - Compute purchasing power metrics
   - Create "squeeze" indices showing gap between income and cost growth
4. **Analysis:**
   - Time series comparison of wage growth vs. inflation
   - Category-specific cost analysis
   - Correlation analysis between metrics
   - Decade-by-decade trend analysis
   - CAGR (compound annual growth rate) calculations
5. **Visualization:**
   - Line charts showing income vs. inflation trends
   - Multi-category comparisons of cost growth
   - GDP vs. income disconnect visualization
   - Summary bar charts of total growth

## Expected Outcomes

This analysis will quantify:
- How much of median income is consumed by necessities today vs. 25 years ago
- Whether purchasing power has truly increased or Americans are working harder just to maintain the same standard of living
- Which necessity categories are rising fastest relative to income
- The gap between GDP growth and real income growth

## Significance

This project will provide clear, data-driven answers to why many Americans feel the economy isn't working for them, even when GDP numbers look strong. By comparing macroeconomic indicators (GDP, CPI) with household-level metrics (median income, real wages), the analysis will reveal the disconnect between "the economy" and individual economic experience.

The findings will help explain the lived reality behind headlines about economic growth and demonstrate the importance of looking beyond aggregate statistics to understand household financial wellbeing.

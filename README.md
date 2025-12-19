# Demand-Forecasting-Analysis-Multi-Model-Approach
Inventory optimization tool designed to applying behavior-specific forecasting models to historical sales data.

# Project Overview
This project is a comprehensive demand forecasting tool built in Excel to address diverse product demand behaviors. It applies specific statistical models—ranging from Regression to Seasonal Indices—to provide accurate future projections. The goal is to provide insights that help businesses minimize stockouts and prevent backorders.

# Methodology & Models

The project accounts for four distinct demand behaviors, and applying a specific statistical approach to each:

**1. Stable Demand (Normal Distribution)**
- Use Case: Products with consistent sales and minimal fluctuations.
- Logic: Uses the Arithmetic Mean of historical data.

**2. Seasonal Demand**
- Use Case: Products that see predictable spikes (e.g., icemakers in summer).
- Logic: Calculates Seasonality Indices for each period (quarter) and applies them to the average baseline.

**3. Trend-Based Demand**
- Use Case: Products in a growth or decline phase.
- Logic: Uses Linear Regression Analysis ($y = mx + b$) to project future values based on the line of best fit.
- Key Metric: R-Squared is used to validate the strength of the trend.

**4. Complex Demand (Trend + Seasonality)**
- Use Case: Products growing in popularity that also have seasonal peaks.
- Logic: A hybrid approach. First, a linear regression establishes the "De-seasonalized" trend line; then, seasonality indices are reapplied to the regression result.
- Formula: $\hat{y} = (mx + b) \times Seasonality Index$

# Repo Structure
```

```

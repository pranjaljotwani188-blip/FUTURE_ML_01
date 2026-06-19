#  Sales & Demand Forecasting for Businesses

**Internship:** Future Interns — Machine Learning Track
**Task:** 1 of 3

##  Objective
Build a machine learning model to forecast future sales/demand using historical business data, enabling data-driven inventory and business decisions.

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest Regressor)
- Jupyter Notebook

## Approach
1. Data Preparation** — Generated/cleaned 3 years of historical sales data
2. Feature Engineering** — Extracted time-based features (month, day of week, lag values, rolling averages)
3. Exploratory Data Analysis** — Identified trend, seasonality, and weekly sales patterns
4. Model Building** — Trained and compared Linear Regression vs Random Forest
5. Evaluation** — Assessed performance using MAE, RMSE, and R² Score
6. Forecasting** — Predicted next 90 days of sales
7. Business Insights** — Delivered actionable recommendations for inventory and staffing

##  Results
- Best Model:** Random Forest Regressor
- Accuracy (R² Score):** 67.7%
- Average Error:** ±113 units/day
- Key Insight:** Recent 7-day sales trend (Rolling_7) is the strongest predictor of future sales (74.9% feature importance)

##  Business Recommendations
1. Increase inventory ahead of peak demand months
2. Run promotions during low-demand periods
3. Staff up on weekends (106% above average sales)
4. Use ±113 units as a safety stock buffer

## Files in this Repository
- `FUTURE_ML_01.ipynb` — Full notebook with code, analysis, and visualizations
- `eda_analysis.png` — Exploratory data analysis charts
- `sales_forecast_dashboard.png` — Final forecast dashboard

##  Track
Machine Learning | Future Interns

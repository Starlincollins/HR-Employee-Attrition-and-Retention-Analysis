#  HR Employee Attrition and Retention Analysis

An end-to-end exploratory data analysis (EDA) and workforce analytics project investigating the drivers of employee turnover (16.12% attrition rate) across 1,470 personnel using Python, Pandas, Seaborn, and Matplotlib.

**Project Overview**

This project investigates the root causes of employee turnover (at 16.12%) within an organization of 1,470 employees. Using Python (`pandas`, `numpy`, `seaborn`, `matplotlib`), the workflow spans data cleaning, exploratory data analysis (EDA), univariate/bivariate/multivariate profiling, and actionable business strategy development.

**Key Findings**

**The Burnout Catalyst:** Mandatory overtime (`OverTime_Yes`) is the strongest single predictor of employee exit.
 **Compensation and Equity Vulnerability:** Entry-level tiers (`JobLevel_1`), low monthly income brackets (`MonthlyIncome_group_low`), and zero stock options (`StockOptionLevel_0`) drive high turnover.
**Tenure and Career Stagnation:** High-turnover roles (Sales Representatives, Laboratory Technicians) experience a major exit window within their first 1 to 3 years.

**Repository Structure**

**`notebooks/`**: Contains the step-by-step Python notebooks for EDA and feature engineering.
**`reports/`**: Presentation decks and slides detailing executive findings and recommendations.

**Strategic Recommendations**

1. **Immediate (0–3 Months)**: Audit overtime and implement workload caps to prevent burnout.
2. **Mid-Term (3–6 Months)**: Benchmark compensation for low-income brackets and expand stock option eligibility.
3. **Long-Term (6–12 Months)**: Introduce flexible hybrid/commute policies and build a predictive machine learning model for flight-risk scoring.

# us-macro-var-analysis
# Macroeconomic Dynamics of the U.S. Economy (1978–2025): A VAR-Based Analysis

## Project Overview
This project explores **long-term interactions** among key U.S. macroeconomic indicators from **January 1978 – May 2025** using **multivariate time series analysis**. The goal is to understand how changes in one variable impact others and the broader economy over time.

---

## Variables Studied
- **Personal Consumption Expenditure (PCE):** Measures consumer spending.  
- **Money Supply (M2):** Reflects monetary environment and policy stance.  
- **Industrial Production Index (INDPRO):** Captures manufacturing and supply-side activity.  
- **University of Michigan Consumer Sentiment Index (UMCSENT):** Gauges consumer confidence and expectations.

---

## Analytical Methods
- **Vector Autoregression (VAR)** for modeling interdependencies.  
- **Granger Causality Tests** to identify directional relationships.  
- **Impulse Response Functions (IRF)** to analyze dynamic effects of shocks.  
- **Forecast Error Variance Decomposition (FEVD)** to quantify variance contributions.  
- **Time Series Visualizations, ACF & PACF Plots** for preliminary diagnostics.  

---

## Key Findings
- Monetary aggregates (**M2**) are **not purely exogenous**; they respond dynamically to consumption (**PCE**) and production (**INDPRO**).  
- **PCE and INDPRO reinforce each other**, validating a demand-pull mechanism in the U.S. economy.  
- **Consumer Sentiment (UMCSENT)** evolves largely autonomously, influenced more by external psychological or geopolitical factors than core macroeconomic variables.  

---

## Policy Implications
- **Monetary Policy:** Should dynamically respond to real-time consumption patterns, not only inflation or output gaps.  
- **Industrial Output:** Can be boosted by combining fiscal measures (tax cuts, transfers) with monetary stimulus to meet demand quickly.  
- **Consumer Behavior:** Managed via expectation strategies, behavioral tools, and credible communication to stabilize sentiment.  
- **Forecasting:** Consumption and output improve each other's forecasts; sentiment may serve as an early warning signal in uncertain times.

---

## Project Workflow
1. Data collection (1978–2025) and preprocessing for stationarity (ADF & KPSS tests).  
2. Visualization of time series and correlation structures (ACF & PACF).  
3. VAR model fitting and optimal lag selection.  
4. Granger causality tests, IRF analysis, and FEVD decomposition.  
5. Interpretation of macroeconomic linkages and policy implications.

---

## Conclusion
This VAR-based analysis highlights a **feedback-driven structure** between real (PCE, INDPRO) and nominal (M2) variables, with sentiment (UMCSENT) behaving autonomously. Findings enhance understanding of how economic shocks propagate and inform **policy design, risk management, and business strategy**.

---

## Tech Stack
Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)

---

## Status
Analysis complete. Forecasting module and dashboard visualization planned for future iterations.


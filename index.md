# Predicting Prosperity: What Drives a Country’s GDP?

*Using World Bank data, we explore how life expectancy, health expenditure, education, and inflation influence GDP per capita across countries, supported by predictive modeling and visualizations.*

![Predicted vs Actual GDP Scatter Plot](scatter_plot.png)

---

## Introduction

GDP per capita is a common measure of a country's economic wellbeing. But what factors influence it the most? Using World Bank data, we explored economic, health, and education indicators to predict GDP per capita across countries.

This blog explains our findings in a clear, non-technical way, supported by visualizations and analysis.

---

## 1. Life Expectancy and GDP

**Hypothesis:** Countries with higher life expectancy tend to have higher GDP per capita.  

**Analysis:** Scatter plot of life expectancy vs GDP. 

**Interpretation:** The scatter plot shows a positive trend, indicating higher life expectancy is generally associated with higher GDP per capita.

**Conclusion:** The hypothesis is supported by the data.

---

## 2. Secondary School Enrollment and GDP

**Hypothesis:** Higher secondary school enrollment rates are associated with higher GDP per capita.

**Analysis:** Scatter plot of school enrollment vs GDP.

**Interpretation:** The relationship is positive but weaker than life expectancy.

**Conclusion:** Education appears to contribute positively to economic prosperity.

---

## 3. Inflation and GDP

**Hypothesis:** Higher inflation is associated with lower GDP per capita.

**Analysis:** Scatter plot of inflation vs GDP.

**Interpretation:** A mild negative relationship exists, with significant variation across countries.

**Conclusion:** Inflation has a negative but limited effect on GDP per capita.

---

## 4. Predicting GDP Per Capita

**Hypothesis:** GDP per capita can be predicted using socio-economic indicators.

**Model Results:**
	•	R²: ~0.39
	•	MAE: ~13,169 USD

**Interpretation:** The model explains ~39% of the variation. Extreme high-income countries are harder to predict accurately.

**Conclusion:** Socio-economic indicators provide meaningful predictive power, but additional factors also affect GDP.

---

## Deployment

**Purpose:** Make insights and the predictive model accessible to stakeholders.
	•	**GitHub:** Full notebook, cleaned dataset, and scatter plot available
	•	**Blog Post:** Communicates findings to non-technical stakeholders via GitHub Pages
	•	**Predictive Model:** Linear Regression model ready to generate GDP predictions on new data

**Example Scenario:** Increasing school enrollment and health expenditure predicts higher GDP per capita.

**Model Reuse:** The model can be saved and loaded using pickle for future predictions.

---

## Project Files

- [`Worldbank.ipynb`](Worldbank.ipynb) — full analysis, cleaning, and modeling  
- [`c538bed6-24d9-4d25-a075-11dc22bfe385_Data.csv`](c538bed6-24d9-4d25-a075-11dc22bfe385_Data.csv) — cleaned dataset  
- [`scatter_plot.png`](scatter_plot.png) — visualization of predicted vs actual GDP  

Explore the notebook and data directly in this repository.

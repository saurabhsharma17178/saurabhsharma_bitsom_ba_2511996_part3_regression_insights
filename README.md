# Part 3: Regression-Based Business Insights & Model Interpretation

## Project Overview

This project applies regression analysis to identify the key business factors associated with monthly sales across retail stores. Both simple and multiple linear regression models were developed and compared to understand the relationship between business variables and sales performance.

---

# Repository Structure

```
part3_regression_insights/
│
├── data/
│   └── business_regression_data.xlsx
│
├── analysis/
│   ├── regression_workbook.xlsx
│   ├── model_comparison.md
│   └── residual_analysis.md
│
├── outputs/
│   ├── regression_summary.xlsx
│   ├── final_recommendation.md
│   └── model_equations.md
│
├── screenshots/
│   ├── simple_regression_output.png
│   ├── multiple_regression_output.png
│   ├── residuals_preview.png
│   └── model_comparison_preview.png
│
└── README.md
```

---

# Business Scenario

A retail company wants to understand which business factors influence monthly sales across different stores. Regression analysis was used to identify significant variables and support business decision-making.

---

# Objectives

* Understand the dataset.
* Prepare clean regression data.
* Create dummy variables.
* Build simple regression models.
* Build a multiple regression model.
* Compare regression models.
* Perform residual analysis.
* Interpret regression coefficients.
* Provide business recommendations.

---

# Dataset

The dataset contains information about retail store performance, including:

* Store ID
* Region
* Store Type
* Marketing Spend
* Footfall
* Inventory Availability
* Discount Percentage
* Staff Count
* Customer Rating
* Monthly Sales
* Monthly Profit

---

# Regression Models

## Simple Regression Models

Two simple regression models were developed:

### Model 1

* Dependent Variable: Monthly Sales
* Independent Variable: Marketing Spend

### Model 2

* Dependent Variable: Monthly Sales
* Independent Variable: Footfall

---

## Multiple Regression Model

Dependent Variable:

* Monthly Sales

Independent Variables:

* Marketing Spend
* Footfall
* Inventory Availability
* Region_N (Dummy Variable)

---

# Model Comparison

The models were compared using:

* R-Squared
* Statistical significance
* Business usefulness
* Model limitations

The comparison showed that the multiple regression model provides broader business insights by evaluating multiple predictors simultaneously.

---

# Residual Analysis

Residual analysis was performed by:

* Calculating predicted monthly sales.
* Computing residual values.
* Identifying stores with the largest positive residuals.
* Identifying stores with the largest negative residuals.
* Evaluating possible reasons for prediction errors.

---

# Key Findings

* Customer Footfall is the strongest predictor of monthly sales.
* Inventory Availability has a significant positive relationship with sales.
* Marketing Spend contributes positively to sales.
* The Region_N dummy variable was not statistically interpretable in the final model.
* The multiple regression model provides better decision support than individual regression models because it considers multiple business drivers together.

---

# Business Recommendations

* Increase customer footfall through targeted marketing initiatives.
* Maintain high inventory availability to reduce lost sales.
* Optimize marketing investments based on performance.
* Continue collecting additional business variables such as promotions and seasonal effects to improve future prediction accuracy.

---

# Files Included

* Regression Workbook
* Model Comparison Report
* Residual Analysis Report
* Regression Summary Workbook
* Model Equations Document
* Final Recommendation Report
* Required Screenshots

---

# Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* Linear Regression Analysis
* Dummy Variable Encoding

---

# Conclusion

Regression analysis helped identify the primary business drivers of monthly sales. The final multiple regression model offers useful business insights and can assist leadership in making informed decisions related to marketing, inventory management, and overall store performance.

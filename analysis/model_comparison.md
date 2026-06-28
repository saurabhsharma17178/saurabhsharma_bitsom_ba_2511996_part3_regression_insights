# Model Comparison

## Model 1: Simple Regression (Marketing Spend)

### Variables Used
- Dependent Variable: Monthly Sales
- Independent Variable: Marketing Spend

### R-Squared
0.1672

### Significant Variables
- Marketing Spend (P-value = 2.48E-14)

### Business Usefulness
Marketing spend positively influences monthly sales but explains only a small portion of sales variation.

### Limitations
This model considers only one predictor and ignores other important business factors.

---

## Model 2: Simple Regression (Footfall)

### Variables Used
- Dependent Variable: Monthly Sales
- Independent Variable: Footfall

### R-Squared
0.7363

### Significant Variables
- Footfall (P-value = 4.75E-94)

### Business Usefulness
Footfall is a strong predictor of monthly sales and explains a large proportion of sales variation.

### Limitations
The model does not account for marketing, inventory availability, or regional differences.

---

## Model 3: Multiple Regression

### Variables Used
Dependent Variable:
- Monthly Sales

Independent Variables:
- Marketing Spend
- Footfall
- Inventory Availability
- Region_N (Dummy Variable)

### R-Squared
0.4577

### Significant Variables
- Marketing Spend
- Footfall
- Inventory Availability

Region_N could not be interpreted because of a numerical issue (#NUM!).

### Business Usefulness
This model considers multiple business drivers simultaneously and provides better insights than a single-variable model.

### Limitations
The model explains only about 45.8% of sales variation and may miss other important factors such as promotions, seasonality, and economic conditions.

---

# Overall Comparison

| Model | R² | Best Variable |
|-------|------|---------------|
| Marketing Spend | 0.1672 | Marketing Spend |
| Footfall | 0.7363 | Footfall |
| Multiple Regression | 0.4577 | Footfall + Inventory + Marketing |

## Conclusion

Among the simple regression models, Footfall performs the best because it has the highest explanatory power (R² = 0.7363). The multiple regression model provides broader business insights by considering several predictors together, making it more useful for business decision-making despite its lower R² than the Footfall-only model.
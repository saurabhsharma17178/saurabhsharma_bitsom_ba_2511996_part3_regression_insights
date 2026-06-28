# Dummy Variable Creation

Categorical Variable Used:

- Region

Reference Category:

- West

Dummy Variables Created:

- Region_North
- Region_South
- Region_East

Reason:

West was selected as the reference category to avoid the dummy variable trap (perfect multicollinearity). Each dummy variable takes a value of 1 if the observation belongs to that region; otherwise it takes a value of 0.



# Model Equations

## Simple Regression Model 1

### Dependent Variable
Monthly Sales

### Independent Variable
Marketing Spend

### Regression Equation

Monthly Sales = 560777.3 + (2.1296 × Marketing Spend)

### Results

- R Square: 0.1672
- Coefficient: 2.1296
- P-value: 2.48E-14

### Business Interpretation

Marketing spend has a positive and statistically significant impact on monthly sales. An increase in marketing spend is associated with higher monthly sales.

### Variable Usefulness

Useful predictor because the p-value is less than 0.05.

---

## Simple Regression Model 2

### Dependent Variable
Monthly Sales

### Independent Variable
Footfall

### Regression Equation

Monthly Sales = 446410.6 + (35.6780 × Footfall)

### Results

- R Square: 0.7363
- Coefficient: 35.6780
- P-value: 4.75E-94

### Business Interpretation

Footfall has a strong positive relationship with monthly sales. Stores with higher customer footfall tend to generate higher monthly sales.

### Variable Usefulness

Footfall is a very strong predictor because it has a high R Square and a highly significant p-value.

---

## Comparison

| Variable | R Square | P-value | Useful |
|----------|---------:|---------|:------:|
| Marketing Spend | 0.1672 | 2.48E-14 | Yes |
| Footfall | 0.7363 | 4.75E-94 | Yes |

### Conclusion

Among the two simple regression models, **Footfall** is the better predictor of monthly sales because it explains a much larger proportion of the variation in sales (R² = 0.7363) than Marketing Spend (R² = 0.1672).


| Metric            |        Value |
| ----------------- | -----------: |
| R Square          |   **0.4577** |
| Adjusted R Square |   **0.4508** |
| F Statistic       |    **66.47** |
| Significance F    | **1.01E-40** |



# Model Equations

# Simple Regression Model 1

## Dependent Variable
Monthly Sales

## Independent Variable
Marketing Spend

### Regression Equation

Monthly Sales = 560777.3 + (2.1296 × Marketing Spend)

### Coefficient Explanation

- Intercept (560777.3): Expected monthly sales when marketing spend is zero.
- Marketing Spend Coefficient (2.1296): Every one-unit increase in marketing spend increases monthly sales by approximately 2.13 units.

---

# Simple Regression Model 2

## Dependent Variable
Monthly Sales

## Independent Variable
Footfall

### Regression Equation

Monthly Sales = 446410.6 + (35.6780 × Footfall)

### Coefficient Explanation

- Intercept (446410.6): Expected monthly sales when footfall is zero.
- Footfall Coefficient (35.6780): Each additional customer visit increases monthly sales by about 35.68 units.

---

# Multiple Regression Model

## Regression Equation

Monthly Sales =
-80484.1
+ (0.194328 × Marketing Spend)
+ (6.391292 × Footfall)
+ (1576.133 × Inventory Availability)
+ (0 × Region_N)

---

## Coefficient Explanation

### Intercept

Represents the baseline monthly sales when all predictor variables are zero.

### Marketing Spend

A one-unit increase in marketing spend increases monthly sales by approximately 0.194 units, while keeping other variables constant.

### Footfall

A one-unit increase in customer footfall increases monthly sales by approximately 6.39 units, assuming other variables remain unchanged.

### Inventory Availability

A one-unit increase in inventory availability percentage increases monthly sales by approximately 1576.13 units.

### Region_N (Dummy Variable)

The coefficient is zero because the variable could not be interpreted correctly in the final regression model.

---

# Dummy Variable Explanation

Categorical Variable Used:
- Region

Dummy Variable Used:
- Region_N

Meaning:
- 1 = Store belongs to North Region
- 0 = Store does not belong to North Region

---

# Reference Category

Reference Category:
- West Region

The West region was used as the reference category to avoid the dummy variable trap.

---

# Final Model Selected

Selected Model:
- Multiple Regression Model

---

# Reason for Selecting the Final Model

The multiple regression model was selected because it considers multiple business factors simultaneously, including marketing spend, footfall, inventory availability, and regional information. It provides more comprehensive business insights than simple regression models.

Although the Footfall simple regression model achieved a higher R², the multiple regression model is more useful for business decision-making because it evaluates the combined impact of several important variables on monthly sales.

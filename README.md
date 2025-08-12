# 🏠 Task 3: Linear Regression

**Objective:**  
Implement Simple & Multiple Linear Regression using the Housing Price Prediction dataset, evaluate model performance, and interpret results.

**Dataset:**  
[Kaggle - Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
Rows: 545 | Columns: 13 | Features include area, bedrooms, bathrooms, stories, and more.

**Approach:**
1. Data loading, exploration, and preprocessing (encoding categorical variables).
2. Simple Linear Regression: `area` → `price`.
3. Multiple Linear Regression: `area`, `bedrooms`, `bathrooms`, `stories` → `price`.
4. Evaluation using **MAE**, **MSE**, **R²**.
5. Coefficient interpretation for multiple regression.

**Results:**

| Model | MAE | MSE | R² |
|-------|------|------|------|
| Simple LR | 1,474,748 | 3.675e+12 | 0.2729 |
| Multiple LR | 1,158,970 | 2.457e+12 | 0.5138 |

**Insights:**  
- Multiple LR achieved better accuracy than Simple LR.  
- Bathrooms and stories significantly influence price along with area.

**Tech Stack:**  
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

# Task 3: Linear Regression - AI & ML Internship

## 📌 Objective

Implement and understand **Simple & Multiple Linear Regression** using the **Housing Price Prediction** dataset.

## 📂 Dataset

[Kaggle Dataset - Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🔍 Project Steps

1. Imported and preprocessed the dataset (converted categorical features using `get_dummies`).
2. Split the data into train and test sets (80/20).
3. Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`.
4. Evaluated the model using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score
5. Visualized the **actual vs predicted** values and extracted model coefficients.

## 📈 Results

- **MAE**: 82718.44
- **MSE**: 10591377901.57
- **R² Score**: 0.91


These results may vary slightly depending on your train-test split.

## 📊 Plot

Scatter plot showing actual vs predicted house prices.
![image](https://github.com/user-attachments/assets/558a44e3-1d8f-4b14-8dbd-091a2e91c461)


## 📚 Interview Questions & Answers

### 1. What assumptions does linear regression make?
- Linearity
- Independence
- Homoscedasticity (equal variance)
- Normality of residuals
- No multicollinearity

---

### 2. How do you interpret the coefficients?
Each coefficient represents the **expected change in the target variable** for a **unit increase** in the corresponding feature, keeping others constant.

---

### 3. What is R² score and its significance?
R² (coefficient of determination) indicates how much variance in the target variable is explained by the model. R² = 1 means perfect prediction.

---

### 4. When would you prefer MSE over MAE?
MSE penalizes larger errors more heavily, so use it when **large errors are more problematic** than small ones.

---

### 5. How do you detect multicollinearity?
- Use **correlation matrix**
- Calculate **Variance Inflation Factor (VIF)** — VIF > 10 indicates multicollinearity.

---

### 6. Difference between simple and multiple regression?
- Simple Regression: One independent variable
- Multiple Regression: Two or more independent variables

---

### 7. Can linear regression be used for classification?
Not directly. Classification requires discrete outputs; linear regression outputs continuous values.

---

### 8. What happens if you violate regression assumptions?
The model’s performance and validity deteriorate — coefficients become unreliable, and predictions can be misleading.


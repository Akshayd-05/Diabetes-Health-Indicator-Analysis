# 📊 Insurance Claim Prediction and Analysis
## 📝 Project Overview

This project focuses on analyzing and predicting insurance claim amounts using regression techniques. The dataset includes customer demographics, health-related factors, and other relevant features that influence insurance charges.

**Objectives:**

- Perform exploratory data analysis (EDA) on the insurance dataset.
- Predict insurance charges based on age, BMI, smoking status, and other factors.
- Evaluate and compare multiple regression models.
- Visualize patterns in the data related to diabetes, blood pressure, and job title.

---

## 📈 Dataset Details

- **Dataset Name:** `diabetes_health_indicators.csv`

| Column        | Description                               |
|---------------|-------------------------------------------|
| age           | Age of the customer                       |
| sex           | Gender of the customer                    |
| bmi           | Body Mass Index (health metric)           |
| children      | Number of dependents                      |
| smoker        | Smoker status (yes/no)                    |
| region        | Customer's geographical region            |
| charges       | Medical insurance claim amount            |
| diabetes      | Diabetes status (yes/no)                  |
| bp            | Blood Pressure level                      |
| job_title     | Customer's occupation                     |
| exercise      | Weekly exercise frequency                 |

---

## ⚙️ Technologies Used

- **Python 3.9+**
- **Jupyter Notebook**
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels

---

## 🔍 Key Features & Analysis

1. **Exploratory Data Analysis (EDA)**
   - Summary statistics & data cleaning
   - Correlation heatmaps
   - Visualization of factors affecting charges

2. **Regression Modeling**
   - Linear Regression
   - Lasso Regression
   - Ridge Regression
   - Model performance evaluation using MSE, RMSE, and R²

3. **Insights Extraction**
   - Impact of smoking, BMI, and age on claim amounts
   - Health risk analysis based on diabetes and BP

4. **Interactive Visualizations (Optional)**
   - Potential for integration with Tableau or Plotly

---

## 📊 Outputs & Results

- Visualization of key insights such as:
  - Insurance Charges vs Smoking Status
  - Insurance Charges vs BMI
  - Insurance Charges vs Age
- Regression Model Comparison Table (Linear, Lasso, Ridge)
- Final prediction outputs for insurance claim amounts

---

## 🧠 Insights & Learnings

- **Smokers** pay significantly higher insurance premiums compared to non-smokers.
- **BMI and Age** are strong predictors of insurance claim amounts.
- **Lasso & Ridge Regression** help handle multicollinearity and improve model generalization.

---

## 🗂️ Future Improvements

- Deploy the model using **Flask** or **FastAPI** for API-based predictions.
- Create an interactive **Tableau** or **Power BI dashboard** for business insights.
- Integrate **real-time data pipelines** for continuous monitoring and prediction updates.

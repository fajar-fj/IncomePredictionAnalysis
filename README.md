# Income Prediction using Logistic Regression

## 📌 Project Overview
This project focuses on building a binary classification model to predict whether an individual's annual income is greater than $50,000 based on demographic and employment data. Using the **UCI Adult Income Dataset**, I implemented a Machine Learning pipeline that includes data cleaning, exploratory analysis, and predictive modeling.

## 📊 Dataset Features
The model analyzes several key factors:
- **Demographics:** Age, Race, Sex, Marital Status, Native Country.
- **Socio-Economic:** Workclass, Occupation, Education Level, and Hours per week.
- **Target Variable:** Income (<=50K or >50K).

## 🛠️ Technical Workflow
1. **Data Preprocessing:**
   - Handled missing values (marked as '?') using mode imputation.
   - Applied **Label Encoding** for categorical variables.
   - Scaled numerical features using **StandardScaler** to improve model convergence.
2. **Exploratory Data Analysis (EDA):**
   - Created correlation heatmaps to identify relationships between features.
   - Visualized distributions using Seaborn (Countplots for education vs. income, Histograms for age).
3. **Modeling:**
   - Implemented **Logistic Regression** using `scikit-learn`.
   - Split data into training and testing sets (70/30 split).
4. **Evaluation:**
   - Evaluated performance using Accuracy, Precision, Recall, and F1-score.

## 🚀 Results
The model achieved strong predictive power:
- **Accuracy:** ~84.5%
- **ROC AUC Score:** 0.88
- **Key Insight:** Education level, occupation, and age were found to be the most significant predictors of high income.

## 💻 Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

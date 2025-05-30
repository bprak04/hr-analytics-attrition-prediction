# HR Analytics – Attrition Prediction

This project analyzes HR data to predict whether an employee is likely to leave the company, using multiple classification models and visual analytics.

## 📁 Dataset

- Source: IBM HR Analytics Employee Attrition Dataset
- Download link: [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## 🔧 Tools & Libraries

- Python, Pandas, Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Google Colab

## 📊 Key Steps

1. **Data Cleaning & Encoding**
   - Encoded `Attrition` into binary values
   - Removed redundant or ID-like columns

2. **Data Visualization**
   - Bar charts for attrition by gender & department
   - Correlation heatmap of top predictors

3. **Modeling**
   - Logistic Regression, Random Forest, and XGBoost
   - Evaluated using classification report, confusion matrix, accuracy

## ✅ Results

- **Best Accuracy**: ~85% (Random Forest)
- **Important Features**: `OverTime`, `JobRole`, `YearsAtCompany`, `MonthlyIncome`, etc.

## 📤 Export

- Cleaned dataset exported for Tableau visualization

---

### 👤 Author

Prakhyath Boinpally  
🔗 [LinkedIn](#) | 💼 [Portfolio](#)

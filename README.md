# Predicting-Credit-Card-Account-Cancellations

## 📁 Project Overview
This machine learning project focuses on predicting whether a customer will cancel their credit card account based on demographic and financial behavior data. The analysis was performed using a dataset from a U.S. bank with over 4,000 customer records. The aim is to provide actionable insights to reduce customer churn and maximize financial retention.

## 🎯 Objectives
- Identify key factors influencing credit card account cancellations.
- Build and evaluate classification models to predict account closure.
- Provide strategic recommendations to minimize churn.

## 🧪 Dataset
The dataset (`credit_card_df`) includes:
- **Rows**: 4,627 customers
- **Target variable**: `customer_status` — `closed_account` or `active`
- **Features**: Age, income, employment status, card type, credit limit, spend ratio, etc.

## 🔍 Exploratory Data Analysis
Key insights include:
- Customers aged 35-55 with 2-3 dependents show high churn.
- Part-time employed customers and those earning < $5,000/year are more likely to cancel.
- A higher spend ratio and low credit limit correlate with increased account closures.

Visuals and tables from EDA include:
- Bar charts, box plots, scatter plots
- Summary tables using `dplyr` and `ggplot`

## 🧠 Models Used
Three classification algorithms were implemented:
1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest** (Best performer)

### 📈 Performance (ROC AUC):
- Logistic Regression: `0.94`
- Decision Tree: `0.97`
- Random Forest: `0.99` ✅

## 🔍 Evaluation Metrics
- Confusion matrix
- ROC Curve
- Area Under Curve (AUC)
- Accuracy, Sensitivity, Specificity (via parsnip and yardstick in R)

## 🧩 Recommendations
Based on analysis:
- Targeted marketing for 35–55 age group with low income
- Incentives for part-time workers with high spend ratios
- Adjust credit limits for customers with high transaction counts but low credit limits
- Launch financial education programs to reduce churn risk

## 📁 Project Structure
```
├── Ritesh_Somashekar_ml_project.ipynb  # Code & analysis (Python)
├── Credit Card Cancnelling report.pdf   # Detailed report
├── README.md                           # You're reading it
```

## 🚀 How to Run
1. Install Python packages (if re-running):
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Ritesh_Somashekar_ml_project.ipynb
   ```

## 👨‍💻 Author
Ritesh Somashekar  


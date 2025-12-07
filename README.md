# Customer Churn Analysis – BCG Data Science - XYZ Analytics Simulation

**Project Overview**  
This project simulates a **customer churn analysis** for a utility company, using historical electricity and gas consumption, pricing data, and churn indicators. The goal is to **identify patterns leading to churn** and build predictive models to flag high-risk customers, providing actionable insights for retention strategies.

---

## Key Highlights

- Conducted **exploratory data analysis (EDA)** to understand usage, pricing, and churn trends.  
- Engineered features from raw data, including temporal trends, product bundling, margins, and channel indicators.  
- Built and optimized a **Random Forest classifier**, achieving **50% recall** in predicting customer churn.  
- Produced **executive summary**, highlighting actionable insights for stakeholders.  
- Identified **key drivers of churn**: product bundling, net/gross margin, contract tenure, and acquisition channel quality.

---

## Technologies & Tools

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning**: Random Forest Classifier, SMOTE for class balancing  
- **Data Visualization**: Histograms, Countplots, Correlation Heatmaps, Feature Importance, ROC Curve, Confusion Matrix  
- **Documentation & Reporting**: Jupyter Notebook, Executive Summary Slide  

---

## Exploratory Data Analysis (EDA)

- Distribution of electricity and gas consumption  
- Countplots for sales channels and product types  
- Correlation heatmap showing relationships between features and churn  
- Identification of high-risk customer segments  

---

## Modeling Approach

- **Random Forest Classifier** for predicting churn  
- Addressed class imbalance using **SMOTE**  
- Evaluated using:  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-Score)  
  - ROC Curve and AUC  

---

## Insights & Recommendations

- **Bundling Effect**: Electricity + gas customers churn less than electricity-only customers.  
- **Channel Effect**: Customers acquired via certain channels have 1.6× higher churn risk.  
- **Tenure Effect**: Longer-tenure customers are less likely to churn.  
- **Pricing Sensitivity**: Minor role compared to operational factors (margins, bundling, channels).  
- **Actionable Steps**: Targeted retention campaigns focusing on high-risk segments, optimization of bundling, and channel strategies.  

---

## Visualizations to Highlight

- Confusion Matrix & ROC Curve  
- Feature Importance (Top 10–20 predictors)  
- Distribution of predicted churn probabilities  
- Segment-wise churn probability comparisons  

---

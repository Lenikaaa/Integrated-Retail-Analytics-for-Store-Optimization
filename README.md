# 🛒 Integrated Retail Analytics for Store Optimization and Demand Forecasting

## 📌 Project Overview

This project focuses on building an end-to-end Retail Analytics solution using Machine Learning and Data Analytics techniques. The objective is to optimize store performance, forecast weekly sales, identify sales anomalies, segment stores based on performance, discover product associations, and generate actionable business strategies for inventory management and personalized marketing.

The project integrates data preprocessing, feature engineering, anomaly detection, customer segmentation, market basket analysis, demand forecasting, and business intelligence into a single analytics workflow.

---

## 🎯 Objectives

- Detect unusual sales patterns across stores and departments.
- Analyze time-based trends and seasonality.
- Forecast weekly sales using Machine Learning models.
- Segment stores based on sales behavior.
- Discover product associations using Market Basket Analysis.
- Analyze the impact of external economic factors on sales.
- Recommend inventory optimization and personalized marketing strategies.

---

## 📂 Dataset

The project uses three datasets:

### 1. Sales Dataset
Contains weekly sales for each department across stores.

Features include:
- Store
- Department
- Weekly Sales
- Date
- Holiday Flag

### 2. Stores Dataset
Contains store-related information.

Features include:
- Store
- Store Type
- Store Size

### 3. Features Dataset
Contains external variables affecting sales.

Features include:
- Temperature
- Fuel Price
- CPI
- Unemployment
- MarkDown1–5
- IsHoliday

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- mlxtend
- SciPy
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Understanding

- Dataset exploration
- Missing value analysis
- Duplicate detection
- Data profiling

### 2. Data Wrangling

- Merge datasets
- Handle missing values
- Outlier treatment
- Feature encoding

### 3. Feature Engineering

Created features including:

- Year
- Month
- Week
- Day
- DayOfYear
- Total_MarkDown
- Lag_1
- Rolling 4-week Average

---

### 4. Exploratory Data Analysis

- Sales Trends
- Store Performance
- Department Analysis
- Correlation Analysis
- Holiday Effects
- External Factors

---

### 5. Hypothesis Testing

Performed statistical tests including:

- Independent t-Test
- One-Way ANOVA
- Pearson Correlation

---

### 6. Anomaly Detection

- Negative Sales Detection
- Holiday Demand Analysis
- Outlier Investigation

---

### 7. Store Segmentation

Implemented:

- K-Means Clustering
- PCA Visualization

Evaluation Metrics:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Score

---

### 8. Market Basket Analysis

Implemented:

- Apriori Algorithm
- Association Rule Mining

Metrics:

- Support
- Confidence
- Lift

Business applications:

- Cross-selling
- Shelf Optimization
- Joint Promotions

---

### 9. Demand Forecasting

Implemented three Machine Learning models:

- Ridge Regression
- Random Forest Regressor
- Histogram Gradient Boosting Regressor

Evaluation Metrics:

- R² Score
- RMSE
- MAE
- Weighted MAE (WMAE)

---

### 10. Business Strategy

Recommendations include:

- Inventory Optimization
- Personalized Marketing
- Promotional Planning
- Store Optimization
- Demand Planning

---

## 📈 Results

### Best Forecasting Model

Histogram Gradient Boosting Regressor

Performance:

- R² ≈ 0.979
- RMSE ≈ 3221
- MAE ≈ 1543

---

## 📁 Repository Structure

```
Integrated-Retail-Analytics/
│
├── Capstone_Project_9_Integrated_Retail_Analytics.ipynb
├── Documentation.docx
├── README.md
├── requirements.txt
├── data/
│   ├── sales.csv
│   ├── stores.csv
│   └── features.csv
│
├── models/
│   └── best_sales_forecast_model.pkl
│
├── images/
│
└── outputs/
```

---

## 🚀 Future Improvements

- Deep Learning based forecasting (LSTM)
- Prophet Time-Series Forecasting
- XGBoost and LightGBM models
- Real-time dashboard using Streamlit
- Customer-level recommendation system
- Integration with cloud deployment

---

## 👩‍💻 Author

**Lenika Yogi**

Master's in Data Science

---

## 📜 License

This project is developed for educational purposes as part of the Capstone Project.

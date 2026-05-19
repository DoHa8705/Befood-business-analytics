# 🍔 BeFood Business Analytics & Sales Prediction

## 📌 Overview

This project focuses on analyzing large-scale food and beverage data collected from the BeFood platform to uncover customer behavior, restaurant trends, and sales performance.

The project combines:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning

to support data-driven decision-making in the food delivery industry.

---

## 🎯 Business Objectives

This project aims to answer several business-related questions:

* Which food and beverage categories are the most popular?
* How do customer preferences vary across districts in Ho Chi Minh City?
* Which factors influence product sales performance?
* What are the differences in restaurant performance between districts?
* Can machine learning models effectively predict sales-related metrics?

---

## 🗂️ Dataset Description

The dataset was collected from the BeFood platform and contains semi-structured JSON data related to:

* Food and beverage products
* Restaurants and vendors
* Customer ratings and engagement
* Sales-related information
* District-level location data

The project processes large-scale food delivery data for analytics and prediction tasks.

---

## ⚙️ Technologies Used

| Category          | Technologies              |
| ----------------- | ------------------------- |
| Programming       | Python                    |
| Data Processing   | Pandas, NumPy             |
| Visualization     | Matplotlib, Seaborn       |
| Machine Learning  | Scikit-learn, XGBoost     |
| Database          | MongoDB                   |
| Development Tools | Jupyter Notebook, VS Code |

---

## 🔄 Data Workflow

### 1. Data Collection

* Retrieved and processed food delivery datasets from MongoDB
* Converted semi-structured JSON data into structured analytical datasets
* Exported cleaned datasets for downstream analysis

### 2. Data Cleaning & Preprocessing

* Renamed and standardized columns
* Handled missing values and inconsistent formats
* Processed categorical and numerical features
* Removed duplicate and invalid records

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to identify:

* Popular dishes and beverage categories
* Restaurant performance trends
* District-based customer preferences
* Relationships between ratings, engagement, and sales performance

### 4. Data Visualization

The following visualizations were developed to analyze relationships between restaurants, food products, and customer engagement metrics on the BeFood platform.

These analyses help identify interaction patterns between user behavior and product performance, while also revealing correlations among key business indicators.

* Restaurant & Product Relationship Analysis

Visualized the relationship between restaurants and food products to identify product distribution and restaurant-level performance patterns.

<img width="653" height="619" alt="Screenshot 2026-05-19 154024" src="https://github.com/user-attachments/assets/f2232645-93d2-401b-b1ee-2ac2b0cece18" />

*Customer Engagement Analysis

Analyzed the relationship between likes, dislikes, and purchase volume to evaluate how customer interactions influence product popularity and sales performance.
<img width="611" height="586" alt="Screenshot 2026-05-19 154052" src="https://github.com/user-attachments/assets/17f5fc64-71ee-428e-ad48-27d9b78dde61" />


*Correlation Heatmap

Built a correlation matrix to explore relationships among numerical variables such as ratings, likes, dislikes, comments, and sales-related metrics.
<img width="607" height="521" alt="Screenshot 2026-05-19 154119" src="https://github.com/user-attachments/assets/28ffa7a7-2383-4522-b692-9f97585775ac" />


### 5. Machine Learning & Prediction

Implemented and compared multiple regression models:

* Linear Regression
* Gradient Boosting Regressor
* XGBoost Regressor

Evaluation metrics:

* RMSE
* MAE
* R² Score

---

## 📊 Model Performance Comparison

| Model             | RMSE | MAE | R² Score |
| ----------------- | ---- | --- | -------- |
| Linear Regression | ...  | ... | ...      |
| Gradient Boosting | ...  | ... | ...      |
| XGBoost           | ...  | ... | ...      |

---

## 💡 Key Insights

* Food and beverage preferences vary significantly across districts in Ho Chi Minh City
* Highly rated restaurants tend to achieve stronger sales performance
* Customer engagement metrics show positive correlation with sales-related indicators
* Certain beverage categories dominate customer demand in specific local areas
* Ensemble models such as Gradient Boosting and XGBoost achieved better prediction performance compared to baseline Linear Regression models

---

## 📈 Visualization Preview

### Top-Selling Food Categories

![Top Categories](images/top_categories.png)

---

### District-Based Analysis

![District Analysis](images/district_analysis.png)

---

### Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

---

### Regression Analysis

![Regression](images/regression_analysis.png)

---

## 📁 Repository Structure

```bash
befood-business-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_analysis.ipynb
│   └── 04_sales_prediction.ipynb
│
├── images/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

* Build interactive dashboards using Power BI or Tableau
* Extend the analysis to multiple cities and additional food categories
* Deploy prediction models for real-time forecasting
* Integrate automated data pipelines for continuous analytics updates

---

## 📌 Conclusion

This project demonstrates an end-to-end business analytics workflow using real-world food delivery data.

By combining data engineering, exploratory analysis, visualization, and machine learning techniques, the project provides actionable business insights to support data-driven decision-making in the food delivery industry.

# 📦 Supply Chain Analytics & Demand Forecasting

An end-to-end Supply Chain Analytics project that combines **Data Analysis, Machine Learning, and Business Intelligence** to uncover operational insights and forecast product demand. The project leverages Python for data preprocessing and predictive modeling and Power BI for creating interactive business dashboards.

---

## 📌 Project Overview

Efficient supply chain management is critical for reducing operational costs and improving customer satisfaction. This project analyzes supply chain data to identify inventory risks, evaluate supplier performance, optimize transportation decisions, and forecast future product demand using Machine Learning.

The final solution provides actionable insights through an interactive Power BI dashboard that enables data-driven decision-making.

---

## 🎯 Objectives

- Analyze supply chain operations using Exploratory Data Analysis (EDA).
- Identify inventory trends, supplier performance, and transportation costs.
- Forecast future product demand using Machine Learning.
- Build an interactive Power BI dashboard for business users.

---

## 📂 Repository Structure

```
Supply-Chain-Analytics/
│
├── data/
│   ├── supply_chain_data.csv
│   └── forecasted_supply_chain.csv
│
├── notebooks/
│   └── supply_chain_analysis.ipynb
│
├── dashboard/
│   └── supply_chain.pbix
│
├── images/
│   ├── dashboard_overview.png
│   ├── inventory_dashboard.png
│   ├── logistics_analysis.png
│   └── forecasting_results.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 📊 Dataset

The dataset contains supply chain operational information, including:

- Product Type
- SKU
- Inventory Levels
- Number of Products Sold
- Revenue Generated
- Manufacturing Costs
- Shipping Costs
- Lead Time
- Supplier Information
- Transportation Mode
- Order Quantities
- Defect Rates
- Inspection Results

---

## 🛠️ Project Workflow

```
Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Insights
      │
      ▼
Feature Engineering
      │
      ▼
Random Forest Regression
      │
      ▼
Demand Forecasting
      │
      ▼
Power BI Dashboard
```

---

## 🧹 Data Preprocessing

- Removed duplicate records
- Handled missing values
- Converted data into appropriate formats
- Performed feature selection
- Prepared data for Machine Learning

---

## 📈 Exploratory Data Analysis

The project includes analysis of:

- Inventory distribution
- Revenue analysis
- Product-wise sales
- Supplier performance
- Shipping cost analysis
- Manufacturing cost comparison
- Transportation mode analysis
- Correlation between business variables
- Demand distribution

---

## 🤖 Machine Learning

### Model Used

- Random Forest Regressor

### Goal

Predict future product demand based on historical supply chain data.

### Machine Learning Pipeline

- Data preprocessing
- Train-test split
- Model training
- Prediction
- Model evaluation
- Future demand forecasting

---

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive visualizations for:

- Executive KPI Dashboard
- Revenue Analysis
- Inventory Monitoring
- Supplier Performance
- Shipping Cost Analysis
- Transportation Insights
- Demand Forecast
- Product Performance

Users can filter reports dynamically to explore business performance across different products and suppliers.

---

## 💡 Key Insights

- Identified high-performing and underperforming suppliers.
- Analyzed inventory trends to detect stockout and overstock risks.
- Compared transportation modes based on shipping costs.
- Forecasted future product demand using Machine Learning.
- Built an interactive dashboard for data-driven supply chain decision-making.

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Dashboard | Power BI |
| Development | Jupyter Notebook |

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Supply-Chain-Analytics.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebooks/supply_chain_analysis.ipynb
```

To explore the dashboard, open:

```
dashboard/supply_chain.pbix
```

using Microsoft Power BI Desktop.

---

## 📷 Dashboard Preview

> Add screenshots of your Power BI dashboard inside the **images/** folder.

Example:

- Executive Dashboard
- Inventory Dashboard
- Supplier Dashboard
- Demand Forecast Dashboard

---

## 📌 Future Improvements

- Time Series Forecasting using ARIMA or LSTM
- Hyperparameter tuning with GridSearchCV
- Model comparison (Linear Regression, XGBoost, CatBoost)
- SQL database integration
- Streamlit web application deployment
- Real-time dashboard using live data

---

## 👨‍💻 Author

**Aditya Singh**

- B.Tech CSE
- AI & Data Analytics Enthusiast

---

## ⭐ If you found this project useful, consider giving it a star!

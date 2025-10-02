# 📊 Financial Market Data EDA — Portfolio Project

This repository showcases a **Python-based Exploratory Data Analysis (EDA)** on financial market data.  
The goal is to transform raw CSV input into **analytics-ready insights and visualizations**, highlighting patterns, trends, and correlations across key financial indicators.  

---

## 🚀 Project Overview
- **Load & inspect** raw financial market dataset (CSV → pandas DataFrame).  
- **Clean & validate** datatypes, handle missing values, and standardize timestamps.  
- **Explore**:
  - Categorical distributions (`value_counts`, `nunique`)  
  - Numerical relationships (`corr`)  
- **Visualize**:
  - Heatmaps, scatterplots, pairplots, and bar charts (using pandas, matplotlib, seaborn).  
- **Aggregate**:
  - Grouped summaries with `groupby`, `sum`, `mean`, and `max`  
- **Deliverables**:
  - Key findings from EDA  
  - Insights prepared for downstream BI tools (Tableau / Power BI) or machine learning  

---

## 🛠 Tech Stack
- **Python** (pandas, numpy)  
- **Visualization**: matplotlib, seaborn  
- **Data Source**: CSV file(s) with financial market attributes  

---

## 📊 Results & Takeaways
- Systematic cleaning and inspection of missing values & datatypes.  
- **Categorical analysis** revealed key distributions in financial attributes.  
- **Correlation analysis** identified strong linear relationships between features.  
- Visual exploration (heatmaps, scatterplots, pairplots) provided intuitive insights into patterns and dependencies.  
- Grouped aggregations supported **category-level comparisons** across entities.  

---

## 🧰 Functions & Methods Used
### Data Loading & Cleaning
- `pd.read_csv()`, `pd.to_datetime()`, `df.info()`, `df.isnull()`
### Exploration
- `df.head()`, `df.nunique()`, `df.value_counts()`, `df.corr()`, `df.sort_values()`
### Aggregation
- `groupby()`, `sum()`, `mean()`, `max()`
### Visualization
- `df.plot(kind=...)`, `plt.figure()`, `plt.subplot()`, `plt.show()`
- `sns.heatmap()`, `sns.pairplot()`, `sns.scatterplot()`, `sns.barplot()`

---

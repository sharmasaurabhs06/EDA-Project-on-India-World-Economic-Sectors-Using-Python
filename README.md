# 📊 India & World Economic Sectors — Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on economic data covering GDP, employment, and growth rates across multiple countries, sectors, and years.

The analysis uses **Python, Pandas, NumPy, Matplotlib, and Seaborn** to clean the data, perform statistical analysis, identify patterns, and generate business insights.

---

## 🎯 Objectives

* Analyze GDP performance across countries and sectors
* Study employment and economic growth patterns
* Identify GDP trends over different years
* Compare country and sector performance
* Analyze relationships between GDP, employment, and growth
* Detect missing values, duplicates, and outliers
* Generate meaningful business insights through visualization

---

## 📂 Dataset

The dataset contains **15,000 records** covering:

* **8 Countries:** India, China, USA, Germany, France, UK, Brazil, Japan
* **3 Sectors:** Agriculture, Manufacturing, Services
* **Years:** 2010–2023

### Main Columns

| Column             | Description               |
| ------------------ | ------------------------- |
| `Country`          | Country name              |
| `Sector`           | Economic sector           |
| `Year`             | Year of observation       |
| `GDP_Value_USD_Bn` | GDP value in USD billions |
| `Employment_%`     | Employment percentage     |
| `Growth_Rate_%`    | Growth rate percentage    |

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning

The following data-cleaning activities were performed:

* Checked missing values
* Checked duplicate records
* Removed extra spaces from column names
* Converted employment percentages into numeric values
* Converted growth rate into numeric format
* Handled missing values in employment and growth-rate columns
* Checked data types after transformation
* Performed outlier detection using the **IQR method**

---

## 📈 Exploratory Data Analysis

The project analyzes:

### Country-Level Analysis

* Total GDP by country
* Average GDP by country
* Average employment by country
* Average growth rate by country

### Sector-Level Analysis

* Total GDP by sector
* Average GDP by sector
* Average employment by sector
* Average growth rate by sector

### Year-Level Analysis

* Total GDP by year
* Minimum and maximum GDP by year
* GDP trend over time

---

## 📊 Visualizations

The notebook includes **11 different visualizations**:

1. Bar Chart
2. Pie Chart
3. Histogram
4. Histogram with KDE
5. Box Plot
6. Scatter Plot
7. Line Plot
8. Count Plot
9. Correlation Heatmap
10. Pair Plot
11. Violin Plot

These visualizations were used to understand GDP distribution, sector patterns, country performance, and relationships between variables.

---

## 🔍 Advanced Analysis

The project also includes:

* Top and bottom countries by GDP
* Highest and lowest performing sectors
* Country with maximum/minimum employment
* GDP trends over years
* Sector-wise and country-wise pivot tables
* Country-sector cross-tabulation
* Correlation analysis
* IQR-based outlier detection
* Missing-value analysis
* Sector performance comparison

---

## 💡 Key Business Insights

According to the analysis:

* **India** leads in total GDP among the countries in the dataset.
* **Manufacturing** has the highest average GDP.
* **Agriculture** employs the largest workforce share but has the slowest growth.
* The **UK** has the strongest average growth rate.
* GDP reached its highest point around **2011** and its lowest point around **2020**.
* Employment share does **not necessarily indicate higher GDP**.
* No significant meaningful correlations were identified among the main numeric variables.
* No GDP outliers were detected using the IQR method.

---

## ⚠️ Limitations

* Missing values were filled using statistical imputation, which may reduce natural variation.
* The dataset does not show strong meaningful correlations between variables.
* No significant outliers were detected.
* The dataset may be **synthetic**, so the findings should primarily be considered as an **EDA practice project** rather than real-world economic research.

---

## 🚀 Future Scope

Future improvements could include:

* GDP forecasting using time-series techniques
* Adding inflation and trade-related indicators
* Country-sector level growth analysis
* Building an interactive **Power BI dashboard**
* Applying the analysis to reliable real-world economic datasets
* Developing predictive models for GDP and economic growth

---

## 📁 Project Structure

```text
India-World-Economic-Sectors-EDA/
│
├── EDA_Project.ipynb
├── EDA_Project_india_world_economic_sectors.csv
└── README.md
```

---

## 👨‍💻 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | EDA | Statistical Analysis | Data Visualization | Business Insights | Outlier Detection | Correlation Analysis**

---

## ⭐ Project Summary

This project demonstrates an end-to-end **Exploratory Data Analysis workflow**, starting from data loading and cleaning to statistical analysis, visualization, advanced EDA, and business insights using Python.

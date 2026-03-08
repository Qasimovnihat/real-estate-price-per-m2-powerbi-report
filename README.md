# Real Estate Sales & Price per m² Report (Power BI)

This project is an end-to-end real estate analytics workflow built using a Kaggle dataset.  
The goal is to transform raw housing sales data into clean, analysis-ready data and present key insights through an interactive **Power BI report/dashboard** focused on **sales performance and price per m²**.

---

## Project Overview

This project covers:

- data cleaning and preprocessing in **JupyterLab (Python)**
- exploratory data analysis (EDA) using **Seaborn** and **Matplotlib**
- interactive reporting and visualization in **Power BI**

The final output is a Power BI dashboard titled: **“Real Estate Sales & Price per m² Dashboard”**.

---

## Tools & Technologies

- **Python (JupyterLab)** — data cleaning & preprocessing  
- **Pandas / NumPy** — handling missing values, duplicates, formatting  
- **Seaborn / Matplotlib** — exploratory data analysis and visualization  
- **Power BI** — report/dashboard development  
- **GitHub** — project documentation and sharing  

---

## Dataset

- **Source:** Kaggle (Real Estate / Housing Sales dataset)  
- The dataset contains property information such as:
  - location
  - bedrooms
  - bathrooms
  - area type
  - pricing and sales-related fields

> Note: The dataset was downloaded from Kaggle and used for educational/portfolio purposes.

---

## Data Cleaning (JupyterLab)

Key cleaning steps performed:

- removed duplicate rows
- handled missing values (nulls)
- fixed incorrect/empty values
- formatted columns into correct data types (numeric, categorical, etc.)
- filled missing values using **mean** and **median** depending on distribution
- ensured consistency for analysis and reporting

---

## Exploratory Data Analysis (EDA)

After cleaning, EDA was performed using **Seaborn** and **Matplotlib** to explore:

- price distribution and outliers
- average price per m² across bedroom counts
- relationship between area type and sales share
- top locations by average price per m²
- homes sold patterns by bedrooms and bathrooms

---

## Power BI Dashboard

The cleaned dataset was exported and imported into Power BI to build an interactive dashboard.

### Dashboard Highlights

- **Total Revenue**
- **Total Homes Sold**
- **Average Price per m²**
- **Top 10 Locations by Average Price per m²**
- **Average Price per m² by Bedrooms**
- **Sales Share by Area Type**
- **Homes Sold by Bedrooms**
- **Homes Sold by Bedrooms and Bathrooms (heatmap-style matrix)**

---

## Key Insights (Example)

- Certain locations consistently show significantly higher average price per m².
- Larger bedroom properties tend to have higher price per m², but demand (homes sold) may peak in mid-range bedrooms.
- Sales share differs notably by area type, indicating buyer preference differences across property types.

---
## Dashboard Preview
https://app.powerbi.com/view?r=eyJrIjoiMTlkNGEyNTgtN2Q0MC00OWZkLWE3ZDktYmUxYTA0MzA3YmZkIiwidCI6ImZkYTYyMDk1LWI3ZGQtNGNjOS05MTIwLWZkMDYzODg5Y2Q0OCIsImMiOjl9



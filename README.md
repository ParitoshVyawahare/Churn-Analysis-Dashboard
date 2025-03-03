## Dashbord View
![image](https://github.com/user-attachments/assets/94125e5a-578f-4556-b8b4-f143f258c423)

**Link**: (https://app.powerbi.com/groups/me/reports/954bc837-44cc-4e2c-8e0a-ba43d3e919ba/4a297085e02a5d693ded?experience=power-bi)


# Churn Analysis Project using SQL Server, Power BI & Python

## Project Overview
This project focuses on **Churn Analysis** using **SQL Server, Power BI, and Python**. It covers the complete data pipeline, from **ETL processing, data cleaning, and visualization** to **building a predictive machine learning model**. The final output includes an interactive Power BI dashboard that provides insights into customer churn patterns and predicted churners.

## Data Workflow
![image](https://github.com/user-attachments/assets/ad28ecfb-6c59-441b-a6af-e1fc6d31cc64)


## Key Steps in the Project

### 1. ETL Process in SQL Server
- Imported raw customer data from a **CSV file** into **SQL Server** using the Import Wizard.
- Utilized **SQL Server Integration Services (SSIS)** for efficient data transformation and loading into the data warehouse.
- Ensured data consistency and integrity before processing further.

### 2. Data Cleaning in SQL Server
- Handled missing values and outliers using **SQL queries**.
- Standardized column formats and removed duplicates.
- Used **JOIN operations** to merge necessary data from different tables.
- Created views and stored procedures for optimized querying.

### 3. Power BI Transformations (Use of DAX Formulas)
- Applied **Power Query Editor** for additional data transformations.
- Created calculated columns and measures using **DAX (Data Analysis Expressions)** to enhance analysis.
- **Key DAX formulas used:**
  - `CALCULATE()`: Applied filters dynamically for churn rate calculations.
  - `SUMX()`: Aggregated customer lifetime value across different segments.
  - `RANKX()`: Ranked high-risk churn customers based on probability scores.
  - `IF() / SWITCH()`: Defined customer churn classification logic.

### 4. Power BI Visualization & Enhancing Visuals
- Built **interactive dashboards** showcasing:
  - Churn trend analysis over time.
  - Customer demographics affecting churn.
  - Revenue loss due to churn.
  - Geographic and segmentation-based churn heatmaps.
- Used **custom visuals** such as tree maps, slicers, and KPIs to enhance insights.

### 5. Machine Learning Model: Random Forest in Jupyter Notebook
- Processed customer behavioral and demographic data.
- Implemented **Random Forest** classifier to predict churn probability.
- Achieved high accuracy by **hyperparameter tuning** and feature selection.
- Exported predictions back to SQL Server for visualization.

### 6. Visualizing Predicted Data in Power BI - Predicted Churner Profile
- Integrated **predicted churn labels** from the machine learning model into Power BI.
- Developed **churner persona profiles** to understand characteristics of high-risk customers.
- Enabled dynamic filtering based on prediction confidence scores.

## Technologies & Tools Used
- **SQL Server (SSMS, SSIS)** for ETL & Data Cleaning
- **Power BI** for Data Visualization & Dashboarding
- **DAX (Data Analysis Expressions)** for advanced analytics
- **Python (Jupyter Notebook)** for Machine Learning
- **Random Forest Classifier** for churn prediction

## Results & Insights
- Successfully identified key factors influencing customer churn.
- Created a predictive model with **high accuracy**, enabling proactive retention strategies.
- Provided business stakeholders with a **data-driven approach** to reduce churn and improve customer engagement.

---

### 🚀 How to Use This Project
1. Clone this repository.
2. Set up **SQL Server** and import data using provided scripts.
3. Open the Power BI dashboard to explore insights.
4. Run the Jupyter Notebook to train and predict churn outcomes.

## 📩 Contact & Contributions
If you have any suggestions or improvements, feel free to contribute or reach out!

---

### 🔗 Connect with Me
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/paritosh2712/)
- **GitHub**: [Your GitHub Profile](https://github.com/ParitoshVyawahare?tab=repositories)
- 

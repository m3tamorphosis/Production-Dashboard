# 📊 Production Data Analysis Dashboard (Excel)
<img width="1107" height="723" alt="image" src="https://github.com/user-attachments/assets/08020d50-6f28-406d-a766-62055f16342a" />
## 📌 Overview
This project demonstrates an end-to-end **data analysis workflow using Microsoft Excel**, covering data cleaning, transformation, analysis, and dashboard creation. The goal is to convert raw production data into meaningful insights through structured preprocessing and interactive visualizations.

---

## 🗂 Dataset Description
The dataset contains production-related information with the following fields:

- **ProductionID** – Unique identifier for each production record  
- **ProductionDate** – Date of production  
- **Region** – Production region  
- **Manager** – Assigned production manager  
- **ProductType** – Type of product produced  
- **UnitsProduced** – Total number of units produced  
- **TotalCost** – Total production cost  
- **Gender** – Gender classification  
- **True Age** – Actual age of the individual  
- **Age Group** – Categorized age group  
- **Production Cost Per Unit** – Cost per produced unit  

---

## 🧹 Data Cleaning & Preparation
The following steps were performed to clean and prepare the data:

- Removed **null and missing values**
- Eliminated **duplicate records**
- Standardized column formats and values
- Verified data consistency across all fields

---

## 🔄 Data Transformation
Several calculated and derived columns were added:

### ✅ Age Group Classification
Age groups were created using conditional logic:
- **A1** – Age ≤ 35  
- **A2** – Age ≤ 45  
- **A3** – Age > 45  

### ✅ Production Cost Per Unit
A new column was calculated:


### ✅ Lookup Enhancement
- Used **VLOOKUP** to retrieve and validate the exact age
- Applied filtering to analyze lower age groups where needed

---

## 📊 Data Analysis & Visualization
- Created **Pivot Tables** to summarize production performance
- Developed multiple **charts** for trend and comparison analysis
- Designed a structured **Excel dashboard**

---

## 🎛 Dashboard Features
- Interactive **slicers** for filtering data
- Slicers synchronized across **all dashboard charts**
- Dynamic updates based on selected filters
- Clear layout for easy interpretation of production insights

---

## 🛠 Tools & Skills Used
- Microsoft Excel  
- Data Cleaning & Validation  
- Conditional Logic (IF statements)  
- VLOOKUP  
- Pivot Tables & Pivot Charts  
- Dashboard Design  
- Slicers & Filter Synchronization  

---

## 📈 Key Insights
This dashboard enables:
- Comparison of production output by region and product type
- Cost efficiency analysis using cost-per-unit metrics
- Age group–based production analysis
- Interactive exploration of production trends

---

## 🚀 Conclusion
This project showcases practical **Excel data analytics skills**, from raw data handling to dashboard development. It is suitable for demonstrating proficiency in data preparation, analysis, and visualization for entry-level **Data Analyst** roles.




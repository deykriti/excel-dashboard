# Bike Sales Analysis Dashboard – Excel Project

![Excel](https://img.shields.io/badge/Tool-Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Skills](https://img.shields.io/badge/Skills-Data%20Cleaning-blue)
![Analysis](https://img.shields.io/badge/Data%20Analysis-Completed-green)
![Dashboard](https://img.shields.io/badge/Dashboard%20Visualization-Interactive-yellow)
![Status](https://img.shields.io/badge/Project%20Status-Completed-brightgreen)

## 1. Project Overview

This project involved analyzing bike sales data using Excel to uncover customer trends and visualize results for better business insights. The key objectives were to clean and process the raw data, standardize field values, segment customers by relevant criteria such as age and region, and build an interactive dashboard for clear visualization and decision-making.

---

## 2. Objectives

- Clean and preprocess raw sales dataset  
- Standardize categorical text fields  
- Create derived feature for customer age segmentation  
- Build interactive Excel dashboard using PivotCharts  
- Analyze factors impacting bike purchasing behavior  

---

## 3. Data Preparation & Cleaning

### Cleaning Steps Performed:

| Task | Description |
|---|---|
| Removed Duplicates | Ensured no duplicate customer records |
| Standardized Gender | M → Male, F → Female |
| Standardized Marital Status | M → Married, S → Single |
| Fixed Region / Education | Normalized inconsistent entries |
| Handled Missing Values | Fixed blanks, cleaned null entries |

### Created New Feature – Age Bracket

```excel
=IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescence","Invalid")))


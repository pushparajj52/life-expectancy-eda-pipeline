# Life Expectancy EDA

## Overview
This notebook performs **Exploratory Data Analysis (EDA)** on the Life Expectancy dataset to understand data distribution, detect issues, and extract meaningful insights.

---

## Dataset
- **Name:** Life Expectancy Dataset  
- **Description:** Contains health, economic, and demographic factors influencing life expectancy across countries.

---

## Objectives
- Understand dataset structure and features  
- Perform data sanity checks  
- Identify missing values and outliers  
- Visualize distributions and relationships  
- Prepare data for further analysis  

---

## Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  
- Inspected initial structure using `.head()`, `.info()`, `.describe()`

### 2. Sanity Check
- Checked for:
  - Missing values  
  - Data types  
  - Duplicate entries  

### 3. Data Cleaning
- Handled missing values  
- Treated outliers using statistical methods  
- Standardized column formats  

### 4. Exploratory Analysis
- **Histograms** → Understand feature distributions  
- **Boxplots** → Detect outliers  
- Feature-wise analysis of key variables  

---

## Key Features Analyzed
- Life expectancy  
- GDP  
- Adult Mortality  
- BMI  
- Schooling  

---

## Outputs
- Visualizations generated within notebook  
- Insights derived from feature distributions and relationships  

---

## How to Run
```bash
jupyter notebook eda.ipynb

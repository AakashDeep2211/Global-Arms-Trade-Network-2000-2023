# 🌍 SIPRI Arms Trade Analysis (2000-2023)

This project analyzes the **global arms trade network** from **2000 to 2023**, using data exploration, wrangling, and visualization techniques. The objective is to extract insights into trade patterns, quantities, and country-specific trends.

---

## 📊 Dataset Information
- **Total Records:** 10,520 rows  
- **Columns:** 15  
- **Data Types:**  
  - **DateTime variables:** 2 (`Order Date`, `Delivery Date`)  
  - **Continuous variables:** 3  
  - **Discrete Count variables:** 4  
  - **Discrete Categorical variables:** 6  
- **Missing Values:**  
  - `Quantity`, `OrderYrEst` contain **null values**  
- **Skewness:**  
  - `Quantity` column is **right-skewed**  

---

## 🛠️ Libraries Used
- `pandas` → Data manipulation and cleaning  
- `numpy` → Numerical operations  
- `seaborn` → Data visualization  
- `matplotlib` → Plotting charts  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ **Data Exploration**
- **Dataset Shape:** `10520 rows × 15 columns`  
- **DateTime Correction:**  
    - Converted `Order Date` and `Delivery Date` to correct **datetime format**.  
- **Missing Values:**  
    - `Quantity` and `OrderYrEst` contain **null values**.  

### 2️⃣ **Variable Analysis**
- **Id & Trade_id Columns:**  
    - All values are of `int` dtype with no missing values.  
- **Quantity Column:**  
    - Contains **missing values**.  
    - **Right-skewed** distribution.  
- **Target Column:**  
    - Contains **categorical values**.  

---

## 🔥 Key Observations
✅ **Date columns** were initially in incorrect format and were cleaned.  
✅ The `Quantity` column shows a **right-skewed** distribution.  
✅ Some columns contain **null values**, which were handled appropriately.  
✅ The dataset includes a variety of data types, enabling diverse analyses.  

---

## 📈 Data Wrangling & Cleaning
- **Converted date columns** to `datetime` format.  
- **Replaced null values** in the `Quantity` and `OrderYrEst` columns with appropriate strategies.  
- Verified **data types** for accuracy.  

---

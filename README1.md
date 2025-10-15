# US Debt Tracker Project

**Author:** Joel Martin  
**GitHub:** [JoelMartinm](https://github.com/JoelMartinm)  
**Tool:** Microsoft Excel  

---

## Project Overview

The **US Debt Tracker Project** is an Excel-based data analysis portfolio project that examines how the **United States Total Public Debt Outstanding** has evolved from 2000 to 2025.  

This project demonstrates skills in **data cleaning, transformation, growth rate calculation, forecasting**, and **visualization** using Excel.

---

##  Dataset Description

- **Source:** [U.S. Treasury Fiscal Data](https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/debt-to-the-penny)  
- **Time Period:** 2000 – 2025  
- **Frequency:** Daily (aggregated to yearly)  
- **Fields:**
  - Record Date  
  - Debt Held by the Public  
  - Intragovernmental Holdings  
  - Total Public Debt Outstanding  

---

##  Data Cleaning & Preparation

**Steps performed:**

1. Transposed and pasted raw data into a new sheet called `Cleaned Data`.
2. Selected all blanks and deleted them.
3. Replaced all `null` values with empty strings (`''`).
4. Converted numbers in scientific notation to standard numeric format.
5. Aggregated daily data into yearly summaries.
6. Attempted pivot tables but opted to clean and organize data manually due to formatting issues.

This ensures the dataset is **consistent, clean, and ready for analysis**.

---

## Key Analyses

### 1. How has the US Total Public Debt changed year by year?

- Calculated **yearly percentage growth** of Total Public Debt Outstanding.  
- Built a line chart to visualize trends from 2000 to 2025.

**Insight:**  
From 2016–2019, the average increase in total public debt was around 5%. In 2020, a sharp spike occurred, likely due to **pandemic-related government spending**.  

<img width="741" height="481" alt="image" src="https://github.com/user-attachments/assets/24ac4615-9b27-4867-a307-4e67af7214a4" />
*Figure 1: Yearly Percentage Growth of US Total Public Debt*

---

### 2. Which months historically see the highest and lowest debt increases?

- Aggregated debt changes by month to identify **seasonal trends**.  
- Visualized using column charts.

**Insight:**  
- **Highest increases:** January, February, November, December.  
- **Lowest increases:** May, June, July.  

**Hypothesis:** High months coincide with major US holidays (e.g., Thanksgiving, Christmas) when spending and debt accumulation increase. Low months have no significant holidays, resulting in lower debt.  

<img width="970" height="545" alt="image" src="https://github.com/user-attachments/assets/d8e7c775-ff10-49f1-b113-69abe49fabc6" />
*Figure 2: Monthly Increases in US Total Public Debt*

---

### 3. What is the projected growth of publicly held debt?

- Applied **forecasting techniques** in Excel to estimate future debt trends.  

**Summary:**  
- From 1997–2007: debt increased ~1 Trillion USD.  
- From 2008–2019: debt rose from 6 Trillion to 17 Trillion USD.  
- From 2020–2022: debt increased from 21.5 Trillion to 25 Trillion USD.  
- Projected 2023–2027: debt expected to reach 33 Trillion USD.  

**Conclusion:** Publicly held debt is expected to grow steadily over the next 5 years. Further analysis could explore correlations with **stock market trends, housing market, credit card usage, and unemployment rates**.  

<img width="751" height="452" alt="image" src="https://github.com/user-attachments/assets/f4d689a5-0e48-4885-a533-8d1f26838a05" />

*Figure 4: Forecasted Growth of Publicly Held Debt*

---

##  Skills Demonstrated

- Excel **Data Cleaning & Transformation**  
- **Aggregation & Pivoting**  
- **Charting & Dashboard Design**  
- Forecasting and trend analysis  
- Data storytelling and interpretation  

---

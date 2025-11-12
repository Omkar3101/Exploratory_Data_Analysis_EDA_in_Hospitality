# **Exploratory Data Analysis (EDA) in Hospitality for Atliq Hotels**
---

### **Table of Contents**
1.  [**Project Overview**](#project-overview)
2.  [**Problem Statement**](#problem-statement)
3.  [**Tools & Technologies Used**](#tools--technologies-used)
4.  [**Data Exploration & Cleaning**](#data-exploration--cleaning)
5.  [**Ad-Hoc Insights Generation**](#ad-hoc-insights-generation)
6.  [**Key Learnings**](#key-learnings)
7.  [**Acknowledgements**](#acknowledgements)

---

### **Project Overview**

This project is an Exploratory Data Analysis (EDA) conducted for **Atliq Hotels**, a fictional hotel chain with a 20-year history and a strong presence across major cities in India. The analysis was performed as part of the Codebasics Data Analytics Bootcamp to simulate real-world challenges faced by the hospitality industry.

The primary goal was to dive deep into Atliq Hotels' booking data, which is spread across multiple sources, to uncover trends, identify issues, and provide actionable insights to address declining revenue and market share.

---

### **Problem Statement**

Atliq Hotels is losing revenue and market share to its competitors. To combat this, the management has decided to adopt a data-driven culture and has tasked the data analytics team with the following objective:

> **Analyze the booking data to provide actionable insights that will help the company regain its market position and drive growth.**

This involves answering a series of ad-hoc business questions posed by stakeholders to understand performance at a granular level.

---

### **Tools & Technologies Used**

*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **IDE:** VS Code with Jupyter Notebook

---

### **Data Exploration & Cleaning**

The analysis began with five separate CSV files containing information about hotels, rooms, dates, and booking transactions.

*   `dim_date.csv`
*   `dim_hotels.csv`
*   `dim_rooms.csv`
*   `fact_aggregated_bookings.csv`
*   `fact_bookings.csv`

The initial steps involved a rigorous data cleaning and transformation process:
1.  **Data Loading:** All CSV files were loaded into Pandas DataFrames.
2.  **Handling Missing Values:** Null values were identified and treated appropriately to ensure data integrity.
3.  **Correcting Data Types:** Data types of columns were corrected for accurate calculations.
4.  **Data Merging:** The separate DataFrames were merged into a single, clean master dataset, creating a solid foundation for analysis.

---

### **Ad-Hoc Insights Generation**

To simulate a real-world business environment, a series of ad-hoc questions were addressed using the cleaned dataset. Below are the key business questions and the insights derived from the analysis:

**1. What is the average occupancy rate in each room category?**
   *   **Insight:** 'Elite' rooms have the highest average occupancy (65%), indicating high popularity, while 'Presidential' suites have a lower rate (35%), as expected for a premium category.

**2. What is the average occupancy rate per city?**
   *   **Insight:** Delhi and Mumbai lead with over 60% average occupancy, suggesting stronger market presence or higher demand compared to Hyderabad (52%).

**3. When is the occupancy better: Weekday or Weekend?**
   *   **Insight:** Weekend occupancy (72%) is significantly higher than weekday occupancy (51%), highlighting a strong leisure travel segment.

**4. What was the occupancy for different cities in the month of June?**
   *   **Insight:** In June, Mumbai had the highest occupancy (68%), likely driven by summer travel, while Hyderabad was the lowest (45%).

**5. How can we append new data (e.g., for August) to the existing dataset?**
   *   **Process:** The new CSV data can be read into a DataFrame and appended to the master dataset using `pandas.concat`, allowing for continuous analysis.

**6. What is the revenue realized per city?**
   *   **Insight:** Mumbai generates the highest revenue, followed by Delhi, directly correlating with their higher occupancy rates.

**7. What is the month-by-month revenue trend?**
   *   **Insight:** A line chart revealed revenue peaks in high-travel months (May, July) and a noticeable dip in June, which requires further investigation.

**8. What is the revenue realized per hotel type?**
   *   **Insight:** The luxury properties, 'Atliq Palace' and 'Atliq Exotica', are the primary revenue drivers, contributing over 60% of the total revenue.

**9. What is the average rating per city?**
   *   **Insight:** Ratings are consistent across cities (around 3.8/5), indicating a system-wide opportunity to improve customer satisfaction and push the average rating above 4.

**10. What is the revenue share per booking platform?**
    *   **Insight:** A pie chart revealed a heavy reliance on third-party platforms like 'Make My Trip' (65% of revenue), while direct bookings via the Atliq website are low (15%). This points to a major concern regarding high commission payouts.

---

### **Key Learnings**

This project provided hands-on experience in:
*   Performing end-to-end Exploratory Data Analysis (EDA).
*   Data cleaning, transformation, and merging techniques using Pandas.
*   Translating ad-hoc business questions into data queries and visualizations.
*   Deriving actionable insights from raw data to support strategic decision-making.
*   Presenting complex data in a clear and understandable manner.

---

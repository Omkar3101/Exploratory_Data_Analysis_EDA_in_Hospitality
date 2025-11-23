# **Exploratory Data Analysis (EDA) for Revenue Optimization**

### **[🔗 View Project Notebook](#)** *(Paste your notebook/blob link here)*

---

### **Project Overview**

Conducted a **diagnostic analysis** on a large hospitality dataset for AtliQ Hotels to identify **revenue leakage points** and **optimize booking strategies**. This project addresses a critical decline in market share by leveraging **statistical methodologies** to analyze customer behavior, cancellation trends, and channel performance.

The goal was to move beyond basic descriptive statistics to provide **strategic, data-driven recommendations** aimed at increasing **Revenue Per Available Room (RevPAR)** and operational efficiency.

---

### **Business Problem**

AtliQ Hotels, a luxury hotel chain in India, faced a significant loss in revenue and market share due to fierce competition and ineffective management decisions. The management lacked a data-driven culture to identify:
*   **High Cancellation Rates:** Leading to unpredictable revenue streams.
*   **Platform Dependency:** Over-reliance on third-party booking platforms charging high commissions.
*   **Inefficient Pricing:** Lack of dynamic pricing strategies for weekends vs. weekdays.

**Objective:** To clean, transform, and analyze booking data to engineer features that reveal **customer friction points** and formulate strategies to regain market dominance.

---

### **Strategic Business Impact**

This analysis delivered the following actionable outcomes:

*   **Revenue Optimization:** Identified a strategic opportunity to implement **dynamic pricing**, capitalizing on the 72% weekend occupancy rate vs. 51% on weekdays.
*   **Cost Reduction Strategy:** Uncovered a heavy reliance on 3rd party platforms (65% revenue share). Proposed a "Direct Booking Incentive" program to reduce commission payouts.
*   **Customer Acquisition:** Engineered **3 new features** to segment customers, enabling targeted marketing campaigns for underperforming cities like Hyderabad.
*   **Projected Impact:** Formulated recommendations projected to potentially **increase RevPAR by 5-10%** within the next fiscal quarter.

---

### **Technical Implementation & Statistical Methodologies**

*   **Data Cleaning & Pre-processing:** Applied statistical techniques to handle missing values (imputation) and outliers across 5 disparate datasets (`dim_date`, `dim_hotels`, `dim_rooms`, `fact_aggregated_bookings`, `fact_bookings`).
*   **Feature Engineering:** Created **3 new features** (e.g., `revenue_per_booking`, `day_type`, `booking_status_category`) to enable deeper granular analysis of booking patterns.
*   **Data Transformation:** Merged and consolidated raw data into a single master dataset using `pandas.merge` and `concat` for holistic analysis.
*   **Diagnostic Analysis:** Utilized grouping and aggregation to diagnose the root causes of revenue dips in specific months (e.g., June).

---

### **Key Insights & Analysis**

The analysis answered critical business questions to drive strategy:

**1. Occupancy & Pricing Dynamics**
*   **Insight:** Weekend occupancy (72%) significantly outperforms weekdays (51%).
*   **Recommendation:** Implement **dynamic pricing models** to maximize yield during weekends and introduce corporate packages to boost weekday occupancy.

**2. Revenue Leakage via Platforms**
*   **Insight:** Third-party platforms (e.g., MakeMyTrip) contribute **65% of revenue**, eroding margins through commissions. Direct website bookings are only 15%.
*   **Recommendation:** Launch a loyalty program for direct bookings to improve **Net Revenue Retention**.

**3. Product Performance**
*   **Insight:** 'Elite' rooms drive the highest occupancy (65%), while 'Presidential' suites lag (35%).
*   **Recommendation:** Re-evaluate pricing or introduce upgrade offers for premium suites to optimize inventory utilization.

**4. Geographical Performance**
*   **Insight:** Mumbai generates the highest revenue, while Hyderabad lags significantly behind in both occupancy and revenue.
*   **Recommendation:** targeted local marketing campaigns required for the Hyderabad market.

---

### **Tools & Technologies Used**

*   **Python:** Core language for analysis.
*   **Pandas & NumPy:** Data Manipulation, Feature Engineering, and Statistical Aggregation.
*   **Matplotlib & Seaborn:** Data Visualization to identify trends and outliers.
*   **Jupyter Notebook:** Interactive environment for documentation and code execution.

---

### **Connect with Me**

If you found this project insightful or want to discuss data, technology, and new opportunities, feel free to connect with me on my professional platforms:

- 💼 **LinkedIn:** [**Omkar Sharma**](https://www.linkedin.com/in/omkar3101)
- 📂 **Portfolio:** [**My Portfolio**](https://rhinestone-dibble-6c6.notion.site/Omkar-Sharma-2a56733b537c800db9ebe11314a946b5)
- 💻 **GitHub:** [**@Omkar3101**](https://github.com/Omkar3101)

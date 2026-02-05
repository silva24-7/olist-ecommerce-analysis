# Olist E-Commerce Data Analysis

## 📌 Project Overview
This project analyzes a dataset of **100k+ orders** from Olist Store (a Brazilian marketplace) between 2016 and 2018.

**Data Source:** The dataset used in this project is public and available on [Kaggle: Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

The main objective is to evaluate **Sales Performance**, **Logistics Efficiency**, and **Customer Satisfaction** to identify why some high-selling categories suffer from low ratings. The final output is an automated dashboard for stakeholders to monitor daily operations.

### 🚀 Interactive Dashboard

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/d81f84ae-8af9-408f-a07e-9121795c4e8c" />

**[👉 Click Here to View the Looker Studio Dashboard](https://lookerstudio.google.com/reporting/c82ae7bc-2add-428a-b8ac-43835c7472a7)**

---

## ❓ Business Problem
Olist faces a challenge where high sales volume does not always correlate with high customer retention. The management needs to understand:
1.  Which product categories drive the most revenue vs. which ones cause the most complaints?
2.  How does delivery time impact customer review scores?
3.  When are the peak shopping hours to optimize marketing campaigns?

---

## 📊 Key Insights & Findings
Based on the data analysis, here are the critical findings:

### 1. The "Volume vs. Quality" Paradox
* **Insight:** The category **"Bed_Bath_Table"** generates the highest sales volume but has a concerningly low average review score of **~3.8/5.0**.
* **Root Cause:** Analysis suggests that high order volume leads to quality control slips and packaging issues, resulting in higher return rates.

### 2. Logistics Bottlenecks
* **Insight:** The average delivery time is **12.01 days**. However, delivery to remote states like **Roraima (RR)** and **Pará (PA)** takes up to **25+ days**.
* **Correlation:** There is a strong negative correlation between delivery time and review score. Delays exceeding 12 days significantly increase the probability of receiving a **1-star review**.

### 3. Customer Behavior (Peak Time)
* **Insight:** The highest purchasing activity occurs on **Weekdays (Mon-Tue)** between **11:00 AM - 4:00 PM**.
* **Opportunity:** Weekend marketing spend shows a lower Return on Investment (ROI) compared to weekdays.

---

## 💡 Recommendations
1.  **Logistics:** Establish partnerships with local fulfillment centers in the **North Region** to reduce delivery time by at least 30%.
2.  **Quality Control:** Conduct a strict audit on sellers within the "Bed_Bath_Table" category to improve packaging standards.
3.  **Marketing Strategy:** Shift ad budget to focus on **Monday & Tuesday afternoons**, utilizing "Flash Sales" to convert high traffic into sales.

---

## 🛠️ Tools & Technologies
* **Python (Pandas & NumPy):** For Data Cleaning, Manipulation, and Aggregation.
* **Google Looker Studio:** For Data Visualization and Dashboarding.
* **Git/GitHub:** For Version Control.

## 📂 Project Structure
* `notebooks/`: Contains the Jupyter Notebook (`.ipynb`) with the full python code.
* `data/`: (Optional) Sample data or link to the Kaggle dataset.
* `README.md`: Project documentation.

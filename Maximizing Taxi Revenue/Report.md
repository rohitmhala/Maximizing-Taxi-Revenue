
# 🛺 Taxi Fare Analysis: Impact of Payment Methods on Revenue

## 📌 Problem Statement

In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness.

This project uses data-driven insights to **maximize revenue streams** for taxi drivers. It focuses on determining whether **payment methods** have an impact on **fare pricing**, specifically exploring the relationship between **payment type** and **fare amount**.

## ❓ Research Question

**Does the type of payment method influence the fare amount paid by taxi customers?**

## 📊 Data Overview

The dataset includes trip records with fields such as `passenger_count`, `trip_distance`, `payment_type`, `fare_amount`, and `duration`.

![Sample Data](./Screenshot%202025-08-01%20221600.png)

## 🔍 Methodology

- **Data Cleaning**: Removed nulls and filtered unrealistic fare/distance values.
- **Encoding**: Encoded payment types for numerical analysis.
- **Grouped Analysis**: Compared average fare amounts by payment type.
- **Visualization**: Created bar plots, pie charts, and histograms.
- **Hypothesis Testing**: Applied statistical tests to assess significance.

## 📈 Analysis & Findings

- **Payment Preference**: Most users prefer card payments (78%) over cash (22%).  
  ![Payment Preference Pie Chart](./Screenshot%202025-08-01%20221209.png)

- **Payment Type Comparison**: Card payments dominate across most fare bins.  
  ![Payment Type Bar Chart](./Screenshot%202025-08-01%20221146.png)

- **Fare and Distance Distributions**: Card payments are more common for longer trips and higher fares.  
  ![Distributions](./Screenshot%202025-08-01%20221128.png)

## 📊 Hypothesis Testing

- **Null Hypothesis (H0)**: No significant difference in fare amount across payment types.
- **Alternative Hypothesis (H1)**: Significant difference in fare amount across payment types.

Statistical tests (ANOVA, regression) confirm a significant relationship between payment type and fare amount.

## 💡 Recommendations

- Encourage card payments as they are linked to higher fare values.
- Train drivers to promote digital transactions.
- Include additional metrics like tip amount and ride location in future studies.

## 🛠️ Tech Stack

- Python (Pandas, Matplotlib, Seaborn, Statsmodels)
- Jupyter Notebook


## 👤 Author

**Rohit Mhala**  
Data Analyst | B.E. Data Science

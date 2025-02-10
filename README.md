# 🛒 A/B Testing: Conversion Rate Optimization  

## 📌 Project Overview  
This project analyzes an A/B test for an e-commerce company to determine whether a new landing page improves conversion rates compared to the old page.  

## 🎯 Hypothesis  
- **H₀ (Null Hypothesis):** The new page does NOT significantly improve conversion rates.  
- **H₁ (Alternative Hypothesis):** The new page significantly changes conversion rates.  

## 🛠 Methods Used  
- **T-Test** to compare the means of conversion rates.  
- **Chi-Square Test** to compare conversion proportions.  
- **Seaborn & Matplotlib** for visualization.  
## 📊 Visualizations  

## 📊 Dataset Description  

This dataset contains user interaction data from an **A/B test conducted by an e-commerce company**.  
The goal of this A/B test is to determine whether a **new landing page (treatment group)** improves conversion rates compared to the **old landing page (control group)**.  

### **🔹 Dataset Columns**  
| Column Name   | Description |
|--------------|------------|
| `user_id`    | Unique identifier for each user in the test |
| `timestamp`  | The time when the user interacted with the landing page |
| `group`      | The test group: **control** (old page) or **treatment** (new page) |
| `landing_page` | The actual page viewed: **old_page** or **new_page** |
| `converted`  | **1** = User converted (made a purchase, signed up, etc.), **0** = User did not convert |

### 1️⃣ Conversion Rate Comparison  
![Conversion Rate](conversion_rate_comparison.jpg)  

### 2️⃣  A/B Test Group Counts  
![A/B Group Comparison](ab_group_comparison.jpg)  

## 📈 Key Findings  
- **T-Test P-value:** 0.XX (> 0.05) → No significant difference.  
- **Chi-Square Test P-value:** 0.XX (> 0.05) → No significant difference.  
- **Business Decision:** The company should **keep the old page** since the new page does not improve conversions.  

## 🔗 Dataset  
- The dataset used is from Kaggle: [E-commerce A/B Testing Dataset](https://www.kaggle.com/datasets/putdejudomthai/ecommerce-ab-testing-2022-dataset1)  

## 📜 Notebook  
You can view the full Jupyter Notebook in this repository:  
[🔗 Click Here](./AB_Testing.ipynb)  

## 💡 Technologies Used  
✅ Python (`pandas`, `scipy.stats`, `seaborn`, `matplotlib`)  
✅ Jupyter Notebook  
✅ A/B Testing & Statistical Hypothesis Testing  

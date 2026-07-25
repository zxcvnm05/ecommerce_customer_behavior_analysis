# ecommerce_customer_behavior_analysis

## 📌 Executive Summary
This project investigates the factors driving a critical 50.5% product return rate across 5,000 e-commerce transactions. Through rigorous statistical hypothesis testing (ANOVA, Chi-Square, Pearson Correlation), the study debunks common operational assumptions and proposes targeted, data-backed interventions to protect profit margins.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, Seaborn, Matplotlib, SciPy
- **Statistical Tests:** Pearson Correlation, One-Way ANOVA, Chi-Square Test of Independence

## 📂 Project Structure
├── data/               # Transactional dataset (5,000 records)
├── notebooks/          # Data cleaning, outlier treatment (IQR), and statistical testing
├── outputs/            # Correlation heatmaps, category return charts, boxplots
└── README.md           # Project documentation

## 🚀 Key Results & Findings
- **Return Rate Risk:** Identified an overall **50.5% return rate**, with the "Beauty" category recording the highest risk (**52%**).
- **Debunked Assumption:** Delivery speed showed no statistically significant correlation with customer ratings ($r = -0.02, p = 0.14$), proving that product quality—not delivery speed—drives satisfaction.
- **Payment Risk:** High-value impulse transactions via instant payment methods correlated with higher return frequencies.

## 💼 Business Impact & Recommendations
- **Virtual AR Try-On:** Implement AR shade-matching for Beauty products to eliminate size/color mismatches.
- **Friction in Checkout:** Add confirmation steps for high-value UPI payments to curb impulse buys and reduce return volumes.

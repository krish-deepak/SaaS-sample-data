# SaaS Revenue Analysis: Correlation & Insights

This project performs **correlation analysis** and **insight discovery** for SaaS company revenue data. The focus is on understanding how different features influence company performance by comparing behavior across above-average and below-average revenue segments.

---

## 🎯 Project Objective

To analyze key performance metrics across SaaS companies and discover:

- How feature relationships differ between high and low performers
- Which metrics are most influential in determining ARR/MRR growth
- Actionable business insights from comparing feature correlations

---

## 🗂️ Project Files
- saas_revenue_analytics.ipynb # Main analysis notebook
- saas_revenue_dataset.csv # Dataset used in analysis
- README.md

---

## 📈 Key Analysis Performed

### 📊 Feature Correlation Comparison

- Separated companies into **above-average** and **below-average** revenue performers
- Computed correlation matrices for both groups
- Visualized and compared how feature relationships change between segments

This helps answer questions like:
- Does churn correlate differently with NPS in top-performing companies?
- Is marketing efficiency more predictive of growth in low performers?

---

## 🧠 Summary Insights

- **Top performers** often show stronger positive correlation between NPS and ARR.
- In **below-average** companies, churn and ARR have a stronger negative correlation.
- **Marketing spend** does not always lead to more subscribers in weaker segments — indicating diminishing returns or poor targeting.
- **Interaction terms** like churn × marketing or NPS × churn differ meaningfully across segments.

These insights can help business teams focus on the right levers for improving revenue performance.

---

## 📎 Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 🚀 How to Run

1. Clone this repository  
2. Open `saas_revenue_analytics.ipynb` in Jupyter  
3. Run all cells sequentially to reproduce the analysis and plots

---


# 🧪 A/B Test – Recommender System

This project analyzes the results of an A/B test for an improved recommender system in an eCommerce funnel. The goal was to evaluate conversion lift at key funnel stages using statistical testing and Python.

---

## 🎯 Objective

Determine whether the new recommender system leads to statistically significant improvements in:

- Product page views (`product_page`)
- Items added to cart (`product_cart`)
- Completed purchases (`purchase`)

---

## 🧠 Methodology

- Cleaned and merged raw data from 4 CSV files
- Calculated funnel conversion rates for control (A) and test (B) groups
- Performed exploratory analysis (EDA)
- Conducted a **Z-test for proportions** to assess statistical significance
- Identified funnel drop-offs and anomalies in user behavior

---

## 🛠️ Tools Used

- **Python**: Pandas · NumPy · Matplotlib · Seaborn  
- **Statistics**: Z-test for proportions (Scipy)  
- **Jupyter Notebook**: Full analysis pipeline

---

## 📁 Repository Structure

```bash
📁 data/              # Raw CSV files (not included here)
📁 notebooks/         # Jupyter notebook with full analysis
📁 src/               # Helper scripts (optional)
📄 README.md          # Project overview
📄 LICENSE            # MIT License

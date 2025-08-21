# 📊 Seaborn Basics — Data Visualization with Python

This repository contains a Jupyter Notebook (`seaborn-basics.ipynb`) that introduces the basics of **Seaborn**, a powerful Python visualization library built on top of Matplotlib.  

The exercise analyzes the **restaurant invoices and tips dataset** (`tips.csv`) and demonstrates how to create meaningful visualizations to explore data relationships.

---

## 🚀 Project Goals

- Learn the basics of **Seaborn** for statistical data visualization.  
- Explore the `tips` dataset and analyze customer behavior.  
- Practice creating different plots:
  - Countplots
  - Histograms & KDE plots
  - Categorical plots (bar, box, violin, boxen)
  - FacetGrid visualizations
  - Scatterplots, Jointplots, and Regression plots
  - Pairplots for correlation analysis  

---

## 📂 Dataset

We use the classic **Tips dataset** from Seaborn:  

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/mwaskom/seaborn-data/refs/heads/master/tips.csv")
df.head()

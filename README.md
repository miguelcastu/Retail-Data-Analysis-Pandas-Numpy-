# Retail Analysis — Pandas / NumPy Notebook

A historical notebook exercise for the fictional company RetailNow, exploring
store sales, inventory and satisfaction using three local CSV inputs. It shows
data cleaning, grouped metrics, descriptive statistics and a seeded simulation.

[Engineering portfolio](https://github.com/miguelcastu/miguelcastu) · [Project directory](https://github.com/miguelcastu/miguelcastu/blob/main/PROJECTS.md)

## Reproduce the notebook

Create a Python environment with Jupyter, Pandas and NumPy, launch Jupyter from
this repository root, and open `analisis_red_tiendas.ipynb`. Keep `sales.csv`,
`inventories.csv` and `satisfaction.csv` beside the notebook. Dependencies are not
locked; a fresh-kernel execution was not performed during this audit. Saved
outputs are historical artifacts, not independently verified business findings.

## Original notebook guide


# 📊 Retail Data Analysis with Pandas & Numpy

This repository contains a complete data analysis project for the fictional company **RetailNow**, implemented in a Jupyter Notebook.

---

## 🔍 Notebook Contents

### ✔ Data Loading & Cleaning
- CSV import  
- Removal of null values  
- Date conversion  
- DataFrame structure inspection  

### ✔ Core Analysis
- Total sales by store  
- Inventory rotation metrics  
- Critical inventory detection (<10%)  
- Customer satisfaction analysis  
- Statistical summaries with `describe()`

### ✔ Numpy Calculations
- Median of sales  
- Standard deviation  
- Random simulation of future sales  
- Use of seeds for reproducible results  

---

## 📁 Included Files
- `analisis_red_tiendas.ipynb`
- `sales.csv`
- `inventories.csv`
- `satisfaction.csv`

---

## ▶️ Requirements
```bash
pip install pandas numpy
```

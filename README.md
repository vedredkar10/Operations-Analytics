# Warehouse Optimization for 3PL Delivery Partners (Goa, India)

This project applies **Mixed Integer Linear Programming (MILP)** to optimize warehouse locations for last-mile delivery operations in Goa. It simulates real-world logistics for an Amazon-style network using real geographic and cost data.

---

## Problem Statement
Identify the best combination of warehouses that:
- Minimize overall delivery and setup costs
- Stay within a 40 km delivery radius
- Include staffing and rental overheads
- Account for multiple delivery truck types

---

## Tools & Techniques
- Python with **PuLP** (MILP Solver)
- Jupyter Notebook (Google Colab)
- Excel/CSV for cost matrices and demand data

---

## Project Files

| File Name | Purpose |
|-----------|---------|
| `DeliveryOpsFile.ipynb` | Python code implementing the MILP model |
| `Transport Cost Matrix.csv` | Distance-based cost per route |
| `Constituency Wise Demand.csv` | Monthly delivery demand per Goa constituency |
| `Transport Calculation Table.csv` | Aggregated costs for modeling |
| `warehouse Info Table.csv` | CapEx and OpEx data for each potential warehouse |
| `Operations_Report_Goa.pdf` *(Add this if you upload it)* | Final project write-up |

---

## Scenario Covered
- Demand spread across **40 constituencies**
- Testing impact of allowing 2, 3, 4, or 5 warehouses
- Output includes cost breakdown and warehouse selection per scenario

---

## 👤 Author
**Ved Redkar**  
MSc Business Analytics, Newcastle University  

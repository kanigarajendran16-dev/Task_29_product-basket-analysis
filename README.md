# 🛒 Product Basket Analysis – Veda Technology Task 29

## 📌 Project Overview

This project is completed as part of the **Veda Technology Data Analytics Internship – Task 29**.

The project focuses on **Product Basket Analysis**, where products purchased within the same order are analyzed to identify products that are frequently purchased together.

The analysis uses **Order IDs** to group products into transactions and performs association-style analysis to discover product relationships and generate product recommendations.

---

## 🎯 Objective

The main objectives of this project are:

- Identify frequently purchased products together
- Find the most common product pairs
- Perform association-style analysis
- Calculate Support, Confidence, and Lift
- Generate product recommendations
- Visualize purchasing patterns
- Build an interactive/live dashboard
- Export analysis results into downloadable files

---

## 🧰 Tools & Technologies

| Technology | Purpose |
|---|---|
| 🐍 Python | Data analysis and processing |
| 🐼 Pandas | Data cleaning and analysis |
| 🔢 NumPy | Numerical operations |
| 📊 Plotly | Interactive visualizations |
| 📈 Matplotlib | Data visualization |
| 🎛️ ipywidgets | Interactive dashboard controls |
| ☁️ Google Colab | Development environment |
| 📗 Excel | Analysis and report output |
| 🐙 GitHub | Project version control |

---

## 📂 Dataset

The project uses transaction-level product purchase data.

Important columns:

- **Order ID** – Identifies each customer transaction/order
- **Product** – Product purchased in the transaction

Each Order ID is treated as a single basket/transaction.

Example:

| Order ID | Product |
|---|---|
| ORD0001 | Milk |
| ORD0001 | Bread |
| ORD0001 | Butter |
| ORD0002 | Coffee |
| ORD0002 | Biscuits |

From this transaction structure, product combinations are generated.

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Order ID & Product Extraction
     ↓
Transaction Creation
     ↓
Product Combination Generation
     ↓
Product Pair Analysis
     ↓
Support Calculation
     ↓
Confidence Calculation
     ↓
Lift Calculation
     ↓
Top Product Pairs
     ↓
Product Recommendations
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Export Results

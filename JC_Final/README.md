# JC_Final: Final Model Refresh

**Author**: Jeana Codipilly  
**Date**: January 30, 2026  
**Project Type**: ERP Forecasting Model (Logistic Regression)  
**Status**: Finalized and tested in VS Code + Jupyter

---

## 📦 Project Overview

This notebook represents a structured refresh of a forecasting model using ERP-style datasets. It demonstrates how logistic regression can be applied to transactional data (orders and invoices) to predict binary outcomes relevant to business operations.

---

## 📁 Folder Structure

JC_Final/
├── JC_Final.ipynb          # Final notebook with full pipeline
├── Data2/
│   ├── orders.csv           # ERP order data
│   └── invoices.csv         # ERP invoice data
└── .ipynb_checkpoints/     # Jupyter autosaves

---

## 🔍 Model Summary

- **Algorithm**: Logistic Regression (`sklearn.linear_model`)
- **Data Sources**:  
  - `orders.csv`: Contains order-level features  
  - `invoices.csv`: Contains invoice-level features
- **Workflow**:
  1. Load and inspect CSVs
  2. Merge datasets if needed
  3. Feature engineering
  4. Train/test split
  5. Model training and evaluation
- **Metrics**: Accuracy, classification report

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/jcodipilly/erp-ml-projects.git

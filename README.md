# 🛒 Recommendation System Project

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Pandas](https://img.shields.io/badge/Pandas-1.5.2-lightgrey) ![SciPy](https://img.shields.io/badge/SciPy-1.9.3-blueviolet) ![implicit](https://img.shields.io/badge/implicit-0.5.4-orange)

## 📖 Project Overview
This repository contains a collaborative‐filtering recommendation system built with Python.  
It reads users’ past grocery orders, performs exploratory data analysis (EDA),  
trains an ALS model on a user–product sparse matrix, and evaluates Recall@K & Precision@K.  
Finally, it presents interactive visualizations and summary tables of key metrics.  
Ideal for learning end-to-end recommendation pipelines using implicit feedback.

---

## 📂 Data
We use the “Instacart Market Basket Analysis” dataset from Kaggle:  
🔗 **Download**: https://www.kaggle.com/c/instacart-market-basket-analysis/data  
- **orders.csv** — order metadata (order_id, user_id, order_number, etc.)  
- **order_products__prior.csv** — which products were in each “prior” order  
- **products.csv** — product catalog with names and IDs  

---

## 🚀 Installation & Setup

1. **Clone** this repo  
   ```bash
   git clone https://github.com/tu-usuario/recommendation-system.git
   cd recommendation-system

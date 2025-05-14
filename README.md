# Walmart Customer Insights & Inventory Forecasting (v1)

This project explores purchasing behavior from a simulated Walmart dataset, using data analysis and machine learning to uncover insights and estimate product demand.

## 🔍 Objective

To identify purchasing patterns by customer segment and generate predictive estimates of average purchase values per product category and city, as a foundation for inventory optimization.

---

## ⚙️ Workflow (APPASA Framework)

- **Ask:** What patterns drive purchase behavior? Can we predict demand by product and city?
- **Prepare:** Cleaned a dataset of 550,000 records, handled data types and nulls.
- **Process:** Encoded categorical variables, ensured correct distributions and consistency.
- **Analyze:** Explored average purchases by gender, age, city category, and product category.
- **Share:** Documented key insights with visualizations and actionable summaries.
- **Act:** Proposed strategies for marketing and inventory based on the data.
  
---

## 📈 Key Insights

- Age group **51–55** had the highest average purchases.
- City Category **C** showed the strongest spending, though differences were moderate.
- **Product Category 1** dominated in revenue generation.
- Gender had limited influence, with men spending slightly more than women.

---

## 🤖 Machine Learning Model

A Random Forest Regressor was used to estimate purchase amounts based on customer and product features.

**Metrics:**
- RMSE: ~3,030
- R² Score: 63.5%

Although functional, the model's prediction error is too high for deployment. This version serves as a baseline for future improvements.

---

## 🧠 Future Work

- Add more predictive features (e.g., User_ID segmentation, time-based patterns).
- Apply log transformations to normalize high variance in purchase values.
- Explore advanced models (e.g., XGBoost, deep learning).

---

## 🗂️ Files

- `Consumer_Demand_Pattern_Analysis.ipynb`: Main notebook with EDA and ML
- `Inventory_prediction_Walmart`: Model of predicted demand (lite version)
- `README.md`: Project documentation

---

## 💼 Author

Maria José Almeida — Industrial Engineer & ML Analyst  
Focus: Operational AI, customer segmentation, predictive modeling  

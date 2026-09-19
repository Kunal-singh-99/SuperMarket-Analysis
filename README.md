# Supermarket Sales Analysis 🛒

This repository contains my first end-to-end data analytics project. I built this to put my learning into practice by combining **Python (Pandas, Matplotlib)** and **SQL (MySQL)** to extract, clean, and analyze supermarket transaction data. 

The goal of this project wasn't just to write code, but to answer real-world business questions and find actionable insights hidden in the numbers.

## 🛠️ Tools Used
* **Python:** Pandas for data cleaning and aggregation, Matplotlib for data visualization.
* **SQL:** MySQL (via SQLAlchemy) to validate my Pandas logic with direct database queries.
* **Environment:** Jupyter Notebook

## 🎯 Questions Answered
I structured the analysis around specific operational questions:
1. Which branch generates the highest revenue and average transaction value?
2. How do purchasing behaviors differ across genders?
3. When is the busiest time of day for the store?
4. Do 'Member' tier customers actually spend more than 'Normal' customers?
5. Which product lines drive the most sales?

## 📊 Key Findings & Business Takeaways

* **The Evening Rush is Critical:** Store traffic and transaction volumes peak sharply at 19:00 (7 PM). **Takeaway:** Management should optimize shift schedules to ensure maximum checkout staff are available during this evening window to reduce queue times.
* **Branch Performance:** The Giza branch outperformed the others in total revenue and average transaction value, while Naypyitaw generated the highest gross income. **Takeaway:** Operational practices at these branches should be studied and replicated across the network.
* **Loyalty Programs Work:** 'Member' tier customers consistently outspend 'Normal' tier customers regardless of the payment method. **Takeaway:** The store should heavily incentivize POS (Point of Sale) membership sign-ups to drive higher average order values.
* **Surprising Demographics:** Female customers drove the highest volume in *Sports and Travel*, while male customers led in *Health and Beauty*. **Takeaway:** Traditional marketing assumptions should be tested; digital ads and in-store displays should reflect these actual buying patterns.
* **Top Product Line:** *Food and Beverages* is the highest revenue-generating category.

## 💡 What I Learned
As my first major project, this helped me solidify my understanding of:
* Standardizing and cleaning raw data (e.g., parsing datetime strings, cleaning column headers).
* Using `groupby` and `agg` functions to summarize datasets.
* Designing clean, readable visualizations that highlight the actual business answer rather than just plotting default charts.
* Writing SQL queries that mirror Python logic to validate my findings.

## 📂 Files in this Repo
* `SuperMarket Analysis.csv`: The raw dataset (1,000 transactions).
* `Analysis.ipynb`: The main Pandas EDA and SQL and Matplotlib visualization notebook.

---
**Author:** Kunal Singh  
*Aspiring Data Scientist*

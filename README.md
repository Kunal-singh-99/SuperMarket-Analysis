# Super Market Sales Analysis 

This repository contains an exploratory data analysis (EDA) and business intelligence project focused on historical supermarket sales data. The objective of this project is to process raw sales records and extract actionable insights regarding branch performance, customer purchasing behavior, and operational efficiency. 

The workflow integrates standard SQL querying with Python's data manipulation and visualization libraries to simulate a realistic corporate data analytics environment.

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas
* **Database & Querying:** MySQL via SQLAlchemy
* **Data Visualization:** Matplotlib

## Data Engineering & Cleaning
Before querying, the raw `SuperMarket Analysis.csv` dataset required standardization to ensure SQL compatibility and accurate financial reporting:
* **Column Standardization:** Converted all column headers to lowercase and replaced spaces with underscores.
* **Feature Engineering:** Calculated true gross revenue by multiplying `unit_price` by `quantity`, bypassing the pre-calculated sales tax column to ensure accurate performance metrics.
* **Datetime Formatting:** Combined the raw string `date` and `time` columns into a standardized Pandas `date_time` object for chronological analysis.

## Key Business Questions Analyzed
The core of this project relies on writing optimized SQL queries to answer specific operational questions:
1. Which of the three branches generated the highest total revenue, and what was their average transaction value?
2. How does purchasing behavior differ by gender, and which product lines are the most popular among female vs. male customers?
3. What is the busiest time of day for the supermarket based on total transaction volume?
4. Do 'Member' tier customers spend more on average than 'Normal' tier customers, and do their preferred payment methods differ?
5. Is there a relationship between specific product lines and average customer satisfaction ratings?

## Visual Design Philosophy
Effective data communication requires clarity. The visualizations in this notebook avoid cluttered, default aesthetics in favor of a clean, high-contrast, minimalist design. Charts utilize custom color palettes (e.g., blue and deep pink for demographic breakdowns) and explicitly highlight the primary business insight directly within the figure layout. 

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install pandas matplotlib sqlalchemy pymysql`
3. Download the Supermarket Sales dataset and save it as `SuperMarket Analysis.csv` in the root directory.
4. Run the Jupyter Notebook cell by cell. 

**Author:** Kunal Jadon
**Contact:** https://www.linkedin.com/in/kunal-jadon-a9796735b/

# Supermarket Sales Analysis

## Project Overview
This project analyzes supermarket sales transaction data to identify sales performance, product/category trends, branch performance, customer behavior, payment preferences, and customer satisfaction.

The project was developed as part of the **IBM SkillsBuild Data Analytics with AI Academic Internship Program 2026** project submission.

## Problem Statement
The objective is to analyze supermarket sales data and convert transaction-level data into useful business insights. The analysis focuses on products, branches, categories, customer types, payment methods, sales values, quantities, and customer ratings.

## Dataset
**Dataset:** [Supermarket Sales Dataset](https://docs.google.com/spreadsheets/d/1QIX__4VObHFMEXnRM2xJyXmB5JAB2peHrJcQ41_U9TE/edit?usp=sharing)

The supplied dataset contains 500 sales transactions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Excel

## Project Workflow
1. Load the dataset.
2. Inspect rows, columns, data types, missing values, and duplicates.
3. Clean and validate the data.
4. Validate the sales calculation using Quantity × Unit Price.
5. Calculate KPIs.
6. Perform exploratory data analysis.
7. Create visualizations.
8. Answer business questions.
9. Provide business recommendations.
10. Export the cleaned dataset for further analysis.

## Key Business Questions
- Which product/product line generates the highest sales?
- Which branch performs best?
- Which category/product line sells the most?
- What is the most popular payment method?
- Do Members spend more than Normal customers?
- What is the average customer rating?

## Key Findings
- Cheese generated the highest sales: **₹27,906.30**.
- Branch C (Mumbai) generated the highest branch sales: **₹72,469.45**.
- Beverages generated the highest category sales: **₹56,108.24**.
- UPI was the most-used payment method with **127 transactions**.
- Average Member transaction: **₹483.14**.
- Average Normal transaction: **₹497.07**.
- Average customer rating: **3.99/5**.

## Business Recommendations
- Maintain sufficient inventory for high-selling products and categories.
- Investigate the operational factors contributing to Branch C's performance.
- Continue supporting commonly used digital payment methods such as UPI.
- Monitor customer ratings to identify service-improvement opportunities.
- Compare Member and Normal customer behavior when planning membership campaigns.
- Use sales patterns to improve inventory allocation and promotional planning.

## How to Run
### Option 1 — Jupyter Notebook
1. Install Python.
2. Open a terminal in the project folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open:
   `DeepakMalviya_SupermarketSalesAnalysis.ipynb`
6. Keep the source Excel file in the same folder or update the file path in the notebook.
7. Run the cells from top to bottom.

### Option 2 — Google Colab
Upload the `.ipynb` notebook and the Excel dataset to Google Colab, then update the file path if necessary.

## Files Submitted
- `DeepakMalviya_SupermarketSalesAnalysis.ipynb` — complete Python/Jupyter code
- `requirements.txt` — Python dependencies
- `DeepakMalviya_ProjectReport.docx` — project report
- `README.md` — project overview and setup instructions

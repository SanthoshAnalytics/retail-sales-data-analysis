## RETAIL SALES ANALYSIS


# Overview
This project explores retail transaction data using Python, Pandas, and Matplotlib. It summarizes sales performance, compares product categories, examines monthly revenue, and explores customer demographics and category preferences by gender.

# Objectives
- Inspect dataset structure and data quality.
- Calculate retail sales KPIs.
- Compare revenue and units sold by product category.
- Explore monthly revenue trends.
- Analyze revenue by gender and customer age group.
- Summarize findings and practical next steps.


# Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
# Project structure


retail-sales-analysis/
├── data/


│   └── retail_sales_dataset.csv
├── notebooks/
│   └── retail_sales_analysis.ipynb
└── README.md
Place the CSV file in data/ and the notebook in notebooks/. The notebook uses a relative path, so it does not depend on a specific Windows username or download folder.

# Project workflow

<img width="2172" height="724" alt="f7cc9114-f944-4067-84df-de793445c128" src="https://github.com/user-attachments/assets/17ca19a7-87fc-4a52-aef4-5a29f0f04271" />

# Setup and run
1. Install Python 3.
2. Install the required libraries:
   python -m pip install pandas matplotlib jupyter
3. Place retail_sales_dataset.csv in the data/ folder.
4. Open the project folder in VS Code or start Jupyter from the project directory.
5. Open notebooks/retail_sales_analysis.ipynb and run the cells from top to bottom.
# Dataset fields
The notebook expects these columns: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Amount.
# Findings from the current analysis
- Dataset size: 1,000 rows and 9 columns.
- Total recorded revenue: ₹456,000.
- Units sold: 2,514.
- Average transaction amount: ₹456.
- Highest-revenue category: Electronics, ₹156,905 (34.41%).
- Clothing generated ₹155,580 (34.12%); Beauty generated ₹143,515 (31.47%).
- Female customers generated ₹232,840 in recorded revenue; male customers generated ₹223,160.
- The 51–60 age group generated the highest recorded age-group revenue at ₹100,085.
- Clothing was the highest-revenue category among female customers, while Electronics was highest among male customers in the current category-by-gender comparison.
These results describe the supplied dataset and should not be treated as causal conclusions. Check monthly transaction counts and date coverage before interpreting the low January 2024 value as a sales decline.
# Limitations and next steps
The analysis focuses on revenue rather than profit, costs, returns, or customer satisfaction. Potential extensions include monthly transaction counts, repeat-customer analysis, average transaction amount by category, and profit-margin analysis if those fields are available.
# Data and licensing
Add the dataset source and license here before publishing. Only commit the CSV if its license permits redistribution and it contains no sensitive information. Otherwise, explain how readers can obtain it separately

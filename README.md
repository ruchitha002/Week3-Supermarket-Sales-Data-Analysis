# Week 3: Supermarket Sales Data Analysis

## Project Overview
This project analyzes supermarket transaction data using Python. It follows the CodSoft Week 3 workflow:

1. Load the sales dataset
2. Explore the dataset
3. Check missing values
4. Check/remove duplicates
5. Clean the data
6. Calculate sales statistics
7. Analyze product categories
8. Analyze quantity sold
9. Analyze payment methods
10. Analyze customer types
11. Analyze daily sales
12. Create visualizations
13. Find highest and lowest sales
14. Identify key patterns
15. Present business insights

## Dataset
The included `data/supermarket_sales.csv` contains 1,000 supermarket transactions with 9 columns matching the Week 3 project structure:
- Invoice ID
- Date
- Product
- Category
- Quantity
- Unit Price
- Customer Type
- Payment
- Total

**Note:** The PDF provides an example schema and sample values but does not contain an actual downloadable CSV. Therefore, this submission includes a reproducible 1,000-row educational supermarket dataset generated for this project. The analysis code is written so that an official CSV can be substituted later if required.

## Key Results
- Total sales: $81,902.28
- Average transaction value: $81.90
- Highest transaction: $799.80
- Lowest transaction: $0.76
- Highest-sales category: Electronics
- Most-used payment method: Cash
- Highest-sales customer type: Member
- Highest-sales day: 2023-01-11 ($4,753.16)
- Lowest-sales day: 2023-01-23 ($1,046.62)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Open `notebooks/week3_supermarket_sales_analysis.ipynb` and run all cells.

## Project Structure
```text
Week3_Supermarket_Sales_Data_Analysis/
├── data/
│   └── supermarket_sales.csv
├── notebooks/
│   └── week3_supermarket_sales_analysis.ipynb
├── outputs/
│   ├── dashboard.png
│   ├── sales_by_category.png
│   ├── quantity_by_category.png
│   ├── payment_methods.png
│   ├── sales_by_customer_type.png
│   └── daily_sales_trend.png
├── README.md
├── requirements.txt
└── .gitignore
```

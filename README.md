# Data Analysis Project

This project contains Jupyter notebooks and CSV files for analyzing customer, product, and order data. The main components are:

## Structure
- 'customers.csv': Raw customer data
- 'products.csv': Raw product data
- 'orders.csv': Raw order data
- 'requirements.txt': Python dependencies
- 'tables.ipynb': Notebook looking at full table data
- 'notebooks/customer_notebook.ipynb': Customer data analysis notebook
- 'notebooks/product_notebook.ipynb': Product data analysis notebook
- 'notebooks/orders_notebook.ipynb': Order data analysis notebook

## Notebooks
Each notebook starts by importing required packages and loading the customer data. Analyses include:
- Data visualization with Plotly and Matplotlib
- Summary statistics and charts for customers, products, and orders
- Grouped and comparative plots by region, age, loyalty tier, and product category

## Setup
1. Create a Python virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open notebooks in Jupyter or VS Code and run cells

## Usage
- Explore customer, product, and order data
- Visualize trends and distributions
- Modify notebooks to add new analyses

## Notes
- Ensure CSV files are in the project root for correct loading
- Notebooks use relative paths to access CSV files

---
For questions or improvements, feel free to update this README or add new notebooks.

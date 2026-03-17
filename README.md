# Data Analysis Project

This project contains Jupyter notebooks and CSV files for analyzing customer, product, and order data. The main components are:

## Highlights
- Combined analysis notebook for cross-dataset insights
- Multiple interactive visualizations using Plotly and Matplotlib
- Example analyses: sales by category, sales by region, monthly trends, top customers, order status breakdown, and more

## Structure
- 'CSVs/customers.csv': Raw customer data
- 'CSVs/products.csv': Raw product data
- 'CSVs/orders.csv': Raw order data
- 'requirements.txt': Python dependencies
- 'notebooks/tables.ipynb': Notebook looking at full table data
- 'notebooks/customer_notebook.ipynb': Customer data analysis notebook
- 'notebooks/product_notebook.ipynb': Product data analysis notebook
- 'notebooks/orders_notebook.ipynb': Order data analysis notebook
- 'notebooks/combined_notebook.ipynb': Combined analysis across all datasets

## Notebooks
Each notebook starts by importing required packages and loading the relevant data. Analyses include:
- Data visualization with Plotly and Matplotlib
- Summary statistics and charts for customers, products, and orders
- Combined notebook: cross-dataset visualizations (e.g., sales by region, top customers, payment method analysis)
- Grouped and comparative plots by region, age, loyalty tier, product category, and more

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
   - For combined analysis, open 'notebooks/combined_notebook.ipynb'

## Usage
- Explore customer, product, and order data
- Visualize trends and distributions
- Use 'combined_notebook.ipynb' for multi-table insights and advanced visualizations
- Modify notebooks to add new analyses

## Notes
- Ensure CSV files are in the 'CSVs' folder for correct loading
- Notebooks use relative paths to access CSV files

---
For questions or improvements, feel free to update this README or add new notebooks.

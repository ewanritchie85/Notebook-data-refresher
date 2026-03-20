# Projects Data Workspace

This workspace contains Jupyter notebooks and CSV files for managing and analyzing customer, order, and product data. It is designed for data exploration, database interaction, and reporting.

## Highlights
- Combined analysis notebook for cross-dataset insights
- Multiple visualizations using Plotly, Seaborn and Matplotlib
- Example analyses: sales by category, sales by region, monthly trends, top customers, order status breakdown, and more
- Database interaction via local PostgreSQL and SQLAlchemy (required for database notebooks)

## Structure
- `CSVs/customers.csv`: Raw customer data
- `CSVs/products.csv`: Raw product data
- `CSVs/orders.csv`: Raw order data
- `requirements.txt`: Python dependencies
- `notebooks/tables.ipynb`: Table data overview
- `notebooks/customer_notebook.ipynb`: Customer data analysis
- `notebooks/product_notebook.ipynb`: Product data analysis
- `notebooks/orders_notebook.ipynb`: Order data analysis
- `notebooks/combined_notebook.ipynb`: Combined analysis across all datasets
- `notebooks/database.ipynb`: Database setup and interaction (requires local PostgreSQL)

## Notebooks
Each notebook starts by importing required packages and loading the relevant data. Analyses include:
- Data visualization with Seaborn and Matplotlib
- Summary statistics and charts for customers, products, and orders
- Combined notebook: cross-dataset visualizations (e.g., sales by region, top customers, payment method analysis)
- Grouped and comparative plots by region, age, loyalty tier, product category, and more
- Database notebook: connects to local PostgreSQL using SQLAlchemy, creates tables, loads CSV data, and runs SQL queries

## Requirements
- Python (recommended: 3.8+)
- Jupyter Notebook
- Required Python packages listed in `requirements.txt`
- **Local PostgreSQL database** (must be running for database notebooks)

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
3. Ensure a local PostgreSQL server is running and accessible.
4. Open notebooks in Jupyter or VS Code and run cells
   - For combined analysis, open `notebooks/combined_notebook.ipynb`
   - For database setup and SQL queries, open `notebooks/database.ipynb`

## Usage
- Explore customer, product, and order data
- Visualize trends and distributions
- Use `combined_notebook.ipynb` for multi-table insights and advanced visualizations (now using Seaborn/Matplotlib)
- Use `database.ipynb` for database setup, table creation, and SQL queries (requires local PostgreSQL and SQLAlchemy)
- Modify notebooks to add new analyses

## Notes
- Ensure CSV files are in the `CSVs` folder for correct loading
- Notebooks use relative paths to access CSV files
- Database interaction is handled with SQLAlchemy for improved reliability
- Update connection settings in `database.ipynb` as needed for your local PostgreSQL setup

---

For questions or improvements, feel free to update this README or add new notebooks.

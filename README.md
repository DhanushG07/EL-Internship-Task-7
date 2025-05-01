# Task 7: Basic Sales Summary using SQLite & Python

## Objective
- Run SQL queries in Python to get total quantity sold and total revenue.
- Visualize sales by product using matplotlib.
- Use SQL within Python to extract basic sales metrics from a SQLite database.
- Summarize total quantity sold and revenue for each product.
- Visualize the revenue using a bar chart.


## Tools Used
- Python
- SQLite
- pandas, matplotlib
- [Google Colab](https://colab.research.google.com/drive/1KGIWZLRDeaUeau6VXhrvyqa3ZLkhyxnB#scrollTo=lZ5fRSe8dit5)

## Sample Dataset Used
The data was inserted into the SQLite database as shown below:

| Product   | Quantity | Price |
|-----------|----------|-------|
| Pen       | 10       | 1.5   |
| Pencil    | 20       | 0.5   |
| Notebook  | 15       | 2.0   |
| Eraser    | 25       | 0.75  |
| Marker    | 12       | 1.25  |

This data was inserted into a table named `sales` using Python.

## Output
- Sales summary table
- Bar chart: `sales_chart.png`

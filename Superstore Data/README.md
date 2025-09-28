# Superstore Data Analysis

This project explores sales and profit data from a small retail office store (Superstore dataset). The notebook performs exploratory data analysis (EDA) to answer key business questions and visualize insights.

## Features
- Loads and inspects the **Superstore** dataset.
- Groups data by **Category** and **Sub-Category** to find the most and least profitable areas.
- Generates **summary tables** of profit by category and sub-category.
- Creates **Matplotlib/Seaborn bar charts** with annotations highlighting the highest and lowest profit values.

## Business Questions
1. **Which product categories and sub-categories generate the highest and lowest profits?**  
   *(Implemented with charts & summaries.)*

2. **What are the monthly trends in sales vs. profit? Are there seasonal patterns?**  
   *(Suggested extension — add time series analysis.)*

3. **Which customers contribute the most revenue and profit?**  
   *(Suggested extension — group by customer and rank top contributors.)*

## Dataset
The analysis expects a file named `superstore.csv` with at least the following columns:
- `Category`  
- `Sub-Category`  
- `Profit`  

For extended analysis, you will also need:
- `Order Date`  
- `Sales`  
- `Customer Name`

## Requirements
- Python 3.9+
- Libraries: `pandas`, `matplotlib`, `seaborn`

Install them with:
```bash
pip install pandas matplotlib seaborn
```

## How to Run
1. Place `superstore.csv` in the same folder as the notebook.  
2. Open the notebook in Jupyter, VS Code, or Google Colab.  
3. Run all cells to generate the tables and charts.  

## Outputs
- **Category Profit Summary** (table + chart)  
- **Sub-Category Profit Summary** (table + chart)  

The charts mark the highest and lowest profit areas for easy interpretation.

## Next Steps
- Add monthly trend analysis with time-based grouping.  
- Rank top customers by revenue and profit.  
- Export results to CSV or save plots for reports.  

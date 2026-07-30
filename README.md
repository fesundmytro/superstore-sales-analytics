# Global Superstore Sales Analysis

Exploratory analysis of 51,290 Global Superstore orders from 2011 to 2014.

## Project Objective

The project focuses on cleaning and validating sales data, analyzing
revenue and profitability, identifying seasonal patterns, and preparing
a clean dataset for further reporting and visualization.

## Dataset

- 51,290 order records
- Global sales data
- Period: 2011–2014
- Total sales: 12,642,905
- Missing values in key columns: 0

## Tools

- Python
- pandas
- NumPy
- SQLite
- SQL
- matplotlib
- seaborn
- Google Colab

## Analysis

The notebook includes:

- data cleaning and validation;
- SQL analysis by category, market, region, month, and product;
- monthly sales trends;
- month-over-month growth;
- seasonal demand analysis;
- sales outlier detection;
- correlation analysis;
- category revenue and profitability analysis.

## Key Findings

- Technology is the largest category, generating 4,744,691 in sales
  and 37.53% of total revenue.
- APAC is the strongest market by total sales.
- Central is the leading region.
- November and December show the highest average monthly sales.
- Technology has the highest total profit.
- Furniture has the lowest category margin at approximately 7%.
- Discount has a negative correlation with profit.
- Around 11.03% of orders are identified as potential sales outliers;
  they are retained because large orders may represent valid business activity.

## Repository Files

- `superstore-sales-analytics.ipynb` — complete analysis;
- `sales_clean.csv` — cleaned dataset for Python, SQL, and visualization;
- `README.md` — project documentation;
- `requirements.txt` — required Python libraries.

## Running the Project

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells from top to bottom.

## Business Recommendations

- increase inventory availability before the strongest seasonal months;
- review discount policies for low-margin products;
- prioritize strong markets and regions when allocating inventory;
- investigate high-value orders separately instead of automatically
  treating them as data errors.

  ## Data Source and Privacy

This project uses the public Global Superstore dataset obtained from:

https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset

The dataset is used only for educational and portfolio purposes.
No employer, customer, or confidential business data is included.

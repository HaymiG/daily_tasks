# Pandas Hands-On Project: Superstore Dataset

## Objective
Use Pandas to explore, analyze, and visualize the Superstore Dataset to uncover insights about sales, profit, and customer behavior.

## Dataset
**Source:** [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset contains retail sales data including orders, customers, products, and financial metrics.

## Project Tasks

### Task 1: Load & Explore Data
- Load the dataset into a Pandas DataFrame
- Display the first few rows
- Check data types and dataset structure
- Generate summary statistics

### Task 2: Data Cleaning
- Identify missing values
- Handle missing data appropriately
- Convert relevant columns to correct data types (e.g., dates)

### Task 3: Feature Engineering
- Extract Month and Year from the order date
- Create a new column based on existing numerical columns
- Verify whether your new column is logically correct

### Task 4: GroupBy & Aggregation
- Calculate total sales by category
- Calculate total profit by region
- Identify top 5 customers based on sales
- Analyze sales trends over time (monthly)

### Task 5: Pivot Tables
Create pivot tables to show:
- Sales by category and region
- Sales trends by segment over time
- Profit by sub-category

### Task 6: Data Splitting & Merging
- Split the dataset into at least two meaningful DataFrames
- Merge them back into a single dataset
- Ensure the merged result is correct

### Task 7: Data Visualization
Create the following visualizations using Pandas:
- Line chart for sales trend over time
- Bar chart for sales by category
- Bar chart for profit by region
- Pie chart for segment distribution

### Task 8: Insights & Analysis
From your analysis, determine:
- The most profitable category
- The least performing region
- Any patterns between sales and profit
- Important trends over time


## Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Project
1. Clone this repository
2. Place the dataset in the `data/` folder
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run all cells sequentially

## Project Structure
```
.
├── data/
│   └── Sample - Superstore.csv
├── README.md
└── superstore_analysis.ipynb
```

## Key Findings

After completing the analysis, the following insights were discovered:

### Business Performance
- **Total Sales:** Comprehensive analysis of revenue across categories, regions, and time periods
- **Profitability:** Identification of most and least profitable segments
- **Customer Insights:** Top customers and their contribution to overall sales

### Category Analysis
- Technology, Furniture, and Office Supplies performance comparison
- Sub-category profitability rankings
- Product-level insights

### Regional Performance
- Sales and profit distribution across Central, East, South, and West regions
- Regional strengths and areas for improvement

### Trends & Patterns
- Monthly and yearly sales trends
- Seasonal patterns in purchasing behavior
- Correlation between discounts and profitability
- Year-over-year growth analysis

### Recommendations
- Strategic focus areas based on data
- Discount optimization opportunities
- Regional expansion or improvement strategies


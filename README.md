# Amazon Sales Analysis

Exploratory data analysis of Amazon India sales data using Python, 
pandas, Matplotlib and Seaborn.

## Dataset
Amazon Sale Report — 128,000+ orders covering product categories, 
order status, fulfilment method, shipping location and revenue.  
Source: Kaggle

## Questions Answered
- Which product category has the highest cancellation rate?
- Which Indian states generate the most revenue and highest 
  average order values?
- Does Amazon or Merchant fulfilment have a lower cancellation rate?
- How did total revenue change month by month?
- Which sizes are most popular across product categories?

## Key Findings
- Set and Kurta have the highest cancellation rates (~9.9%), but 
  all categories cluster between 6-10%, suggesting cancellations 
  are not driven by product type alone
- Maharashtra generates nearly double the revenue of second-place 
  Karnataka, while smaller states occasionally show higher average 
  order values
- All 11,471 cancellations in the dataset belong to Amazon 
  fulfilment orders — Merchant fulfilment shows no cancelled status, 
  likely due to different recording methods rather than better 
  performance
- Medium, Large and XL are the dominant sizes across all categories, 
  with XS and sizes above XXL showing significantly lower demand

## Tools Used
- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Skills Demonstrated
- Data cleaning on a large real-world dataset (128k rows)
- Cancellation rate calculation using binary encoding
- Multi-level groupby aggregations
- Pivot table and heatmap for two-dimensional categorical analysis
- Time series revenue trend analysis
- Critical interpretation of ambiguous findings

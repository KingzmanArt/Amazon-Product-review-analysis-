# Amazon-Product-Review-analysis-

This project analyzes Amazon product data to uncover trends in pricing, discounts, ratings, and reviews. The goal is to build an interactive Excel dashboard for business stakeholders to identify top performing products and evaluate pricing strategies.

## Objectives

- Analyze product discounts by category
- Identify top-rated and most-reviewed products
- Correlate discount levels with customer ratings
- Create a clean, interactive Excel dashboard
- Reccomendation for shareholders using the result from this analysis


## Data Source

-The dataset was scraped from Amazon product pages.
-Each row represents a unique product with aggregated data:
    -**Product metadata**: name, category, price, discount, rating.
    -**Review data**: review IDs, titles, and contents (stored as comma-separated values).
-Total rows: 1,466
-Fields: 16 columns


## Project Structure

| Folder        | Description                                   |
|---------------|-----------------------------------------------|
| `data/`       | Raw Excel dataset                             |
| `analysis/`   | Excel dashboard and calculated columns        |
| `visuals/`    | Exported charts from the dashboard            |
| `docs/`       | Project summary, tasks, and insights          |

## Analysis Tasks

1. Average discount % by category  
2. Product count per category  
3. Total number of reviews per category  
4. Products with highest average ratings
5. Average actual price vs discounted price by category
6. Products with the highest number of reviews
7. Products with 50% discount or more
8. Distribution of product rating
9. Total potential revenue by category
10. Number of unique products per price range
11. Relationship between rating and level of discount
12. Products woth less than 1000 reviews
13. Categories of products with the highest discounts
14. Top 5 products by combined rating × reviews

## Exploratory Data Analysis

Analysis was carried out using PivotTables and dynamic charts in Excel. The dashboard explored:

- Discounts by category
- Product and review distribution
- Revenue potential
- Rating vs review engagement
- Price impact analysis


## Results

| Metric                            | Value/Insight                              |
|----------------------------------|--------------------------------------------|
| **Total Products Analyzed**      | 1,466                                      |
| **Total Potential Revenue**      | ₹7,976,911                                 |
| **Highest Average Discount**     | HomeImprovement (58%)                      |
| **Top Category by Review Count** | Electronics                                |
| **Most Products in**             | <₹200 price range                          |
| **Top Revenue Categories**       | Electronics, Computers, Home & Kitchen     |
| **Top Rated Products**           | Found across multiple smaller categories   |
| **Products with a discount of 50% and more** | 751.                             |

## Dashboard Preview



## Files

- `review_analysis.xlsx`: Complete pivot tables and charts
- `calculated_fields.md`: Excel formulas for calculated columns

## Key Insights

- Categories like *Electronics* and *Books* offer the highest discounts
- Discount level doesn't always translate to higher ratings
- Products with both high ratings and review volume are best-sellers

## Tools Used

- Microsoft Excel (Pivot Tables, Charts, Dashboard)
- Git & GitHub for version control and collaboration

## Contact

Feel free to fork or reach out via [LinkedIn](https://www.linkedin.com/in/kingsleyoghenekaro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) or [email](omleysplufic@gmail.com) for collaboration.

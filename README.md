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


## Tools and Technique

- **Microsoft Excel** for:
  - Data transformation (formulas & calculated fields)
  - PivotTables and PivotCharts
  - Dashboard design
- Key techniques:
  - String manipulation to count reviews
  - Grouping & binning for rating/discount/price ranges
  - Visual storytelling through charts
 
  
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
- Rating vs review engagement
- Price impact analysis
- Product counts and revenue potential  
- Rating distribution across all products  
- Relationship between rating and discount  
- Products with ≥50% discount


## Results

| Metric                           | Value/Insight                             |
|----------------------------------|--------------------------------------------|
| **Total Products Analyzed**      | 1,466                                      |
| **Total Potential Revenue**      | ₹7,976,911                                 |
| **Highest Average Discount**     | HomeImprovement (58%)                      |
| **Top Category by Review Count** | Electronics                                |
| **Top Price Band**               | <₹200 price range                          |
| **Top Revenue Categories**       | Electronics, Computers, Home & Kitchen     |
| **Top Rated Products**           | Found across multiple smaller categories   |
| **Products with ≥50% discount**  | 751.                                       |
| **Top Review Volume**            | Electronics (4,095 reviews)                |
| **Most Common Rating**           | 4.0–5.0 bucket                             |
| **Top 5 Products by Score**      | Includes USB Cables, Smart Televisions     |



## Dashboard Preview


## Observations and Insights

These insights are crafted for business stakeholders to inform pricing, inventory, and marketing strategies:

### 🔸 Discounts vs Rating:
- No direct correlation between higher discounts and better ratings.
- Categories with deep discounts (like Home Improvement) didn’t always translate to higher ratings.

### 🔸 Review Engagement:
- Electronics and Computers received the **highest review volume**, indicating higher user engagement and visibility.
- Many products had fewer than 1,000 reviews, signaling low exposure or new listings.
- Products with both high ratings and review volume are best-sellers

### 🔸 Product Count:
- Most products fall within the **<₹200** price range, showing a preference or saturation in budget products.

### 🔸 Revenue Potential:
- Top 3 revenue-contributing categories: **Electronics**, **Computers & Accessories**, and **Home & Kitchen**.
- These should be prioritized for marketing and stock optimization.

### 🔸 Top Products:
- Top 5 products by engagement (rating × reviews) include USB Cables and Smart TVs.
- These products have both **high popularity and quality**, making them good promotional anchors.

### 🔸 Rating Distribution
- Over **1,100 products** have ratings in the **4.0–5.0** range, indicating generally high satisfaction.
- Very few products rated below 2.0 — possibly filtered during listing.

### 🔸 Review Count Distribution
- Majority of products have **fewer than 1,000 reviews**.
- Electronics and Computers dominate total review volume, signaling strong visibility and buyer trust.


## Recommendations

1. **Focus marketing spend** on top-performing categories (Electronics, Computers).
2. **Reduce discounts** on low-engagement categories unless they impact sales volume.
3. **Encourage review activity** on under-reviewed products via follow-up emails or incentives.
4. **Consider price repositioning** for products in oversaturated low-price segments.
5. **Use high-rated products** as anchors or featured listings in promotional banners.

## Limitations

- **Review content was not analyzed semantically** (e.g., positive vs negative sentiment).
- **Data represents a static snapshot**, not real-time or time-series trends.
- **External factors** like brand popularity, availability, and delivery time were not considered.
- **Potential revenue** is estimated and doesn’t account for returns, taxes, or conversion rates.


## Contact

Feel free to fork or reach out via [LinkedIn](https://www.linkedin.com/in/kingsleyoghenekaro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) or [email](omleysplufic@gmail.com) for collaboration.

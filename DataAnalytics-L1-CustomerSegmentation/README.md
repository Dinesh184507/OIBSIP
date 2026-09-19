# Customer Segmentation Analysis

**Intern:** Dinesh Desale  
**Track:** Data Analytics  
**Task:** Level 1 – Task 2

## Objective

To segment customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed

1. Loaded and inspected the Online Retail dataset.
2. Handled missing Customer IDs.
3. Removed cancelled transactions and invalid quantities/prices.
4. Created TotalPrice from Quantity × UnitPrice.
5. Performed RFM analysis:
   - Recency
   - Frequency
   - Monetary Value
6. Calculated Average Purchase Value and Customer Lifetime Value.
7. Applied log transformation and StandardScaler.
8. Used the Elbow Method to determine the number of clusters.
9. Applied K-Means clustering with 4 clusters.
10. Visualized customer segments using scatter plots.
11. Profiled each customer segment.
12. Created a customer-count bar chart.
13. Developed marketing actions for each segment.

## Customer Segments

| Cluster | Segment | Customers |
|---|---|---:|
| 0 | Active Low-Value Customers | 837 |
| 1 | High-Value Loyal Customers | 716 |
| 2 | At-Risk Customers | 1,173 |
| 3 | Inactive Low-Value Customers | 1,612 |

## Key Insights

- High-value loyal customers show high purchase frequency and monetary value.
- Active low-value customers are recently active but have lower purchase frequency.
- At-risk customers have relatively high recency and can be targeted with win-back campaigns.
- Inactive low-value customers have high recency and low purchase activity.

## Marketing Recommendations

- Use loyalty rewards and exclusive offers for high-value customers.
- Encourage repeat purchases from active low-value customers.
- Use reminders and limited-time offers for at-risk customers.
- Use re-engagement campaigns for inactive customers.

## Conclusion

RFM analysis combined with K-Means clustering successfully divided customers into four behavioral segments. These segments can help businesses develop targeted marketing strategies, improve customer retention, and increase customer engagement.

# Customer Segmentation Analysis Using Python

## Project Overview
This project uses RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on their purchasing behavior.

## Dataset
- **Source:** UCI Online Retail Dataset
- **Original records:** 541,909
- **Original columns:** 8
- **Customers after cleaning:** 4,372
- **Customers included in clustering:** 4,322

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow
1. Loaded and explored the dataset.
2. Checked missing values and duplicate records.
3. Removed duplicate rows and records missing CustomerID or Description.
4. Calculated transaction amounts.
5. Performed RFM analysis.
6. Excluded customers with zero or negative total spending from clustering.
7. Scaled RFM features using StandardScaler.
8. Used the Elbow Method to select 3 clusters.
9. Applied K-Means clustering.
10. Visualized customer segment sizes and average spending.

## Results
- **Cluster 0:** 1,077 customers — low activity and lower average spending.
- **Cluster 1:** 3,222 customers — regular purchasing behavior.
- **Cluster 2:** 23 customers — high average spending and frequent purchases.

## Conclusion
The analysis identified three customer groups with different purchasing patterns. These insights can help businesses plan targeted marketing campaigns and improve customer retention.

*Note: Segment names are preliminary interpretations based on average RFM values.*

## Author
Oasis Infobyte Data Analytics Internship Project


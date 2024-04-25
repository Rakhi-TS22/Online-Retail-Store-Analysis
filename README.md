# Customer Purchase Behavior Analysis

## Problem Statement
An online retail store aims to understand various customer purchase patterns to improve its competitive advantage.

## Project Objective
**Extracting Valuable Insights from Customer Purchasing History:**  
Explore the provided dataset to uncover actionable insights into customer purchasing behavior. Identify customers, popular products, and regions that can provide a competitive advantage for the online retailer.  

**Customer Segmentation for Targeted Strategies:**  
Employ advanced segmentation techniques to categorize customers based on their purchasing behavior, focusing on Recency, Frequency, and Monetary (RFM) analysis.

## Data Description
The dataset contains 541909 rows and 8 columns:

- **Invoice:** A unique identifier assigned to each transaction or purchase made by a customer.
- **StockCode:** A specific code assigned to uniquely identify each product or item in the retailer's inventory.
- **Description:** A detailed description of the product or item purchased.
- **Quantity:** The quantity of a particular product or item included in a specific invoice or transaction.
- **InvoiceDate:** The date and time when the invoice or transaction took place.
- **Price:** The price per unit of the product, representing the cost assigned to a single item in the transaction.
- **CustomerID:** A unique identifier assigned to each customer.
- **Country:** The geographical region or country where the purchase transaction occurred.

## Data Pre-processing Steps and Inspiration
- Cleaning the missing values.
- Converting Customer ID to int and InvoiceDate into datetime datatype.
- Identifying top customers based on Recency, Frequency, and Monetary metrics.
- Using StandardScaler for feature scaling to ensure uniformity.

## K Mean Algorithm
K-Means is ideal for RFM analysis due to its simplicity, scalability for large datasets, and effectiveness with numeric features. It provides clear, interpretable clusters, making it suitable for unsupervised customer segmentation based on buying behavior.

## Assumptions
- The dataset is representative of the overall customer base.
- Customer transaction records are accurate and up-to-date.

## Model Evaluation and Techniques
- **Clustering Evaluation:** Utilize silhouette scores and within-cluster sum of squares for K-means clustering.
- **Silhouette Score:** 0.6003883114752382
- **Visual Inspection:** Plot the clustered data points in a reduced-dimensional space (e.g., 2D or 3D) to visually inspect how well-defined the clusters are.

## Inferences
- **Optimal Revenue Growth Driven by Segment 2:** Segment 2 leads in consistent and frequent product purchases.
- **Personalized Marketing:** Implement personalized marketing campaigns tailored to specific customer segments.
- **Dynamic Pricing Strategies:** Optimize pricing based on customer preferences and buying patterns.
- **Enhanced Customer Experience:** Implement insights to improve overall customer experience and satisfaction.

## Future Avenues for Project Advancement
By leveraging data-driven insights, the online retail store aims to enhance customer engagement, drive sales, and stay competitive in the dynamic e-commerce landscape.

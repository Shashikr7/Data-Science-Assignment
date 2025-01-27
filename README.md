## eCommerce Assignment: Data Science
# Objective
This project involves analyzing an eCommerce Transactions dataset to:
1. Perform Exploratory Data Analysis (EDA) to derive actionable business insights.
2. Build a Lookalike Model to recommend similar customers based on their profile and transaction history.
3. Conduct Customer Segmentation using clustering techniques to group customers with similar characteristics.

# Dataset Description
The project uses three datasets:
1. Customers.csv:
   Details about customers, including ID, name, region, and signup date.
2. Products.csv:
   Information about products, such as product ID, name, category, and price.
3. Transactions.csv:
   Transaction details, including transaction ID, customer ID, product ID, quantity, and total value.
   
# Tasks
Task 1: Exploratory Data Analysis (EDA)
       Performed detailed analysis of the datasets to uncover trends and patterns.
       Visualized customer distribution by region, top-selling products, and monthly transaction trends.
Derived 5 key business insights:
       Most customers are from the Asia region.
       Product XYZ contributes the highest revenue, accounting for 15% of total sales.
       40% of transactions occur in the months of November and December.
       The top 10 customers contribute over 50% of total revenue.
       Product category A has the highest purchase frequency.
       
Task 2: Lookalike Model
      Built a model to find and recommend 3 similar customers for the first 20 customers (CustomerID: C0001 - C0020).
      Used customer and transaction data to calculate similarity scores using cosine similarity.
      Output: Lookalike.csv containing recommendations with similarity scores.
      
Task 3: Customer Segmentation
     Applied clustering techniques to group customers based on their profiles and transactions.
     Used the K-Means algorithm with 4 clusters and evaluated the clustering using the Davies-Bouldin Index.
     Visualized the clusters using PCA for dimensionality reduction

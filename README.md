# K-Means-Clustering-for-Banking-Customer-Segmentation
## Project Overview

In this project, I used data science techniques to perform customer segmentation for a bank. The main idea is to divide the bank's customers into different groups based on how they use their credit cards, their spending habits, and their overall financial behavior. By understanding these different groups, the bank's marketing team can create targeted marketing campaigns that are better suited to what each group of customers needs.

## Business Problem

Banks need to really understand their customers to offer personalized services and make their marketing efforts more effective. In this case, the marketing team wants to run a targeted ad campaign by dividing customers into distinct groups. The goal is to engage customers better, increase revenue, and make customers happier by offering them the right kind of products and services.

## Solution Approach

1. **Data Preparation and Cleaning**: The dataset includes customer information on balance, purchases, cash advances, credit limits, payments, etc. The data is first cleaned and preprocessed, including handling missing values and scaling features for effective clustering.
   
2. **Exploratory Data Analysis (EDA)**: Conducted EDA to understand customer behaviors and identify significant features that differentiate them. Visualizations like histograms and distribution plots were used to gain insights.

3. **Clustering with K-means**: The K-means clustering algorithm was applied to segment customers. The "Elbow Method" was used to determine the optimal number of clusters, which was found to be around 5 to 7. 

4. **Cluster Interpretation and Naming**: Each cluster was analyzed in detail to understand its unique characteristics, such as spending habits, purchase frequency, and reliance on cash advances. Clusters were named based on these behaviors, such as "Affluent High Spenders," "Cash Advance Reliant," "Dormant Users," etc.

5. **Recommendations**: Based on the clusters, specific marketing strategies and product offerings were recommended for each segment. For example, "Affluent High Spenders" could be targeted with premium rewards, while "Dormant Users" could be reactivated with special offers.

## Key Findings

- Identified 7 distinct customer segments with unique behaviors and financial habits.
- High-value customers (e.g., "Affluent High Spenders") were identified for premium services.
- Customers heavily dependent on cash advances ("Cash Advance Heavy Users") were considered for financial counseling or tailored credit products.

## Technologies Used

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

## Conclusion

This project provides a data-driven approach to customer segmentation for a bank, enabling more effective and personalized marketing strategies. By understanding customer behaviors, the bank can optimize its marketing efforts, enhance customer satisfaction, and drive business growth.

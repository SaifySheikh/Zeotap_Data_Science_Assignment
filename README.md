# Assignment

## Task 1: Business Insights from Customer Data
This task involves analyzing customer transaction data to extract business insights. I focused on deriving insights like:
- Average Transaction Value by Region
- Monthly Trends in Total Sales
- Customer Frequency and Purchase Patterns

The task helped in identifying key patterns and insights from transaction data that can be useful for business decision-making. The analysis utilized pandas, matplotlib, and seaborn for data manipulation and visualization.

### Key Deliverables:
- A set of business insights and visualizations.
  
## Task 2: Lookalike Model
In this task, I built a Lookalike Model that recommends 3 similar customers based on their profile and transaction history. The model used customer and product information, with similarity scores assigned to the recommended customers. The key steps included:
- Merging customer, product, and transaction data.
- Feature engineering to create a comprehensive customer profile.
- Implementing K-Nearest Neighbors (KNN) to find similar customers.

### Key Deliverables:
- A CSV file with lookalike recommendations and their similarity scores.
- A Python script implementing the model.

### Example Output:
For Customer ID `C0001`, the similar customers were:
- Customer ID: C0069 | Similarity Score: 0.9947
- Customer ID: C0055 | Similarity Score: 0.994
- Customer ID: C0072 | Similarity Score: 0.9925

## Task 3: Customer Segmentation / Clustering
This task involved segmenting customers using clustering techniques, combining both profile and transaction information. The steps included:
- Data preprocessing and feature engineering from customer and transaction data.
- Standardizing the features using `StandardScaler`.
- Applying the KMeans clustering algorithm with an optimal number of clusters determined through metrics like DB Index.
- Visualizing the clusters using plots.

### Key Deliverables:
- The clustering results with the number of clusters and relevant metrics.
- Visualizations to represent the clusters.

### Key Metrics:
- Number of clusters formed: 5
- DB Index: 1.2749
- Cluster visualizations with distinct customer segments.

Feel free to explore the notebooks, and if you have any questions or suggestions, don't hesitate to reach out!

---

**Note**: Replace the placeholders like `[insert value here]` and update any example outputs with the actual results from your work.

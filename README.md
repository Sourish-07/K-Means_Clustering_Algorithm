**Customer Segmentation using K-Means Clustering**

**Objective:**
To group customers of a retail store based on their purchase history, focusing on annual income and spending score, using the K-means clustering algorithm.

**Data:**
The dataset used is 'Mall_Customers.csv', which includes attributes like CustomerID, Gender, Age, Annual Income, and Spending Score.

**Methodology:**
1. **Data Preparation:**
   - Extracted relevant features: Annual Income and Spending Score.
   
2. **Determining Optimal Clusters:**
   - Employed the Elbow Method to determine the optimal number of clusters. This involved plotting the within-cluster sum of squares (WCSS) for different values of k (number of clusters) and identifying the "elbow point" where the rate of decrease sharply slows.

3. **Model Training:**
   - Used the K-means++ initialization to avoid random initialization traps.
   - Determined 5 as the optimal number of clusters.
   - Trained the K-means model on the dataset with the specified number of clusters.

4. **Visualization:**
   - Visualized the clusters on a scatter plot, displaying customer segments based on their annual income and spending score.
   - Highlighted cluster centroids for better interpretability.

**Results:**
The K-means clustering successfully segmented the customers into five distinct groups, allowing for enhanced understanding of customer behaviors and targeted marketing strategies.

# Spotify-Data-Analysis 

**Machine Learning Project on Spotify Data using K-Means Clustering** 🎶🤖

**Objective:**
- Explore and cluster Spotify music data to identify patterns and group similar tracks.

**Project Steps:**

1. **Data Loading and Exploration:**
   - Load Spotify dataset from a CSV file.
   - Explore dataset structure, columns, and information.

2. **Feature Engineering:**
   - Use label encoding to transform categorical features like 'track_id', 'track_name', etc.

3. **Outlier Detection and Handling:**
   - Identify and replace outliers using the Interquartile Range (IQR) method.

4. **2D Clustering:**
   - Standardize features ('track_popularity' and 'danceability') using StandardScaler.
   - Apply k-means clustering and visualize clusters in a 2D scatter plot.

5. **Elbow Method:**
   - Determine the optimal number of clusters (k) using the Elbow Method for each clustering scenario.

6. **3 Clustering Scenarios:**
   - Perform k-means clustering on three different pairs of features and visualize the clusters.
     - ('track_popularity' and 'danceability')
     - ('energy' and 'loudness')
     - ('track_artist' and 'track_name')

7. **Cluster Labeling:**
   - Add cluster labels to the original DataFrame.

8. **Inertia and Silhouette Score:**
   - Calculate inertia and silhouette score for model evaluation.

9. **3D Scatter Plot with Plotly:**
   - Create an interactive 3D scatter plot to visualize clusters based on 'track_artist', 'track_name', and 'track_popularity'.

**Results and Insights:**
- Identify distinct clusters representing different music characteristics.
- Gain insights into the relationships between track features and artist information.
- Evaluate model performance using inertia and silhouette score.

**Tools and Libraries Used:**
- Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Plotly.

**Next Steps:**
- Further analysis or application of clustering results for personalized music recommendations or genre categorization.

**Note:**
- The project leverages unsupervised machine learning (K-Means) to uncover patterns in the Spotify music dataset.
- The interactive 3D scatter plot provides a visual representation of the clustered data.

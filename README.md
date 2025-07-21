# Customer Segmentation Using Unsupervised Learning

## Overview
This project applies unsupervised machine learning techniques to segment customers based on their purchasing behavior. By identifying distinct customer groups, businesses can tailor their marketing strategies and offerings to better serve each segment.

## Objective
To identify meaningful customer segments from behavioral data using clustering algorithms and visualize these segments for actionable business insights.

## Dataset Description
- **Features**: Numerical attributes describing customer behavior (e.g., annual income, age, spending score).
- **Source**: Typically a retail or mall customer dataset used for segmentation tasks.
- **Goal**: Discover natural groupings in customer data without using labeled output.

## My Approach
1. **Data Cleaning and Preprocessing**
   - Removed missing or duplicate records
   - Scaled features using standardization for distance-based clustering
2. **Exploratory Data Analysis (EDA)**
   - Explored distributions and correlations between features
3. **Clustering**
   - Applied the KMeans algorithm to segment customers
   - Determined the optimal number of clusters using the Elbow Method and Silhouette Score
4. **Dimensionality Reduction and Visualization**
   - Used Principal Component Analysis (PCA) and t-SNE for visualizing clusters in 2D space

## Key Insights
- Distinct customer clusters were identified, each representing a group with shared characteristics such as high income, low spending, or younger age profiles.
- Visualization of clusters revealed patterns that can help target marketing efforts more precisely.
- Example strategies include targeting high-income low-spending customers with exclusive offers or engaging younger segments through digital channels.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- PCA and t-SNE for visualization

## Skills Demonstrated
- Unsupervised Learning (Clustering)
- Feature Scaling and Preprocessing
- Dimensionality Reduction
- Data Visualization and Interpretation

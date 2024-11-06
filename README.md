# Customers-Segmentation-for-SuperStore
**Objective** 
The main goal of analysis is to `segment customers of superstore´ based on their demographic and purchasing behavior to understand different customer profiles .This segmentation can help develop target marketing strategy and personalized experiences to enhance customer retention and increase sales.

**Dataset Description**
The dataset contains 2,240 rows and 21 features, including demographic information (e.g., Year_Birth, Education, Marital_Status), purchase behavior across various product categories (MntWines, MntFruits, etc.), and additional features such as Income, NumWebPurchases, and Dt_Customer (enrollment date).

**Approach**
1-Data Loading and Cleaning: Import the dataset, handle missing values, and perform data type conversions.
2-Exploratory Data Analysis (EDA): Analyze data distributions, detect correlations, and observe spending patterns across product categories.
3-Feature Engineering: Prepare data for clustering by selecting relevant features and normalizing or encoding data as needed. Clustering 4-Analysis: Apply K-means clustering to segment customers and interpret the characteristics of each cluster.
Visualization and Interpretation: Visualize clusters and spending trends to understand customer profiles and purchasing behaviors.

**Assumptions**
1-Missing values in Income represent non-responses and are filled with the median value.
2-Categories in Education and Marital_Status columns have been standardized for consistency.
3-Customers' spending habits are assumed to be influenced by their demographics, which helps in segmentation.

**Key Findings**
1-The dataset reveals distinct spending patterns across product categories, with some customers consistently spending more on certain products.
2-Correlations between spending categories suggest that customers who buy more in one category may also spend more in others.
3-Preliminary clustering shows that customers can be grouped based on income levels and purchasing patterns, offering potential for tailored marketing strategies.

**Next Steps**
1-Further exploration into feature engineering (e.g., creating aggregated spending or frequency features) to improve clustering.
2-Experiment with additional clustering algorithms (e.g., DBSCAN) to see if they offer more insightful customer segments.
3-Conduct hyperparameter tuning on the clustering model to refine segments and achieve a clearer understanding of customer profiles.


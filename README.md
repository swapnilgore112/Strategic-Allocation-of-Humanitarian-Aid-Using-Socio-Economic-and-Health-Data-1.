# Strategic-Allocation-of-Humanitarian-Aid-Using-Socio-Economic-and-Health-Data-1.

Project Summary: Strategic Allocation of Humanitarian Aid Using Socio-Economic and Health Data

1. Project Objective:

The goal of this project is to assist an international humanitarian NGO in strategically allocating $120 million in funding. The allocation is to be based on a data-driven analysis that identifies countries most in need of aid, using various socio-economic and health factors. The analysis will involve classifying countries using Principal Component Analysis (PCA), K-Means Clustering, and Hierarchical Clustering.

2. Dataset Overview:

The dataset used in this project contains socio-economic and health-related data for various countries. The key columns in the dataset include:



country: Name of the country

child_mort: Child mortality rate per 1,000 live births

exports: Exports as a percentage of the GDP

health: Health expenditure as a percentage of the GDP

imports: Imports as a percentage of the GDP

income: Net income per person

inflation: Inflation rate (annual %)

life_expec: Life expectancy in years

total_fer: Total fertility rate (births per woman)

gdpp: GDP per capita

3. Data Preprocessing:

Standardization: The dataset was first preprocessed by standardizing the features to ensure that all variables contribute equally to the analysis. This step was crucial for PCA and clustering algorithms, which are sensitive to the scale of data.

4. Principal Component Analysis (PCA):

Dimensionality Reduction: PCA was applied to reduce the dimensionality of the dataset to two principal components, making it easier to visualize the data and capture the most significant variance in the data.

Visualization: The results of the PCA were plotted, allowing us to observe the distribution of countries based on the reduced dimensions.

5. K-Means Clustering:

Clustering: K-Means clustering was applied to the PCA-transformed data to group the countries into three distinct clusters. This method helps in identifying countries that share similar socio-economic and health characteristics.

Cluster Visualization: The clusters were visualized on the PCA plot, showing how countries are grouped based on their principal components.

6. Hierarchical Clustering:

Dendrogram: Hierarchical clustering was performed to further analyze the relationships between countries. A dendrogram was plotted, providing a hierarchical view of the country clusters and revealing how clusters are nested within each other.

Interpretation: This step provided insights into how closely related different countries are in terms of socio-economic and health factors, and allowed for the identification of outliers or distinct clusters.

7. Evaluation of Clustering Results:

Silhouette Score: The quality of the K-Means clustering was evaluated using the Silhouette Score, a metric that measures how similar a country is to its own cluster compared to other clusters. A higher silhouette score indicates better-defined clusters.

8. Identification of Countries in Need:

Target Cluster Identification: Based on the clustering results, the cluster representing the countries in the direst need of aid was identified. This cluster likely contained countries with the lowest income, highest child mortality rates, and other adverse indicators.

Country Recommendations: The countries in this target cluster were recommended as the primary focus for the NGO's aid distribution strategy.

9. Visualizations:

Correlation Matrix: A heatmap of the correlation matrix was created to show the relationships between different socio-economic and health factors, highlighting which factors are most closely related.

Feature Distributions: Histograms of each feature were plotted to provide insights into the distribution of data across different socio-economic and health metrics.

10. Conclusion:

The analysis provided a data-driven approach to classify countries based on their socio-economic and health status. By identifying clusters of countries with similar characteristics, the NGO can strategically allocate its resources to the country's most in need. This method not only ensures effective use of funds but also helps in maximizing the impact of humanitarian efforts.

This project demonstrates the power of combining PCA and clustering techniques to solve real-world problems in a strategic and impactful manner, making it a valuable tool for NGOs and other organizations involved in international development.

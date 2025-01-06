# Cluster-analysis
This is my course project about clustering analysis of districts/cities in West Java based on socio-economic conditions using the K-Means method.

# Objective
- How to analyze clusters with K-Means method?
- How to clustering districts/cities in West Java province based on socio-economic conditions using the K-Means algorithm method?

### How to analyze clusters with K-Means method?
- Cluster analysis is a multivariate technique whose main objective is to group objects based on their characteristics (Awalludin & Taufik, 2017)
- Cluster analysis is to classify objects so that objects that are closest in similarity to other objects are in the same cluster (Ediyanto et al., 2013)

K-Means method is a non-hierarchical cluster analysis that seeks to group existing data into one group, where data in one group has different characteristics from data in one group (Helilintar & Farida, 2018)

Basic algorithm of K-Means method:
- Determine the value of k as the number of clusters to be formed.
- Initialize the value of k as a centroid that can be generated randomly.
- Calculate the distance of each data to each centroid using the euclidean distance equation.
- Group each data based on the closest distance between the data and its centroid.
- Determine the new centroid position (k)
- Return to point 3 if the position of the new centroid with the old centroid is not the same. According to Santoso (2014), K-Means clustering has assumptions that must be met, namely the samples taken must be able to truly represent the existing population and multicollinearity, which is the possibility of correlation between objects. However, it should not exist, if there is a large multicollinearity is not high (for example above 0.5).

### How to clustering districts/cities in West Java province based on socio-economic conditions using the K-Means algorithm method?
Research methods:
- Collection of socio-economic data for districts/cities in West Java in 2020 from the Central Bureau of Statistics of Indonesia.
- Describe variables with descriptive statistics.
- Data visualization of data pre-processing results.
- Data clustering with K-Means algorithm.

# Conclusion
Based on cluster analysis using the k-means method, the socio-economic data of districts/cities in West Java in 2020 is divided into 3 clusters.
- Cluster 1 contains districts / cities in West Java with medium quality socio-economic life. this cluster consists of Bogor, Bandung, Kuningan, Cirebon, Sumedang, Subang, Purwakarta, Karawang, Bekasi, West Bandung, Sukabumi city, Cirebon city, and Tasikmalaya city.
- Cluster 2 contains districts/cities in West Java with low socioeconomic quality of life. this cluster consists of Bogor city, Bandung city, Bekasi city, Depok city, Cimahi city.
- Cluster 3 contains districts/cities in West Java with high socioeconomic quality of life. this cluster consists of Sukabumi, Cianjur, Garut, Tasikmalaya, Ciamis, Majalengka, Indramayu, Pangandaran, and Banjar city.

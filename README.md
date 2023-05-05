# Netflix-Movies-and-TV-shows-Clustering
## Project Summary
Netflix uses data analysis and machine learning techniques such as clustering to group their content into similar categories, aiming to improve the user experience by providing personalized content recommendations to users based on their viewing history and preferences. This involves analyzing various characteristics of each title, such as genre, cast, and plot, and using algorithms to identify patterns and similarities.

Clustering techniques such as k-means, hierarchical clustering, and principal component analysis (PCA) are used to group movies and TV shows with similar features into distinct groups, each representing a unique genre or category. This approach helps Netflix provide personalized recommendations to users based on their viewing history and preferences, leading to increased user engagement and satisfaction, which in turn can lead to increased retention and company revenue.

Clustering enables Netflix to make data-driven decisions about content production and licensing by understanding underlying trends and patterns in user behavior. This helps the platform to optimize its content library and offer titles that are more likely to be successful with its user base, leading to increased customer retention and company revenue.

In conclusion, Netflix Movies and TV Shows Clustering is a data-driven approach that relies on unsupervised machine learning algorithms to analyze and group its vast library of content into similar categories, providing users with personalized recommendations and improving the overall user experience. Clustering helps Netflix make informed decisions about content production and licensing, leading to increased customer retention and company revenue
## Key Findings
### CONCLUSION FROM EDA:

1. On the Netflix platform, there are more movies available than TV shows. Netflix primarily features content for mature audiences, with a majority of it having a TV-MA rating.

2. The countries with the highest number of productions available on Netflix are the United States, India, and the United Kingdom.

3. Since its establishment in 2008, Netflix's content library has experienced a consistent increase.

4. The most common genres of content on Netflix are Dramas, Comedies, and Documentaries.

5. According to the Wordcloud visualization of movie descriptions, some of the most frequently used words in Netflix movie descriptions are love, family, young, life, and world.

6. The correlation heatmap indicates a moderate positive correlation between a movie's release year and its duration.

7. The pairplot reveals several interesting patterns between variables, such as a strong positive correlation between the number of reviews and the year of release, and a negative correlation between a movie's rating and its duration.

### CONCLUSION FROM MODEL IMPLEMENTATION:

1. Based on the attributes of director, cast, country, genre, rating, and description, the data was clustered.

2. To tokenize, preprocess, and vectorize the values in the attributes, TFIDF vectorizer was used, resulting in a total of 10,000 attributes.

3. In order to capture more than 95% of the variance, Principal Component Analysis (PCA) was utilized to reduce the dimensionality of the data.

4. Using the elbow method and Silhouette score analysis, the optimal number of clusters for the K-Means Clustering algorithm was determined to be 7.

5. The optimal number of clusters for the Agglomerative clustering algorithm was determined to be 5 based on the dendrogram visualization.

6. Utilizing cosine similarity, a content-based recommender system was constructed and will provide 10 recommendations to the user based on the type of show they previously watched.

7. DBSCAN clustering was utilized, and it identified 17 optimal clusters with a low metric score.

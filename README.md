># Netflix Movies And TV Shows Clustering - Unsupervised ML

**AlmaBetter Verified Project** - [**Credentials**]()

![MasterHead](https://www.flashfly.net/wp/wp-content/uploads/2022/08/Netflix.jpeg)

<font size="1">Image Courtesy: https://www.flashfly.net/wp/wp-content/uploads/2022/08/Netflix.jpeg</font>

Click on the following link to check out the video presentation and the colab file.
- [Colab](https://colab.research.google.com/drive/1RiIATGKCpGRRSJqw2Je6j-1RQg4Cdp8q)
- [Video]()


---

## Problem Statement

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report that shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, and rotten tomatoes can provide many interesting findings.

In this project, required to do:

- Exploratory Data Analysis.

- Understanding what type of content is available in different countries.

- Is Netflix increasingly focusing on TV rather than movies in recent years?

- Clustering similar content by matching text-based features.

---
## Project Summary

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report that shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Initially, I have to start with understanding the dataset, then I clean the data to make the analysis ready.

Explore the data and understand the behavior of the same.

Then I prepare the dataset for creating clusters by various parameters wherein I can remove stop words, white spaces, numbers, etc. so that I can get important words and based on that I shall form clusters.

Later I used the silhouette method and k-means elbow method to find an optimal number of clusters, built a recommender system by cosine similarity, and recommended the top ten movies.

---
## Conclusion

The objective of the project was to cluster TV shows and movies based on their similarities and differences, with the ultimate goal of creating a content-based recommender system that recommends 10 shows to users based on their viewing history. Some key points from the project include:

- Exploring the dataset consists of 7787 records and 12 attributes, with a focus on missing value imputation and exploratory data analysis (EDA).

- The analysis revealed that Netflix has a greater number of movies than TV shows, with a rapidly growing collection of shows from the United States.

- To cluster the shows, I have selected six key attributes: director, cast, country, genre, rating, and description (all are categorical variables). These attributes were transformed into a 9000-feature TF-IDF vectorization, and Principal Component Analysis (PCA) was used to address the curse of dimensionality. Captured more than 80% of the variance by reducing the components to 2500.

- Next, I used K-Means and Agglomerative clustering algorithms to group the shows. The elbow method confirmed that the optimal number of clusters was 6 for K-Means, however for the Silhouette score analysis it was 5.

- In Agglomerative clustering, the optimal number of clusters was also 6, which we visualized with a dendrogram.

- Continued all the efforts by creating a content-based recommender system using the similarity matrix obtained through cosine similarity.

The recommender system offers personalized recommendations based on the type of shows the user has watched and provides the user with ten top-notch suggestions to explore.

---

## Author
[Ashwini Suryakar](https://www.linkedin.com/in/ashwini-suryakar-b4b68523a/)

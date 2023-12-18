# Customer Segmentation Analysis Using Unsupervised Learning

This is a Basic Project that will help one understand Unsupervised Learning in a Brief way. Project-wise learning is one of the most effective ways to learn anything.
![Logo](https://github.com/Srayoshi-Mirza/Srayoshi-mirza.github.io/blob/main/uploads/srayoshi-logo-01.png)
- [@Srayoshi-Mirza](https://github.com/Srayoshi-Mirza)
## Customer Segmentation

Customer segmentation is the process of dividing a customer base into groups of individuals who are similar in specific ways relevant to marketing, such as age, gender, interests, spending behavior, and more. The goal of customer segmentation is to understand better and meet the unique needs of different customer groups, allowing businesses to tailor their marketing strategies, product offerings, and customer experiences for maximum effectiveness.
![Customer Segmentationt](https://i.ytimg.com/vi/zPJtDohab-g/maxresdefault.jpg)

## Unsupervised Learning

Unsupervised learning is a type of machine learning where the algorithm is presented with a dataset without labeled responses or targets. Unlike supervised learning, where the model is trained on a dataset with explicit labels, unsupervised learning involves extracting patterns, structures, or relationships inherent in the data without predefined categories. Common techniques in unsupervised learning include clustering, where similar data points are grouped, and dimensionality reduction, which aims to reduce the complexity of the dataset while preserving essential features. Unsupervised learning is beneficial for discovering hidden patterns and gaining insights into the intrinsic properties of the data.

![Unsupervised Learning](https://miro.medium.com/v2/resize:fit:640/format:webp/1*Iihw0V-r0raMMtcDTFGGQA.png)

## Clustering
Clustering is a process of grouping similar objects; i.e., to partition unlabeled examples into disjoint subsets of clusters, such that:

    1. Examples within a cluster are similar (in this case, we speak of high intraclass similarity).

    2. Examples in different clusters are different (in this case, we speak of low interclass similarity).
Two kinds of inputs can be used for grouping:

- in similarity-based clustering, the input to the algorithm is an n × n dissimilarity matrix or distance matrix;
- in feature-based clustering, the input to the algorithm is an n × D feature matrix or design matrix, where n is the number of examples in the dataset and D is the dimensionality of each sample.
Similarity-based clustering allows easy inclusion of domain-specific similarity, while feature-based clustering has the advantage that it applies to potentially noisy data.
![Clustering]([https://nixustechnologies.com/wp-content/uploads/2022/03/unsupervised-machine-learning-1.webp](https://devopedia.org/images/article/242/4320.1575221317.png)https://devopedia.org/images/article/242/4320.1575221317.png)

## About The Dataset

Dataset Link: [Ecommerce Customer Data](https://www.kaggle.com/datasets/iabdulw/ecommerce-customer-data)

This dataset contains data from customers from an E-commerce platform. (2022-01-19)
Can use this data to predict the Yearly Amount Spent based on customer features

Columns:
- Email
- Address
- Avatar
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

Title: Ecommerce Customer Data
    Author Mason Greenwood, Mason Greenwood


## Objective of the Project:
The primary objective of this project is to segment customers based on relevant features, uncovering meaningful insights that can guide business strategies.

## Methodology:
### Unsupervised Learning Techniques:

Utilized
- K-Means clustering
- Hierarchical clustering algorithms
    - Top-Down
    - Bottom-Up
to identify and group similar customers.

### Exploratory Data Analysis and Data Preprocessing
- Conducted data preprocessing, including handling missing values, encoding categorical variables, and scaling features.

![Pairplot](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/EDA%20Pairplot.png)

- Selected relevant features for clustering.
    - Time on App
    - Time on Website
    - Length of Membership
    - Yearly Amount Spent
### Visualization:

- Employed visualizations such as scatter plots to represent clusters.
#### K-Means
![K-Means](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/K-Mean%20Cluster.png)

#### Top-Down
![Top-Down](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/Top%20Down%20Cluster.png)

#### Bottom-Up
![Bottom Up](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/bottom%20up%20cluster.png)

- Utilized cluster characteristics plots to provide an overview of each cluster.

#### Top-Down
![Top-Down](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/Top-Down%20dendrogram.png)

#### Bottom-Up
![Bottom Up](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/bottom%20up%20dendrogram.png)

### Metrics:

Evaluated clustering quality using metrics like silhouette score, examining cluster characteristics, and analyzing feature importance.

## Results and Findings:
#### K-Means Clustering:

- Identified distinct customer segments with varying spending patterns and engagement levels.
- Explored the characteristics and behavior of each cluster.
#### Top-Down Hierarchical Clustering:

- Examined the distribution of data points within clusters.
- Compared results with K-Means clustering, highlighting differences and similarities.
#### Bottom-Up Hierarchical Clustering:

- Presented insights into cluster sizes and their significance.
- Discussed the implications of the identified clusters on business strategies.
### Feature Importance:
- Explored the importance of features in distinguishing clusters.
- Identified key features contributing significantly to the separation of clusters.

![Feature](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/Feature%20Importance.png)
## Comparison:
- Compared the performance of K-Means, Top-Down Hierarchical, and Bottom-Up Hierarchical clustering.
- Discussed the strengths and weaknesses of each method.

## Check the size of each cluster to see if there is a significant imbalance
![all cluster](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/All%20clusters.png)

## Cluster Interpretation:
- Interpreted the meaning of each cluster in practical terms.

![K-means](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/k-means%20feature.png)
![Top-down](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/top%20down%20features.png)
![bottom up](https://github.com/Srayoshi-Mirza/Customer-Segmentation-Unsupervised-Learning-/blob/main/Screenshots/bottom%20up%20feature.png)

- Linked clusters to potential business actions, enabling targeted strategies for different segments.
## Limitations and Future Work:
Acknowledged limitations in the current approach, such as potential bias or data constraints.
Suggested future directions, including exploring additional features or refining clustering algorithms.


## References

 - [Customer Segmentation](https://www.youtube.com/watch?app=desktop&v=zPJtDohab-g)

 - [Unsupervised Learning]([https://nixustechnologies.com/unsupervised-machine-learning/](https://medium.com/analytics-vidhya/beginners-guide-to-unsupervised-learning-76a575c4e942))



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://srayoshi-mirza.github.io)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srayoshi-mirza/)




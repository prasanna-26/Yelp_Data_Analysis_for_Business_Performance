# Yelp Data Analysis for Business Performance

# Introduction
The problem being addressed in the analysis of the Yelp dataset is to understand the factors that contribute to the success of businesses on Yelp. By exploring the dataset and performing various analyses, the goal is to uncover insights that can guide business owners in enhancing their performance, improving customer satisfaction, and ultimately achieving success on the Yelp platform.

Benefits:
1. Business Performance Improvement
2. Customer Satisfaction Enhancement
3. Competitive Advantage

Drawbacks:
1. Data Limitations
2. Causality vs. Correlation
3. External Factors

# Dataset

The dataset that we chose for the project is the Yelp dataset obtained from <a href = "https://www.kaggle.com/datasets/abdulmajid115/yelp-dataset-contains-1-million-rows"> Kaggle </href> </a>. The dataset contains approximately one million rows and 14 attributes. 

1. ID: The unique identifier for each entry in the dataset.
2. Time_GMT: The time of the entry in GMT (Greenwich Mean Time).
3. Phone: The phone number associated with the business.
4. Organization: The name or organization associated with the business.
5. OLF: Unknown variable
6. Rating: The average rating given to the business.
7. NumberReview: The total number of reviews for the business.
8. Category: The category or type of business (e.g., restaurant).
9. Country: The country where the business is located.
10. CountryCode: The country code of the business location.
11. State: The state or province where the business is located.
12. City: The city where the business is located.
13.Street: The street address of the business.
14. Building: The building number or identifier associated with the business.

# Tools and Techniques used

In the project, several tools and techniques were used to analyze the Yelp dataset.
1. PySpark
2. Spark SQL
3. Dataframe API
4. Data Processing Techniques
5. Exploratory Data Analysis
6. Aggregation and Statistical Functions
7. Clustering algorithm

# EDA

1. Distribution of Yelp Businesses by Category
<img src = "Images/Distribution of Yelp Businesses by Category.png">
2. Distribution of Ratings
<img src = "Images/Distribution of Ratings.png">
3. Top 20 organizations count by city
<img src = "Images/Top 20.png">

# Clustering analysis
# Rating vs. Number of Reviews

Cluster 0 Center: [Rating: 2.72, Number of Reviews: 26.49]

Cluster 1 Center: [Rating: 4.06, Number of Reviews: 2314.81]

Cluster 2 Center: [Rating: 3.98, Number of Reviews: 523.50]

<img src = "Images/Ratings vs Reviews.png">

# Conclusion

1. Data Analysis and Insights:
The analysis revealed the top-rated organizations, allowing for recognition of businesses that consistently received positive reviews. Understanding the distribution of ratings and reviews provided insights into customer sentiments and satisfaction levels. Exploring the most common categories helped identify popular business types and industry trends.
The conclusions from the cluster analysis provide Yelp with actionable insights to enhance recommendations, targeted marketing, and market understanding for improved user experience and support for restaurant owners.

2. Limitations and Future Considerations:
The analysis focused on a specific dataset, and the findings are specific to the Yelp dataset used. Generalization to other datasets should be done cautiously. Further analysis could include sentiment analysis of reviews using natural language processing techniques to extract more detailed insights. Incorporating external data sources, such as demographic data or social media trends, could enrich the analysis and provide a broader context.

# UnSupervised_ML_Zomato_Restaurant_Clustering_and_Sentiment_Analysis
 
# Problem Statement
This project aims to cluster Zomato restaurants using advanced data analytics and machine learning techniques, enabling targeted audience identification and data-driven decision-making. Additionally, customer sentiment analysis will provide valuable insights for enhancing customer satisfaction and driving business growth in the competitive restaurant industry.

# Attribute Information
# Zomato Restaurant names and Metadata
Use this dataset for clustering part

Name : Name of Restaurants

Links : URL Links of Restaurants

Cost : Per person estimated Cost of dining

Collection : Tagging of Restaurants w.r.t. Zomato categories

Cuisines : Cuisines served by Restaurants

Timings : Restaurant Timings

# Zomato Restaurant reviews
Merge this dataset with Names and Matadata and then use for sentiment analysis part

Restaurant : Name of the Restaurant

Reviewer : Name of the Reviewer

Review : Review Text

Rating : Rating Provided by Reviewer

MetaData : Reviewer Metadata - No. of Reviews and followers

Time : Date and Time of Review

Pictures : No. of pictures posted with review

The dataset contains information from 105 Zomato Restaurants in Hyderabad. The project focuses on customers and the company to cluster Zomato restaurants into different segments that can be used to solve some of the business cases that can directly help customers find the Best restaurant in their locality and the analysis can be beneficial for the company to grow up and work on the fields where they are currently lagging. Data could be used for sentiment analysis to acquire knowledge about Zomato Restaurants' customers' experiences. We have made two different models in our project

Clustering Model - K Means Clustering , Agglomerative Hierarchial Clustering.

Sentiment Analysis Model(Unsupervised) - LDA (Latent Dirichlet Allocation).

Sentiment Analysis Model(Supervised) - Logistic Regression, XGboost.

# RecomMendation System

We were provided with two datasets - Zomato Restaurants Name and Zomato Restaurants Reviews. We used different imputers to deal with the missing values and manipulated necessary columns to make it analysis ready. Then performed EDA and performed required feature engineering for both the models separately. We used Textual Data PreProcessing Using NLP for the Sentiment Analysis Model.

For Clustering we used K Means and Agglomerative Hierarchial Clustering Algorithms to cluster the Zomato Restaurants and made a separate Sentiment Analysis model to classify the Sentiments as Positives and Negatives. We also used World Cloud to vizualize the most frequent words in both Positive and Negative sentiments reviews and finally built some classification models and chose the best one by comparing the evaluation metrics.

# Notebook Breakdown:
- Business Problem Analysis
- Data Collection
- Data Cleaning and Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Best Restaurants in the City
- The Most Popular Cuisines in Hyderabad
- Restaurants and their Costs
- Cost-Benefit Analysis
- Hypotheses Generation on visualized data for Clustering
- Restaurant Clustering
- K means Clustering on Cost and Ratings
- Multi-Dimensional K means Restaurant Clustering
- Principal Component Analysis
- Silhouette Score
- K means Clustering
- Cluster Exploration
- Sentiment Analysis
- Exploratory Data Analysis
- Critics in the Industry
- Text Pre-Processing and Text Visualization
- Modeling
- Conclusion

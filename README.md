# KNN---book-recommendation-system

# CHAPTER 01 
## 1.0 Introduction  
----------------------------------------------------------------------------------------------------------------------------------------------------------
Nowadays, mostly like leading e-commerce web site and other business-related web, mobile and desktop applications like Spotify, Facebook, YouTube and eBay are using and training machine learning models for getting most successful and productive datasets that regarding to the recommendations on their own functionalities. Because of the recommendation have the ability to maintain the business logic-chain at their present and future business progress.
 
# CHAPTER 02
## 2.1 Selecting suitable dataset
-----------------------------------------------------------------------------------------------------------------------------------------------------------
For developing a machine learning model, the first step is, finding suitable dataset for the targeted problem. In this project, I have used two datasets that’s relating to the above scenario.
The first dataset that I used is books.csv. It includes number so columns and I had to have filter only two columns from this data set. 

## 2.2 Uploading data

By using Pandas python library, I had the able to upload the required columns of each two table under the given data types.

# CHAPTER 03 
 
## 3.1 Cleaning the data 

For developing and training a machine learning model, the gathered data should be more and more clean. In some situations, like under the name, title and description columns, they are included unnecessary symbols. 
Other considerable thing is some values are missing or null. As an example, the mathematically related values will be null. Then when we are going to build matrixes for developing purpose the following matrixes shows NaN values.

Because of above reasons, The data must be cleaned!

# CHAPTER 04

## 4.1 Machine Learning Algorithm

Consider about the development of machine learning model, selecting a correct algorithm is not an easy task at all times. However, for the recommendation systems, developers can develop those kinds of models in 3 different ways mainly.

---------------------------------------------------------------------------------------------------------------------------------------------------------
1.	Content Based Recommendation System
2.	Popularity Based Recommendation System
3.	Collaborative Based Recommendation System
---------------------------------------------------------------------------------------------------------------------------------------------------------

In this scenario, I had decided to develop Collaborative Recommendation System for books, Because the collaborative recommendation systems mostly use user’s rating as well.


For developing purpose, I used K-Nearest Neighbor (KNN) algorithm and used NearestNeighbors library from sklearn.neighbors and also used fuzzywuzzy library for making searching progress easily.

Finally, I had the able to develop and train a model using K-Nearest Neighbor algorithm for performing a small book recommendation system. In this scenario, I have tried several times with passing different types of films’ names and got different suggestions from this trained machine learning model.


![image](https://user-images.githubusercontent.com/82445185/196846740-60cfc3ee-c2cf-46cc-84c2-e5ae17979064.png)

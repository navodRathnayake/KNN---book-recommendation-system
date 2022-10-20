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


![image](https://user-images.githubusercontent.com/82445185/196846843-f20bab53-407f-41e8-ab33-2f37b3bf7564.png)
![image](https://user-images.githubusercontent.com/82445185/196846902-e9ea2f8f-32a4-49e0-b27f-cb67b3a988c0.png)

![image](https://user-images.githubusercontent.com/82445185/196846962-04c2a4d9-f3e9-4aa4-b95e-c40c30fcb036.png)
![image](https://user-images.githubusercontent.com/82445185/196847004-1242c7ae-58ce-4557-9c78-0679917ef917.png)
![image](https://user-images.githubusercontent.com/82445185/196847037-20e15abe-718f-4a11-a841-096259a95c5b.png)


![image](https://user-images.githubusercontent.com/82445185/196847073-4c909830-fb22-4b93-b55f-4dbeeb7ab9de.png)




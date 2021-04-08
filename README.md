# Customer_Segmentation

An automobile company has plans to enter new markets with their existing products.

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers.

I'm required to help the manager to predict the right group of the new customers.

# Goals of the project

1. Perform an Explorartory Data Analysis with visualization 
2. Use the supervised machine learning models to predict the customer segmentation
3. Use unsupervised learning model K Nearest Neighbors to create new clusters.
4. Create Personas of the new clusters. 

# Tools used
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Time
* scikit-learn
  * Supervised learning models for classfication:
    * Support Vector Machine
    * Gradient Boosting Classifier
    * Light Gradient Boosting Classifier
    * Ada Boost
    * Cat Boost
    * Decision Tree
    * Random Forest
    * Logistic Regression
    * KNeighbors
    * Naive Bayes Gaussian
  * Unsupervised Learning model for clustering:
    * K-Means    

# Resources
Customer Segmentation
https://www.kaggle.com/vetrirah/customer

# Classification models performance

The best performers modesl are: 
  * Gradient Boosting Classifier: 
     * Accuaracy: 53.62% - Preccision: 52.77% - F1 score:  53% - Recall: 52.49%
     
       <img src="https://user-images.githubusercontent.com/73388089/114066452-0b7d1900-989c-11eb-9c68-e1eb90c714bd.png" alt="Gradient Boosting Classifier" width="300" height="250">
       
  * Light Gradient Boosting Classifier:      
     * Accuaracy: 52% - Preccision: 49.86% - F1 score: 49.75% - Recall: 50%     
       
       <img src="https://user-images.githubusercontent.com/73388089/114066689-48e1a680-989c-11eb-87e5-171c06b9249e.png" alt="Gradient Boosting Classifier" width="300" height="250">


# K-Means cluster Personas creation

After clustering the datapoints in four clusters I came up with the below Personas:

![Customer Segmentation Personas](https://user-images.githubusercontent.com/73388089/114074814-17b9a400-98a5-11eb-8f58-a0f01aceea94.jpg)


# Process
1. Exploratory Data Analysis
   * Clean the dataset
   * Create visualizations
2. Feature Engineering
   * Create Dummies.
   * Scaling
   * Feature selection SFS and RFE
   * PCA
3. Modeling for Classification. we select the model with better performance (Gradient Boosting Classifier - Light Gradient Boosting Classifier)

4. Hyper Tunning of the (Gradient Boosting Classifier - Light Gradient Boosting Classifier

5. Clustering with Kmeans

6. Create Personas

7. Create Story telling

# Presentation
To see the presentation, click in the below picture.

[<img src="https://user-images.githubusercontent.com/73388089/114032866-0492de00-987d-11eb-9609-31cb62479a73.png" alt="Test_VS_Prediction" width="400" height="330">](https://github.com/isra-st/london_bike_sharing/files/6278860/London_bike_sharing_presentation.pptx)



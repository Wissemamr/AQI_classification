# Air Quality Index  (AQI) Multiclass Classification : 

This repository contains the implementation of the Machine learning project which consists of 3 major parts : 
1. Performing exploratory data analysis on a chosen dataset, including data wrangling, cleaning etc.
2. Implementing different classification algortihms and evaluating their perofrmance.
3. Benchmarking the classification results and interpreting them.


## Dataset : 
I chose the **World Air Quality Index by City and Coordinates** on Kaggle

(click here to obtain it :
 <https://www.kaggle.com/datasets/adityaramachandran27/world-air-quality-index-by-city-and-coordinates> 
 )



## Exploratory Data Analysis : 
- Understadning the structure of the data
- Handling missing and duplicated values
- Understanding the data distribution
- Exploring categorical values and encoding them
- Data visualization
- Feature Engineering
- Pollars alternative 


## Classification Algorithms :

I chose 10 different classification algortihms. In each one, I experimented with different techniques to enhance the results of the classification, like normalizing and scaling the data, performing hyperparamter tuning, using resampling techhniques to mitigate class imbalance etc.

1. #### K-Nearest Neighbors 
2. #### Logistic regression   
3. #### Decision Trees 
4. #### Random Forests  
5. #### Support Vector Machine 
6. #### Naive Bayes
7. #### Neural Networks  
8. #### Gradient Boosting Machine 
9. #### Linear Descrimant Analysis 
10. #### XGBoost 



## Benchmarking results

| Algorithms                       | `Accuracy` |`Recall`    | `Precision`| `F1-score` |
|--------------------------------  |---------   |--------    |----------- |----------  |
| **K-Nearest-Neighbour**          | **0.9902** | **0.9902** | **0.9908** | **0.9891** |
| **Decision Trees**               | **0.9979** | **0.9979** | **0.9983** | **0.9978** |
| **Random Forests**               | **0.9972** | **0.9961** | **0.9971** | **0.9961** |
| **Naive Bayes**                  | **0.4570** | **0.4570** | **0.6317** | **0.4009** |
| **Support Vector Machine**       | **0.9926** | **0.9926** | **0.9928** | **0.9968** |
| **Logistic Regression**          | **0.9740** | **0.9740** | **0.9753** | **0.9703** |
| **Neural Networks**              | **0.8507** | **0.8507** | **0.8726** | **0.8442** |
| **Gradient Boosting Machine**    | **0.9968** | **0.9968** | **0.9973** | **0.9967** |
| **Linear Descriminant Analysis** | **0.9796** | **0.9796** | **0.9805** | **0.9793** |
| **XGBoost**                      | **0.9982** | **0.9982** | **0.9985** | **0.9980** |









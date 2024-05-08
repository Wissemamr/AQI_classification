# AQI_classification : 
-----

This repository contains the implementation of the Machine learning project which consists of two major parts : 
- Performing exploratory data analysis on a chosen dataset, including data wrangling
- Benchmarking different classification algortihms


## Dataset : 
We chose the **World Air Quality Index by City and Coordinates** on Kaggle

(click here to obtain it :
 <https://www.kaggle.com/datasets/adityaramachandran27/world-air-quality-index-by-city-and-coordinates> 
 )

### Exploratory Data Analysis : 
- Introduction to `Polars` library
- Understanding the strucure of our data
- Handling missing and duplicated values
- Exploring categorical values
- Data visualization
- Feature Engineering


## Classification Algortihms :

I chose 10 different classification algortihms. In each one, I experimented with different techniques to enhance the results of the classification, like normalizing adns scalin gthe data, performing hyperparamter tuning, using resampling techhniques to mitigate class imbalance etc.

1. ### K-Nearest Neighbors :
2. ### Logistic regression :  
3. ### Decision Trees : 
4. ### Random Forests : 
5. ### Support Vector Machine :
6. ### Naive Bayes : 
7. ### Neural Networks : 
8. ### Gradient Boosting Machine :
9. ### Linear Descrimant Analysis :
10. ### XGBoost : 



## Benchmarking results

| Algorithms                     | Accuracy   | Recall     | Precision  | F1-score   |
|--------------------------------|---------   |--------    |----------- |----------  |
| `K-Nearest-Neighbour`          | **0.9888** | **0.9888** | **0.9892** | **0.9881** |
| `Decision Trees`               | **0.9989** | **0.9989** | **0.9991** | **0.9988** |
| `Random Forests`               | **0.9979** | **0.9975** | **0.9988** | **0.9984** |
| `Naive Bayes`                  | **0.4622** | **0.4622** | **0.5970** | **0.4262** |
| `Support Vector Machine`       | **0.9940** | **0.9940** | **0.9943** | **0.9938** |
| `Logistic Regression`          | **0.9729** | **0.9733** | **0.9740** | **0.9702** |
| `Neural Networks`              | **0.8507** | **0.8507** | **0.8726** | **0.8442** |
| `Gradient Boosting Machine`    | **0.9993** | **0.9993** | **0.9994** | **0.9993** |
| `Linear Descriminant Analysis` | **0.9817** | **0.9817** | **0.9827** | **0.9814** |
| `XGBoost`                      | **0.9996** | **0.9996** | **0.9997** | **0.9995** |









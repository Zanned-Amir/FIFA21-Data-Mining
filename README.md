# FIFA 21 Data Mining Academic Project

## Introduction
In this academic project, we aim to predict the potential of football players in FIFA 21 using various machine learning models. We will begin by cleaning and exploring the dataset, followed by building predictive models. Finally, we will select the most performant model and use it to recommend teams based on player potential.

## Data Preparation
### Cleaning Data
We start by cleaning the dataset to remove any inconsistencies or missing values that may affect the accuracy of our models. This step ensures the data quality before proceeding with analysis.

[Link to Data Cleaning ](datacleaning.ipynb)

### Exploratory Data Analysis (EDA)
Next, we conduct exploratory data analysis to gain insights into the dataset. This includes visualizing distributions, correlations, and identifying patterns that may influence player potential.

[Link to EDA ](eda.ipynb)

## Model Building
### Feature Selection
Before building predictive models, we select relevant features that are likely to impact player potential. This involves analyzing the importance of each feature and selecting the most informative ones for our models.

### Model Selection
We experiment with several machine learning models:

- Linear Regression
- K-Nearest Neighbors Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression
- AdaBoost

Each model is trained and evaluated using appropriate metrics to determine its performance in predicting player potential.

### Clustering
In addition to predictive modeling, we apply K-Means clustering to group players based on similar characteristics. This can help in identifying player clusters with similar potential or playing styles.

### Similarity Scoring
We also utilize cosine similarity scoring to measure the similarity between players based on their attributes. This allows us to recommend similar players or teams based on player characteristics.

### Evaluation Metrics
We utilize metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-squared, and silhouette score (for clustering) to evaluate the performance of each model and clustering technique.

## Selecting the Best Model
Based on the evaluation results, including both predictive performance and clustering quality, we identify the models and techniques that demonstrate the highest accuracy and usefulness in predicting player potential and clustering players effectively.

## Conclusion
In conclusion, this project demonstrates the application of data mining techniques to predict player potential in FIFA 21. By leveraging machine learning models and data analysis, we can provide valuable insights for team selection and optimization in the virtual football world.

# How to Develop an End-to-End Machine Learning Project and Deploy it to Heroku with Flask
Credits: https://www.freecodecamp.org/news/end-to-end-machine-learning-project-turorial/

## Download Dataset from below site
https://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/
The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes


Predicting Fuel Efficiency of Vehicles

1. Data Collection - we are using the classic Auto MPG dataset from UCI ML Repository.
2. Define Problem Statement - We'll frame the problem based on the dataset description and initial exploration.
3. EDA - Carry our exploratory analysis to figure out the important features and creating new combination of features.
4. Data Preparation - Using step 4, create a pipeline of tasks to transform the data to be loaded into our ML models.
5. Selecting and Training ML models - Training a few models to evaluate their predictions using cross-validation.
6. Hyperparameter Tuning - Fine tune the hyperparameters for the models that showed promising results.
7. Deploy the Model using a web service - Using Flask web framework to deploy our trained model on Heroku


## Predicting Fuel Efficiency Part - 1
### Understanding the data and relations
1. Data Collection - we are using the classic Auto MPG dataset from UCI ML Repository.
2. Define Problem Statement - We'll frame the problem based on the dataset description and initial exploration.
3. EDA - Carry our exploratory analysis to figure out the important features and creating new combination of features.

## Predicting Fuel Efficiency Part - 2 
### Data Preparation using Sklearn

1. Handling Categorical Functions - OneHotEncoder
2. Data Cleaning - Imputer
3. Attribute Addition - Adding custom transformation
4. Setting up Data Transformation Pipeline for numerical and categorical column.

## Predicting Fuel Efficiency Part - 3
### Selecting and Training Models

1. Select and Train a few Algorithms(Linear Regression, Decision Tree, RandomForest)
2. Evaluation using Mean Squared Error
3. Model Evaluation using Cross Validation
4. Hyperparameter Tuning using GridSearchCV
5. Check Feature Importance
6. Evaluate the Final System on test data
7. Saving the Model


## Predicting Fuel Efficiency - Part 4
### Deploying the Trained Model
Refer [flask app](https://github.com/pranavnijampurkar33/ml-heroku-flask-fuel-consumption/tree/main/ml_flask_app)

1. Start a Flask Project.
2. Set up a dedicated environment with dependencies installed using pip.
  Packages to install:
    * pandas
    * numpy
    * sklearn
    * flask
    * matplotlib
    * gunicorn
    * seaborn
3. Create a quick flask application to test a simple endpoint.
4. Define a function to that accepts data from the POST request and return the predictions using a helper module.
5. Test the endpoint using requests package


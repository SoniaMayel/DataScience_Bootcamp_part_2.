## Project 7

- 📊 **Supervised Machine Leraning**: A project involving Supervised MAchine Learning using Python's Scikit-Learn library.
    
- 📑 **Case Study**:

In this project I worked for a consultancy specialising in real estate: my clients include developers, agencies, and investors. Pricing is a central aspect to the business. Traditionally, it’s the domain of home appraisers to determine the value of a property, which must be executed in an unbiased way, following an official criteria to ensure that there is no favour towards either the buyer or the seller.

#I was tasked with creating a model that predicts the price of a house based on its characteristics.

- 💻 **Project Setup**:  

- The project is divided into two major phases:

1. Create a model to predict whether a house is expensive or not. 
2. Create a model to predict the exact price of a house.

In the first phase, the model I built had a categorical target: 'Expensive' and 'Not expensive'. Whenever an ML task involved a categorical target variable, it was called a classification task. In the second phase of the project, the target variable was numerical (the exact prices of the houses in dollars): I was dealing with a regression task."
    

### Data Collection

Data from Kaggle Housing Data

### Data cleaning

1. Cleaned data set

2. Dropped NaN values more then 90%

3. Predicted Traget and split data into Train-test 

### working on Categorical and Numerical columns
(Encoding - "Automated" approach (Using Pipeline))

1. Selected the numerical columns and fill Nan values by Mean

2. Selected the categorical columns

3. Fitted a OneHotEncoder

4. Transformed the categorical columns with the encoder

### Data Scaling methods

1. MinMaxScalar

2. StandardSCalar

### Preprocessing

Used ColumnTransformer a pipeline with 2 branches

### Full_pipeline

1. Created the the pipeline (preprocessor + model)

2. Predicted the target


### There was an additional small project for the Mushroom competition.
find it in "Mashroom competition" folder
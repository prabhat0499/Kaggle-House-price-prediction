### Kaggle-House-price-prediction
### Advanced regression techniques to find the price of the Houses 

### Exploratory Data Analysis [EDA]
### Remember: EDA is to gather information from the dataset, so that's why we will always have to compare with the dependent variable.

## In Exploratory Data Analysis, we will analyze to find out:
#### Missing Values
#### Numerical variables(both discrete and continous)
#### Distribution of Numerical features(Since it is a regression problem)
#### Categorical variables
#### Cardinality of Categorical varibles
#### Outliers
#### Relationship between independent and dependent variables
### NOTE: In this problem statement, we will only do data analysis on Training dataset.


### Temporal Variable or Datetime variable
#### Here in our numerical features, we can see there are some attributes with Years.
#### Year information must be handled carefully.
#### We need to analyze those Year_info to check the relationship with the Target variable.

## Discrete and Continous variables(Numerical Features)
#### Numerical variables are usually of two types:
#### Discrete variable
#### Continous variable
#### A discrete variable is a variable whose value is obtained by counting. A continuous variable is a variable whose value is obtained by measuring.
Continuous data are data which can take any values. Examples include time, height and weight. Because continuous data can take any value, there are an infinite number of possible outcomes. So continuous data must be grouped before they can be represented in a frequency table or statistical diagram.
Discrete data is information that can only take certain values. ... Continuous data is data that can take any value. Height, weight, temperature and length are all examples of continuous data.
Discrete value - either it is 4 or 5 , its not 4.5 or 4.9....it's a specific quantam value.
-----------------------------

### We will not remove outliers from every feature as it may affect the model since test set will have outliers too and our model needs to be robust against them
### Categorical Variables
Categorical variables are those values in a dataset that contains different unique categories.
Categorical Variables are of two types:

### Nominal variables: Unordered variables which doesn't have any sense of Order. For Example:

###### male/female
###### smoker/non-smoker
###### sunny/cloudy/rainy/windy/icy (There is no logic to rank windy before sunny)
yes/no or True/False
###### NOTE: USE ONE HOT ENCODING.
Ordinal variables: Ordered variables which have some sense of order or rank or notion of order. For Example:

###### Education level(BE,ME,Phd)
Shirt size(XS,S,M,L,XL)
1/2/3/4/(minimal/moderate/severe/unbearable pain)
###### NOTE: USE LABEL ENCDOING

------------------------------------

## Algorithm Used : Random Forest 

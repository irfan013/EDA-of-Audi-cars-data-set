# Analysis of Audi cars dataset
Here a sample dataset of used Audi cars was used. Several analyses were done based on this data.

Dataset source: https://www.kaggle.com/aishwaryamuthukumar/cars-dataset-audi-bmw-ford-hyundai-skoda-vw

## Descriptions of the dataset
### Dependent variable
- Price: Price of the cars

### Independent variables (features)
- model: Model of the cars defined by Audi
- year: Specific year when the car was built
- transmission: Type of gearboxes used in the car
- mileage: the number of miles the car has been driven
- fuelType: Type of fuel can be used for this car
- tax: Road tax in Dollar
- mpg: miles per gallon
- engineSize: Size of car's cylinders, measured in cubic centimetres (cc)

## Exploratory Data Analysis
### Analysis performed
- Data analysis using NumPy, Pandas and Seaborn
- Barplot
- Subplots
- Scatterplot
- Histogram
- Cumulative distribution plot
- boxplot
- Using loop, functions for tidy coding
- Pivot table usuage to answer specfic questions
- Barplots usuage for more exploration of data to answer specfic questions 

## Implementing Machine Learning to Audi cars dataset
### Analysis performed (fitting a liner regression with numerical features only)
- Separating the numeric features and target variable
- Spliting the original dataset into the train set (80%) and the test set (20%)
- Performing Linear Regression and predicting the 'Price' from the test set
- Finding the RMSE value from the actual test data and the predicted data
### Analysis performed (fitting a liner regression with all the available features)
- Performing Label Encoding or One-hot Encoding
- Spliting the original dataset into the train set (80%) and the test set (20%)
- Performing Linear Regression and predicting the 'Price' from the test set
- Showing the coefficients of the linear regression model for each feature and the y-intercept value of the linear regression model with interpretation
- Finding the MAE, MAPE, MSE, RMSE, coefficient of determination values from the actual target variable and the predicted target variable
- Comparing the actual and predicted target variable through visualization

Update: 2nd October 2021

# Analysis-of-House-Sales-in-King-County
Final Project for Data Analysis with Python - Course 6/9 of IBM Data Science Professional Certificate

This notebook contains four main parts:
1) Data Wrangling:
- Clean up NaN values 
- Drop unnecessary columns in the dataframe

2) Exploratory data analysis
- Plot figures to have a sense of outliers and correlations between variables
- Find out which feature variable is most correlated with the target ('price')

3) Model development
- Use linear regression models to predict 'price' based on different features
- Build a pipeline object to predict 'price' 
- Use R^2 to assess the accuracy of predictions

4) Model evaluation and refinement
- Use scikit-learn to split the dataset into training and test sets
- Create a Ridge regression object with regularization parameter = 0.1 to prevent overfitting
- Perform 2nd order polynomial transform on the training & test data, then fit a Ridge regression object in the training data
- Calculate R^2 to assess the accuracy of predictions

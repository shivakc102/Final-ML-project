# Final-ML-project
## project title
- Problem 1 : Predict the price of a used car 
- problem 2 : Predict the quality of the wine based on given attributes
- problem 3 : Predict the rating of a restaurant[Zomato Restaurants Rating]

##  PROJECT DESCRIPTION
In this project, the provided data has been analyzed and preprocessed before constructing the machine learning model. The preprocessing steps involve identifying and handling missing values by imputing mean , meadian and mode. Additionally, any categorical variables are transformed into numerical  for computational purposes. Do feature scaling for models such as linear regression , logistic regression etc. Outliers are categorized into two types: errors and anomalies. If an outlier is identified as an error, it is removed .After preprocessed the data is split into training and testing sets, and the chosen machine learning algorithm is applied to determine the optimal model.

## Tools installed
- Jupyter(Notebook)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib and seaborn

## Workflow in this project
### preprocessing
- Analyze the given data to identify missing values, data types, etc. 
- After the analysis, remove duplicates and unwanted columns, dropping any null values in the dataset. 
- Following this, check if there are still missing values. These missing values can be filled using methods    like mean, median, etc., based on the data.
- After cleaning, there are no missing values. Next, analyze the data to determine the number of categorical and numerical columns. 
- If there are categorical columns, encode them numerically for computational purposes.
- Identify outliers in the data, considering two types: errors and anomalies. For errors, remove or replace them with appropriate values.
- Feature scaling is employed to adjust the magnitude or scale of numerical values, particularly for certain algorithms.
- preprocessing steps are crucial for machine learning algorithms and significantly contribute to improving their performance.

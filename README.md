# Real-Estate-Price-Prediction
This project aims to predict the prices of houses in a given area using a machine learning model. The dataset used in this project is sourced from https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data, and it includes information about various features of houses, such as the number of bedrooms, bathrooms, square footage, and more.

## Technologies Used
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## Data Cleaning
The dataset used in this project was cleaned and preprocessed to remove missing values, outliers, and inconsistencies that may affect the accuracy of the machine learning model.
### Handling Missing Values
The dataset contains missing values in some of the features, such as the number of bedrooms, bathrooms, and square footage. To handle these missing values, we used different techniques depending on the type of missingness. For example, the missing values in categorical variables with the mode or the most frequent category, and  imputation techniques such as mean, median, or regression imputation for numerical variables were used.
### Removing Outliers
Outliers are observations that are significantly different from the other observations in the dataset and can affect the performance of the machine learning model. In this project, different techniques were used to detect and remove outliers. Also, visualized the distribution of each feature using histograms and scatterplots to identify potential outliers.

![](https://github.com/sharma-bhavya/Real-Estate-Price-Prediction/blob/main/images/bhhp_graph.PNG)

### Encoding Categorical Variables
The dataset contains categorical variables, that needed to be encoded before feeding it into the machine learning model. One-hot encoding was used to transform these categorical variables into numerical features that the model can understand.

## Feature Selection and Engineering
To improve the performance of the machine learning model, feature selection and engineering techniques were performed to select the most relevant features and transform them into meaningful representations. 

## Model Selection and Evaluation
In this project, regression algorithms, including linear regression, decision tree regression, and random forest regression were used to predict the prices of houses. The performance of each model was evaluated using mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2) metrics. We also used k-fold cross-validation to prevent overfitting and ensure that the model can generalize well to new data.

## Conclusion
The machine learning model achieved 85% accuracy, and we conclude that it is capable of accurately predicting the prices of houses based on the selected features. 

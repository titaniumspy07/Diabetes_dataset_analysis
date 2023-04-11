# _Lab Test 2 For Predictive Analytics_

# Objective of assignment
- [x] Read and analyze the PIMA Indians Diabetes dataset (EDA)
- [x] Build KNN and logistic regression model
- [x] Check for best performance configurations (Hyperparameter tuning)
- [x] ross-validate both models (10-fold cross-validation)
- [x] Check for maximum performance metrics using ROC-AUC value and Matthew's correlation coefficient

# PIMA Indians Diabetes Dataset Analysis
This assignment aims to perform _exploratory data analysis_ on the PIMA Indians Diabetes dataset and build a _K-Nearest Neighbors_ (KNN) classifier to predict whether or not a patient has diabetes.

## Data Description
The PIMA Indians Diabetes dataset consists of 768 observations with 8 input features and 1 binary output variable indicating whether or not the patient has diabetes. The input features include the patient's age, number of pregnancies, glucose concentration, blood pressure, skin thickness, insulin level, body mass index (BMI), and diabetes pedigree function. The dataset can be found here -
"https://raw.githubusercontent.com/Bits-Deep-Analytics/Predictive_analytics/dev/Data/PIMA/diabetes.csv".

## Exploratory Data Analysis (EDA)
The EDA was performed using the following steps:

1. Load the dataset and display the first 5 rows
2. Display the information about the data
3. Display the descriptive statistics of the data
4. Calculate the interquartile range (IQR) and remove outliers
5. Visualize the distribution of the glucose concentration and its relationship with the outcome variable using a histogram and a box plot
5. Visualize the relationship between age and BMI by outcome variable using a scatter plot
6. Create a correlation matrix and visualize it using a heatmap
7. Find highly correlated variables and remove one of the variables from each highly correlated pair
8. Create a pie chart to show the distribution of the outcome variable

## KNN Classifier
The KNN classifier was built using the following steps:

1. Load the dataset and split it into features (X) and target variable (Y)
2. Perform Z scaling on the features using StandardScaler
Split the dataset into training and testing sets using train_test_split
3. Train a KNN classifier on the training set and perform 10-fold cross-validation to evaluate its performance
4. Print the mean and standard deviation of the cross-validation scores
5. Train the KNN classifier on the entire training set and predict the target variable on the testing set
6. Compute and print the confusion matrix and accuracy score
Display the confusion matrix using ConfusionMatrixDisplay

### Conclusion
The EDA revealed that some of the input features are highly correlated, which can affect the performance of the classifier. Therefore, it is important to remove one of the variables from each highly correlated pair. The KNN classifier achieved an accuracy of 72.08% on the testing set, which can be improved by using more advanced machine learning models and feature engineering techniques.

## Contributing
Contributions are always welcome!

## Authors
- [@Aman Kumar Tiwary](https://github.com/titaniumspy07)
- [@Prerit Singh](https://github.com/prerit107)
- [@Shriya Mishra](https://github.com/Shriya06mishra)
- [@Jayant Jain](https://github.com/jayant-bits05)

## License
[MIT](https://choosealicense.com/licenses/mit/)


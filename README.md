# lab_test_2
PIMA Indians Diabetes Dataset Analysis
This project aims to perform exploratory data analysis on the PIMA Indians Diabetes dataset and build a K-Nearest Neighbors (KNN) classifier to predict whether or not a patient has diabetes.

Data Description
The PIMA Indians Diabetes dataset consists of 768 observations with 8 input features and 1 binary output variable indicating whether or not the patient has diabetes. The input features include the patient's age, number of pregnancies, glucose concentration, blood pressure, skin thickness, insulin level, body mass index (BMI), and diabetes pedigree function. The dataset can be found here.

Exploratory Data Analysis (EDA)
The EDA was performed using the following steps:

Load the dataset and display the first 5 rows
Display the information about the data
Display the descriptive statistics of the data
Calculate the interquartile range (IQR) and remove outliers
Visualize the distribution of the glucose concentration and its relationship with the outcome variable using a histogram and a box plot
Visualize the relationship between age and BMI by outcome variable using a scatter plot
Create a correlation matrix and visualize it using a heatmap
Find highly correlated variables and remove one of the variables from each highly correlated pair
Create a pie chart to show the distribution of the outcome variable
KNN Classifier
The KNN classifier was built using the following steps:

Load the dataset and split it into features (X) and target variable (Y)
Perform Z scaling on the features using StandardScaler
Split the dataset into training and testing sets using train_test_split
Train a KNN classifier on the training set and perform 10-fold cross-validation to evaluate its performance
Print the mean and standard deviation of the cross-validation scores
Train the KNN classifier on the entire training set and predict the target variable on the testing set
Compute and print the confusion matrix and accuracy score
Display the confusion matrix using ConfusionMatrixDisplay
Conclusion
The EDA revealed that some of the input features are highly correlated, which can affect the performance of the classifier. Therefore, it is important to remove one of the variables from each highly correlated pair. The KNN classifier achieved an accuracy of 72.08% on the testing set, which can be improved by using more advanced machine learning models and feature engineering techniques.

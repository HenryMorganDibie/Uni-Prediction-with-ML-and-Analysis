# Uni-Prediction-with-ML-and-Analysis
## Here's a summary of the steps I took to train an SVM model on the college acceptance dataset:

* Import libraries and load data: I started by importing the necessary libraries and loading the college acceptance dataset into a pandas DataFrame.

* Exploratory data analysis (EDA): I performed some exploratory data analysis to gain insights into the dataset and check for any missing values, outliers, or other issues that need to be addressed before training the SVM model.

* Preprocessing: I preprocessed the dataset by encoding categorical variables, scaling the numeric features, and splitting the data into features (X) and target (y).

* Train-test split: We split the preprocessed data into training and testing sets using train_test_split from sklearn.model_selection.
* Training the SVM model: I trained the SVM model on the training data using svm_model = SVR(kernel='rbf', C=100, gamma='auto') from sklearn.svm. 
* Evaluating the SVM model: I evaluated the performance of the SVM model on the testing data by making predictions using the predict method and calculated the mean squared error (MSE) as a measure of the model's performance. I used multiple metrics to evaluate the model's performance like RMSE,R2, and MAE

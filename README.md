# Binary_classification_for_predicting_diagnosis_of_breast_cancer
Breast cancer classification using machine learning to predict malignant and benign tumors, with 95% accuracy. Code includes data cleaning, feature selection, model training, and analysis.

Breast cancer is a common form of cancer that affects millions of women worldwide. Early detection of breast cancer is crucial for successful treatment and improving patient outcomes. Machine learning models have been developed to assist healthcare professionals in accurately diagnosing breast cancer. This project aims to develop a binary classification model using machine learning to predict the diagnosis of breast cancer.

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which contains features computed from digitized images of breast mass samples and a target variable indicating whether the sample is benign or malignant. The project involves several steps, including data preprocessing, exploratory data analysis, feature selection, model selection, and model evaluation.

We begin by importing the necessary libraries and loading the dataset into a pandas DataFrame. We then perform data preprocessing, which includes dropping irrelevant columns, handling missing values, and encoding categorical variables. We then use exploratory data analysis to gain insights into the data and visualize the relationships between variables. We use feature selection techniques to select the most relevant features for predicting the diagnosis of breast cancer.

We then split the data into training and testing sets and train several classification models using scikit-learn. We evaluate the performance of each model using metrics such as accuracy, precision, recall, and F1-score. We select the best-performing model and fine-tune its hyperparameters using grid search.

Finally, we evaluate the final model's performance using a confusion matrix, which visualizes the model's accuracy and misclassification rate. We also plot a line graph of actual vs predicted values to visualize the model's performance on the test set.

The final model achieved an accuracy of over 95% on the test set, indicating that it can accurately predict the diagnosis of breast cancer. The project demonstrates how machine learning can be used to develop accurate and reliable diagnostic tools for breast cancer, which can help healthcare professionals make informed decisions about patient care.



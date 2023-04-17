# Mobile-Price-Classification-Kaggle
Classify mobile price range into 4 ranges using SVM and PCA technique

Great job on creating a classification model for the Price Mobile dataset and preparing to share it on GitHub! Here's a template README file you can use as a starting point:

Price Mobile Classification
This repository contains code for a classification model that predicts the price range of a mobile phone based on its features. The dataset used for this project was downloaded from Kaggle.com.

Dataset
The dataset used for this project contains information on various mobile phone features such as battery power, clock speed, 3G enabled, wifi enabled, etc. The target variable is the price range of the mobile phone, which is divided into four categories: low cost, medium cost, high cost, and very high cost.

Preprocessing
Before building the classification model, the dataset was preprocessed by first plotting the data to get a better understanding of the distribution of the features. Then, the features were scaled using the StandardScaler from scikit-learn to ensure that each feature had equal weight in the model.

Classification
The classification model was built using a support vector machine (SVM) algorithm with the best parameters determined through grid search. The accuracy of the model on the test set was near 96%.

Usage
To use this code, simply clone the repository and run the price_classification.py file. The script will preprocess the data, train the SVM model, and output the accuracy of the model on the test set.

Dependencies
This code requires Python 3 and the following libraries:

scikit-learn
pandas
matplotlib
Credits
This project was completed by [Your Name] as part of [Course/Project Name]. The dataset used for this project was obtained from Kaggle.com.

Feel free to modify this template to better suit your needs and add any additional information that you think would be helpful for users who are interested in your project. Good luck!

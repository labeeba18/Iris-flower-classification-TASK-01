# Iris-flower-classification-TASK-01
🌸 IRIS FLOWER CLASSIFICATION USING MACHINE LEARNING

   
Introduction

Iris flower classification is a popular machine learning classification problem. The Iris flower has three species, namely Setosa, Versicolor, and Virginica. These species differ based on certain physical measurements of the flower. The objective of this project is to build a machine learning model that can correctly classify the species of an iris flower using its measurements.




Problem Statement

The main problem is to predict the species of an iris flower based on four input features:

Sepal length

Sepal width

Petal length

Petal width

This is a supervised learning problem because the dataset contains labeled data, and it is a multiclass classification problem since there are three different output classes.







Dataset Description

The Iris dataset is used for this project. It contains 150 samples, with 50 samples for each species.
The dataset has five columns:

Four columns represent flower measurements (features)

One column represents the species (target)

The dataset is clean, well-structured, and commonly used for learning classification algorithms.





Methodology

First, the dataset is loaded using the pandas library. The input features and output labels are separated. Since machine learning models cannot understand text labels, the species names are converted into numerical values using Label Encoding.

The dataset is then divided into training data and testing data using the train-test split method. The training data is used to train the model, while the testing data is used to evaluate its performance.





Model Used

A Random Forest Classifier is used to train the model. Random Forest is an ensemble learning method that uses multiple decision trees and combines their results to improve accuracy and reduce overfitting. It is efficient, reliable, and works well for classification problems.





Model Evaluation

After training, the model is evaluated using:

Accuracy score

Confusion matrix

Classification report

The model achieves high accuracy, showing that it can correctly classify iris flowers based on their measurements.





Prediction

The trained model is also tested with new flower measurements. The model successfully predicts the correct species, which proves its practical applicability in real-world scenarios.






Technologies Used

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook







Conclusion

In conclusion, the Iris Flower Classification project successfully demonstrates the use of machine learning for classification problems. The Random Forest model accurately predicts flower species based on given measurements. This project helps in understanding data preprocessing, model training, evaluation, and prediction, making it an ideal project for beginners in machine learning.

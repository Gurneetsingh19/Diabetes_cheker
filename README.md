Diabetes Prediction System
This project is a Machine Learning model developed to predict the likelihood of diabetes in patients based on clinical parameters.

Model Development Process
During the development phase, multiple machine learning algorithms were tested and evaluated to ensure the highest reliability. The following algorithms were implemented:

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Logistic Regression

After rigorous testing, Logistic Regression outperformed the other models, providing the highest accuracy. Consequently, the final code and the saved model files in this repository are based on the Logistic Regression algorithm.

Project File Structure
The repository contains the following key files:

Diabetes_cheker.ipynb: This is the main Jupyter Notebook containing the complete end-to-end workflow, including data preprocessing, feature analysis, and the model training logic using Logistic Regression.

dibates.joblib: This is the final trained model file. It has been exported using the Joblib library so that it can be loaded directly for making predictions without retraining.

diabetes (1).csv: The original dataset used for training and testing the model. It contains the medical features and the target labels.

LICENSE: This file specifies the terms under which this project’s code and assets can be used or distributed.

.gitattributes: A configuration file used by Git to handle specific file types and line endings correctly.

How to Use
To run this project locally, you will need Python and the following libraries installed:

pandas

scikit-learn

joblib

You can load the model in your Python script using:

Python
import joblib
model = joblib.load('dibates.joblib')


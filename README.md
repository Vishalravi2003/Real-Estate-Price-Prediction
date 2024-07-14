# Real-Estate-Price-Prediction
Project Overview
This data science project series walks through the step-by-step process of building a real estate price prediction website. The project consists of three main components:

Model Building: Using the Bangalore home prices dataset from Kaggle, we build a prediction model using sklearn and linear regression.
Backend Development: Writing a Python Flask server that utilizes the saved model to handle HTTP requests.
Frontend Development: Creating a website with HTML, CSS, and JavaScript that allows users to input home details and retrieve predicted prices from the Flask server.
Project Components
1. Model Building
Data Loading and Cleaning: Utilizing numpy and pandas to load and clean the dataset.
Outlier Detection and Removal: Identifying and removing outliers to improve model accuracy.
Feature Engineering: Creating new features to enhance model performance.
Dimensionality Reduction: Applying techniques to reduce the number of features while retaining important information.
Model Training: Using sklearn to build a linear regression model.
Hyperparameter Tuning: Utilizing GridSearchCV for optimizing model parameters.
Model Evaluation: Employing k-fold cross-validation to assess model performance.
2. Backend Development
Flask Server: Developing a Python Flask server that loads the trained model and serves HTTP requests.
API Endpoints: Creating endpoints to receive user inputs and return predicted prices.
3. Frontend Development
User Interface: Building a responsive UI using HTML, CSS, and JavaScript.
User Inputs: Allowing users to enter home square footage, number of bedrooms, etc.
Prediction Retrieval: Making AJAX calls to the Flask server to get price predictions.
Technologies and Tools
Programming Language: Python
Data Cleaning: Numpy, Pandas
Data Visualization: Matplotlib
Model Building: Sklearn
IDEs: Jupyter Notebook, Visual Studio Code, PyCharm
Backend: Python Flask
Frontend: HTML, CSS, JavaScript
Installation and Setup
Prerequisites
Python 3.x
Pip (Python package installer)

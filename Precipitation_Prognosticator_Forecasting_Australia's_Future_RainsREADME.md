Rain Prediction with Decision Trees and Random Forests

Overview

This project aims to predict whether it will rain tomorrow at a given location based on historical weather data. The dataset used for this task contains approximately 10 years of daily weather observations from various Australian weather stations. The project utilizes decision trees and random forests, two popular machine learning algorithms, to tackle this real-world problem.

Problem Statement

As a data scientist at the Bureau of Meteorology, the task is to develop a fully-automated system capable of predicting whether it will rain at a specific location tomorrow. To achieve this, historical weather data will be analyzed and used to train machine learning models, primarily employing decision trees and random forests.

Approach

The project follows these key steps:

Data Collection: The dataset is obtained from Kaggle, containing weather data from various Australian weather stations over ten years.
Data Preprocessing:
Handling missing values: Missing numeric values are imputed using the mean, and categorical values are handled appropriately.
Scaling numeric features: Numeric features are scaled to a range of [0, 1] using Min-Max scaling.
Encoding categorical features: Categorical features are one-hot encoded for compatibility with machine learning models.
Model Training:
Decision Trees: A decision tree classifier is trained on the preprocessed data to predict rain tomorrow.
Random Forests: A random forest classifier is also trained to compare performance with decision trees.
Model Evaluation:
The accuracy score and confusion matrix are used to evaluate model performance on training and validation data.
Future Work:
Exploration of additional models and feature engineering techniques.
Integration of recent climate data for more accurate predictions.
Requirements

The project relies on several Python libraries, including pandas, numpy, matplotlib, seaborn, scikit-learn, and Jupyter Notebook for code execution and visualization.

Getting Started

Clone Repository: Clone this repository to your local machine.
Install Dependencies: Install the required Python libraries by running pip install -r requirements.txt.
Run Jupyter Notebook: Open the Jupyter Notebook provided (rain_prediction.ipynb) to execute the code and explore the project.
Download Dataset: The dataset used in this project can be downloaded from Kaggle using the provided link in the notebook.
Execute Code Cells: Run each code cell in the notebook sequentially to perform data preprocessing, model training, and evaluation.
Conclusion

This project demonstrates the application of decision trees and random forests in predicting rain based on historical weather data. By leveraging machine learning techniques, it aims to provide valuable insights for weather forecasting and related applications.

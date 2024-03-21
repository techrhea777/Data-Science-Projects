# Random Forest Feature Selection and Correlation Analysis

This project involves generating a random dataset, performing feature selection using Random Forest, and analyzing the correlations between selected features and the target variable. The goal is to identify the most relevant features for predicting the target variable and understand their relationships.

## Requirements

Ensure you have the following libraries installed:

- pandas: For data manipulation and analysis.
- scikit-learn: Specifically, `make_classification` from `sklearn.datasets` for generating synthetic data.
- seaborn: For creating heatmap visualizations.
- matplotlib.pyplot: For plotting correlation matrices and other visualizations.

## Dataset Generation

A synthetic dataset with 1000 samples and 20 features is generated using `make_classification`. The features are labeled as "Feature_0" to "Feature_19", and a target variable is included.

## Data Exploration

Various exploratory analyses are performed on the dataset, including:

- Visualizing the correlation matrix of features using a heatmap.
- Displaying information about the dataset, such as data types and memory usage.
- Showing the first few rows of the dataset to understand its structure.

## Feature Selection with Random Forest

Random Forest is used for feature selection by calculating the Pearson correlation coefficients between each feature and the target variable. The top 10 features with the highest absolute correlation values are selected for further analysis.

## Correlation Analysis of Selected Features

The correlations between the selected features are visualized using another heatmap. This helps in understanding the relationships among the chosen features and identifying any multicollinearity.

## Conclusion

This project demonstrates a simple yet effective method for feature selection and correlation analysis using Random Forest and Pearson correlation coefficients. By selecting the most relevant features, we can build more efficient predictive models and gain insights into the underlying relationships within the dataset.

## How to Run

1. Make sure all required libraries are installed.
2. Run the code sections sequentially to generate the synthetic dataset, perform feature selection, and analyze correlations.
3. Interpret the visualizations and extracted features to gain insights into the dataset's characteristics and relationships.

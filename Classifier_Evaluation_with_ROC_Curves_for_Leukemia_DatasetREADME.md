# Project README

## Introduction
This project aims to compare the performance of different classifiers on two different datasets using ROC curves and AUC metrics. The evaluation helps in understanding how well each classifier discriminates between positive and negative instances and allows for the selection of the most suitable classifier for the given datasets. Additionally, it provides insights into the classifiers' ability to generalize to unseen data, which is crucial for building robust predictive models in various applications, including medical diagnostics.

## Workflow Overview

### Loading
The code begins by loading two datasets, presumably containing features and labels related to leukemia and lung samples, respectively.

### Data Preprocessing
The datasets are assumed to be preprocessed and contain binary classification labels, as indicated by the presence of a 'label' column.

### Train-Test Split
Each dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.

### Classifier Training
Three classifiers are trained on the leukemia dataset: Logistic Regression, Random Forest, and Support Vector Machine (SVM). These classifiers are initialized and fitted to the training data.

### Prediction and Evaluation
For each classifier, predicted probabilities for the positive class are obtained using the testing data. Then, ROC curves and AUC metrics are calculated to evaluate the classifiers' performance.

### Plotting ROC Curves
The ROC curves for each classifier are plotted using Matplotlib. Additionally, a diagonal line representing a random classifier (with an AUC of 0.5) is also plotted for comparison.

### Customization
The plot is customized with appropriate labels for the axes and the title.

### Displaying the Plot
The final plot showing the ROC curves is displayed.

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

## Usage
1. Ensure that all required libraries are installed.
2. Place the datasets (`leukemia.csv` and `lungsample_csv.csv`) in the same directory as the script.
3. Run the script to train classifiers, evaluate performance, and plot ROC curves.

## Dataset Information
- The leukemia dataset contains features related to leukemia samples.
- The lung sample dataset contains features related to lung samples.
- Both datasets contain binary classification labels.

## References
- [sklearn.model_selection.train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
- [sklearn.metrics.roc_curve](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_curve.html)
- [sklearn.metrics.auc](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.auc.html)
- [Matplotlib](https://matplotlib.org/)

This README provides an overview of the project workflow, instructions for usage, and references for further information. It serves as a guide for understanding and utilizing the code for comparing classifiers using ROC curves and AUC metrics.

# codsoft_task-1

# Iris Flower Classification
# Project Overview
This project implements a machine learning model to classify Iris flowers into three species (Setosa, Versicolor, and Virginica) based on their sepal and petal measurements. The dataset used is the classic Iris dataset, and the model employs a Random Forest Classifier to achieve high accuracy in classification.

# Dataset
The Iris dataset (IRIS.csv) contains 150 samples with the following features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
Species (target variable: Iris-setosa, Iris-versicolor, Iris-virginica)
The dataset is sourced from a local file path in the provided notebook.

# Project Structure
IRIS FLOWER CLASSIFICATION.ipynb: Jupyter Notebook containing the complete code for data preprocessing, model training, evaluation, and visualization.
IRIS.csv: The dataset file (not included in this repository; ensure it is available in your local environment or update the file path in the notebook).

# Requirements
To run the notebook, install the following Python libraries:
pip install pandas seaborn matplotlib scikit-learn

# Methodology
Data Loading: The Iris dataset is loaded using pandas.

# Data Preprocessing:
Features (sepal and petal measurements) are separated from the target (species).
The data is split into training (80%) and testing (20%) sets.
Features are standardized using StandardScaler to improve model performance.

# Model Training: A Random Forest Classifier with 100 estimators is trained on the scaled training data.

# Evaluation:
Model accuracy is calculated using accuracy_score.
A detailed classification report (precision, recall, F1-score) is generated.
A confusion matrix is visualized using a heatmap to show classification performance across species.

# Visualization: A confusion matrix heatmap is plotted using seaborn and matplotlib.

# Results
Accuracy: The model achieves an accuracy of approximately 96.67% on the test set.
Classification Report: The model performs well across all classes, with precision, recall, and F1-scores ranging from 0.80 to 1.00 (see notebook output for details).
Confusion Matrix: The heatmap visualizes correct and incorrect predictions, showing minimal misclassifications.

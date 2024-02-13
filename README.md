
# Cancer Detection using Machine Learning Algorithms

This repository contains code and analysis for detecting cancer using various machine learning algorithms. We compare the performance of **logistic regression**, **decision tree**, and **random forest** models. Additionally, we include preprocessing steps to prepare the data for modeling.

## Dataset

The data is included in the repository (`data.csv`). The dataset contains information related to various risk factors associated with breast cancer.

## Project Structure

- `data.csv`: Contains the dataset.
- `cancer_clissifier.ipynb`: Jupyter notebook for data exploration, preprocessing, and model training.
- `README.md`: This file.

## Preprocessing Steps

1. **Feature Selection**: We remove the useless features that are irrelevent to the labels.

2. **Feature Scaling**: To ensure consistent scaling across features, we apply **standardization**.

## Model Implementation

We train the following machine learning models:

1. **Logistic Regression**: A linear model that predicts the probability of an instance belonging to a particular class.

2. **Decision Tree**: A tree-based model that splits the data based on feature thresholds to make predictions.

3. **Random Forest**: An ensemble of decision trees that combines their predictions for improved accuracy.

## Evaluation Metrics

We evaluate the models using the following metrics:

- **Accuracy**: Overall correctness of predictions.
- **Recall**: Ability to correctly identify positive cases (cancer).
- **Precision**: Proportion of true positive predictions among all positive predictions.
- **F1-score**: Harmonic mean of precision and recall.

## Usage

There are two ways that you can work with this project:

1. <a href="https://colab.research.google.com/github/barzansaeedpour/cancer-detection/blob/main/cancer_classifier.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

2. Clone this repository

  
   ```
   git clone https://github.com/barzansaeedpour/cancer-detection.git
   ```

   Navigate to the appropriate directory and run the Jupyter notebooks or Python scripts to explore the data, preprocess it, and train the models.

Feel free to add more details, instructions, or any other relevant information.🌟🔬🩺
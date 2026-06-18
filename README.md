# Supervised Machine Learning: Part 3 (Pipelines, KNN & Naive Bayes)

## 📌 Overview
This repository focuses on enhancing classification models. It covers advanced data scaling, robust evaluation metrics, hyperparameter tuning, and introduces two classic classification algorithms: Naive Bayes and K-Nearest Neighbors (KNN).

## 📚 Topics Covered

### 1. Data Scaling & Preprocessing
* **Standardization & Normalization:** Understanding the mathematical difference between scaling data to a specific range versus centering it around a zero mean.
* **Using StandardScaler:** Implementing scaling programmatically using `sklearn` to ensure models treat all features equally.

### 2. Advanced Evaluation Metrics
* **Understanding Confusion Matrix:** Visualizing True Positives, True Negatives, False Positives, and False Negatives.
* **Classification Evaluation Metrics:** Moving beyond simple accuracy to analyze model performance using specialized classification metrics.

### 3. Classification Algorithms
* **Naive Bayes (Algorithm 4):** Learning the probabilistic approach to classification based on Bayes' Theorem, including practical examples and coding implementations.
* **Types of Naive Bayes:** Exploring different variations of the algorithm for different data distributions.
* **K-Nearest Neighbors (Algorithm 5):** Implementing the distance-based KNN algorithm and understanding its computational limitations.

### 4. Model Validation & Hyperparameter Tuning
* **Validation Data:** Understanding the critical split between training, validation, and testing sets.
* **Cross Validation:** Implementing robust testing techniques to ensure the model performs consistently across different data subsets.
* **Hyperparameter Tuning:** Using cross-validation (CV) to systematically find the most optimal parameters for a model.

### 5. Production Ready Code
* **Pipeline in sklearn:** Chaining preprocessing steps (like scaling) and modeling steps together to prevent data leakage and write cleaner code.

# 🩺 Breast Cancer Classification using Logistic Regression

<p align="center">

A Machine Learning project for **Breast Cancer Diagnosis Prediction** using **Logistic Regression**, developed with **Python** and **Scikit-Learn**.

Designed as a practical introduction to binary classification, model evaluation, and supervised machine learning workflows.

</p>

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 📖 Overview

Breast cancer is one of the most common forms of cancer worldwide, making early diagnosis essential for improving treatment outcomes.

This project demonstrates how **Logistic Regression**, one of the most fundamental supervised machine learning algorithms, can be used to classify breast cancer diagnoses based on medical diagnostic features.

The notebook follows a complete machine learning pipeline—from loading and preparing the dataset to training a classification model, generating predictions, evaluating performance, and validating the classifier using **10-Fold Cross Validation**.

Whether you are beginning your machine learning journey or reviewing the fundamentals of binary classification, this repository provides a clean and practical implementation using Python and Scikit-Learn.

---

# ✨ Features

✔ Complete Logistic Regression implementation

✔ Breast Cancer Classification

✔ Clean machine learning workflow

✔ Train/Test dataset splitting

✔ Binary classification

✔ Prediction on unseen samples

✔ Confusion Matrix evaluation

✔ Accuracy Score calculation

✔ 10-Fold Cross Validation

✔ Beginner-friendly notebook

✔ Well-commented implementation

✔ Easy to extend for future ML experiments

---

# 📑 Table of Contents

- 📖 Overview
- ✨ Features
- 🎯 Project Objectives
- 🛠 Technologies Used
- 📂 Repository Structure
- 📊 Dataset
- ⚙ Machine Learning Pipeline
- 📈 Model Evaluation
- 🚀 Getting Started
- 💻 Installation
- ▶ Running the Notebook
- 📚 Learning Outcomes
- 🔮 Future Improvements
- 🤝 Contributing
- ⭐ Support
- 📜 License

---

# 🎯 Project Objectives

This project aims to demonstrate the complete implementation of a Logistic Regression classifier using Scikit-Learn.

The primary objectives include:

- Understanding supervised learning
- Implementing Logistic Regression for binary classification
- Preparing features and target variables
- Splitting datasets into training and testing subsets
- Training a classification model
- Predicting diagnosis labels
- Evaluating prediction performance
- Understanding Confusion Matrix interpretation
- Measuring classification accuracy
- Validating model robustness using Cross Validation

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data preprocessing and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Scikit-Learn | Machine Learning algorithms |
| Jupyter Notebook | Interactive development environment |

---

# 📂 Repository Structure

```text
.
├── breast_cancer_Logistic_Regression.ipynb
├── breast_cancer.csv
├── README.md
└── LICENSE
```

---

# 📊 Dataset

The project uses the **Breast Cancer Dataset** for binary classification.

The dataset consists of diagnostic measurements extracted from breast mass images.

Each observation represents one patient sample, while the target variable indicates the diagnosis category.

| Variable | Description |
|----------|-------------|
| Features | Diagnostic measurements |
| Target | Breast Cancer Diagnosis |

---

## Target Classes

The Logistic Regression model predicts one of the two diagnosis classes.

| Class | Meaning |
|--------|---------|
| Positive Class | One diagnosis category |
| Negative Class | The other diagnosis category |

The notebook focuses on learning a decision boundary capable of separating these two classes using Logistic Regression.

---

# ⚙ Machine Learning Workflow

```text
                 Breast Cancer Dataset
                          │
                          ▼
                 Import Libraries
                          │
                          ▼
                  Load Dataset
                          │
                          ▼
          Feature & Target Separation
                          │
                          ▼
             Train-Test Split (80/20)
                          │
                          ▼
          Logistic Regression Training
                          │
                          ▼
                   Model Prediction
                          │
                          ▼
               Confusion Matrix
                          │
                          ▼
                 Accuracy Score
                          │
                          ▼
            10-Fold Cross Validation
                          │
                          ▼
               Performance Evaluation
```

---

# 💡 Why Logistic Regression?

Logistic Regression is one of the most widely used algorithms for binary classification problems.

It is computationally efficient, easy to interpret, and often serves as a strong baseline model for medical diagnosis, finance, fraud detection, and many other classification tasks.

In this notebook, Logistic Regression is used to learn the relationship between diagnostic features and breast cancer diagnosis while providing a simple yet effective predictive model.

---

# 🚀 Getting Started

Follow the steps below to set up and run the project on your local machine.

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/aiotaha/breast_cancer_logistic_regression.git
```

Navigate to the project directory.

```bash
cd breast_cancer_logistic_regression
```

---

## 2️⃣ Create a Virtual Environment (Recommended)

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

or

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```text
breast_cancer_Logistic_Regression.ipynb
```

---

# 💻 Project Pipeline

The notebook follows a standard supervised machine learning workflow.

## Step 1 — Import Libraries

Essential Python libraries are imported for:

- Data manipulation
- Numerical computation
- Machine Learning
- Visualization

---

## Step 2 — Load the Dataset

The Breast Cancer dataset is loaded into a Pandas DataFrame for further processing.

At this stage, the notebook prepares the dataset for machine learning tasks.

---

## Step 3 — Prepare Features and Labels

The dataset is separated into

- Input Features (X)
- Target Labels (y)

This separation allows the classifier to learn the relationship between medical measurements and diagnosis.

---

## Step 4 — Split the Dataset

The notebook divides the dataset into

- Training Set
- Testing Set

This enables evaluation on previously unseen data.

---

## Step 5 — Train Logistic Regression

A Logistic Regression classifier is fitted using the training data.

The algorithm learns the relationship between diagnostic measurements and diagnosis labels.

---

## Step 6 — Prediction

After training, the classifier predicts diagnosis labels for the testing dataset.

These predictions are then compared with the actual labels.

---

## Step 7 — Performance Evaluation

The notebook evaluates prediction performance using:

- Confusion Matrix
- Accuracy Score

These metrics provide an initial assessment of the classifier's effectiveness.

---

## Step 8 — Cross Validation

To estimate model generalization, the notebook performs

**10-Fold Cross Validation**

This helps reduce bias caused by a single train-test split and provides a more reliable estimate of model performance.

---

# 📈 Model Evaluation

The notebook evaluates the trained Logistic Regression classifier using several commonly used classification metrics.

| Evaluation Method | Purpose |
|-------------------|---------|
| Confusion Matrix | Analyze prediction outcomes |
| Accuracy Score | Measure prediction accuracy |
| Cross Validation | Estimate generalization ability |
| Mean Accuracy | Average validation performance |
| Standard Deviation | Measure performance consistency |

---

# 📊 Confusion Matrix

The Confusion Matrix summarizes the prediction results by comparing the predicted labels with the actual labels.

It helps identify

- Correct classifications
- Incorrect classifications
- False Positives
- False Negatives

Understanding the Confusion Matrix is an essential step when evaluating classification models.

---

# 🔬 Cross Validation

Instead of relying on a single train-test split, this notebook validates the model using

**10-Fold Cross Validation**

This evaluation strategy repeatedly trains and tests the classifier on different subsets of the data.

Advantages include:

- Better estimation of model performance
- Lower evaluation bias
- Improved reliability
- Better assessment of model stability

---

# 📚 What You Will Learn

After completing this notebook, you will understand:

- Binary Classification
- Logistic Regression
- Data Preparation
- Feature and Target Separation
- Train/Test Splitting
- Classification Prediction
- Confusion Matrix Interpretation
- Accuracy Evaluation
- Cross Validation
- Scikit-Learn Workflow
- Machine Learning Best Practices

---

# 💡 Key Concepts Covered

✔ Supervised Learning

✔ Binary Classification

✔ Logistic Regression

✔ Model Training

✔ Model Prediction

✔ Classification Metrics

✔ Model Validation

✔ Cross Validation

✔ Performance Analysis

✔ Practical Scikit-Learn Implementation

---

# 🎯 Practical Skills Gained

By studying this project, you will be able to:

- Build your first classification model
- Train Logistic Regression models
- Predict labels for unseen data
- Evaluate classifier performance
- Interpret confusion matrices
- Validate machine learning models
- Implement complete Scikit-Learn workflows
- Apply these concepts to other classification datasets

---

# 📌 Applications

Logistic Regression is widely used in real-world applications such as:

- Medical Diagnosis
- Disease Prediction
- Fraud Detection
- Customer Churn Prediction
- Credit Risk Assessment
- Email Spam Detection
- Customer Behavior Analysis
- Financial Decision Systems

---

# 📊 Project Highlights

This project demonstrates a complete end-to-end binary classification workflow using one of the most fundamental supervised learning algorithms.

### Highlights

- 🩺 Breast Cancer Diagnosis Classification
- 🤖 Logistic Regression with Scikit-Learn
- 📂 Clean and organized Jupyter Notebook
- 📊 Model evaluation using Confusion Matrix
- 📈 Accuracy Score calculation
- 🔄 10-Fold Cross Validation
- 🐍 Implemented entirely in Python
- 🎓 Suitable for beginners in Machine Learning
- 🚀 Easily extensible for future classification projects

---

# 📸 Results

After training the Logistic Regression classifier, the notebook evaluates its performance using multiple evaluation techniques.

The implemented workflow includes:

- Model prediction on unseen test samples
- Confusion Matrix generation
- Accuracy calculation
- Cross Validation using 10 folds
- Performance consistency analysis

The notebook is intentionally designed to emphasize the complete machine learning workflow rather than optimizing a specific benchmark score.

---

# 📈 Future Improvements

This repository can be extended in several ways.

Possible future improvements include:

- ROC Curve visualization
- Precision, Recall and F1-Score evaluation
- Classification Report
- Feature Importance Analysis
- Data Standardization experiments
- Hyperparameter tuning using GridSearchCV
- Model comparison with:
  - Support Vector Machine (SVM)
  - Random Forest
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
- Interactive visualization dashboards
- Deployment using Streamlit or Flask

---

# 🎓 Educational Purpose

This project was developed as an educational machine learning notebook to demonstrate the implementation of Logistic Regression for binary classification using Scikit-Learn.

It is intended for:

- Students
- Machine Learning beginners
- Data Science learners
- University coursework
- Self-study
- Practical ML demonstrations

---

# 📚 References

The implementation is based on concepts from:

- Scikit-Learn Documentation
- Python Documentation
- Machine Learning classification principles
- Breast Cancer classification examples commonly used in introductory ML courses

---

# 🤝 Contributing

Contributions are always welcome.

If you have suggestions for improving the notebook or adding new machine learning techniques, feel free to:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Submit a Pull Request.

Bug reports, documentation improvements, and optimization suggestions are greatly appreciated.

---

# ⭐ Support

If this repository helped you learn something new, consider giving it a ⭐ on GitHub.

Your support helps improve the project and encourages the development of more educational machine learning repositories.

---

# 📝 Citation

If you use this repository for educational purposes, presentations, or academic projects, please consider referencing this repository.

Example:

```text
Taha Sarhadi.
Breast Cancer Classification using Logistic Regression.
GitHub Repository.
```

---

# 📜 License

This project is licensed under the **MIT License**.

You are free to:

- Use
- Modify
- Share
- Distribute

the code under the terms of the MIT License.


---

# 🌟 Repository Goals

The goal of this repository is not only to build a Logistic Regression classifier, but also to provide a clean and understandable implementation that demonstrates every major step of a supervised machine learning workflow.

Readers should be able to understand:

- How a classification dataset is prepared
- How Logistic Regression learns from data
- How predictions are generated
- How model performance is evaluated
- Why Cross Validation is important

---

<p align="center">

⭐ If you found this project useful, don't forget to star the repository!

</p>

---

<p align="center">

Made with ❤️ using Python, Scikit-Learn & Jupyter Notebook

</p>

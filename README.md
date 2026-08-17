# 📧 Spam Classification

## 📌 Project Overview

This project focuses on classifying emails as **spam** or **non-spam** using Machine Learning.

The project uses the **UCI Spambase dataset** and explores classification with two Machine Learning algorithms:

- K-Nearest Neighbors (KNN)
- Decision Tree

The notebook also includes data cleaning, exploratory analysis, train/test splitting, model evaluation, and comparison of different K values for KNN.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- `ucimlrepo`

## 📂 Dataset

The project uses the **Spambase** dataset from the UCI Machine Learning Repository.

The target variable is:

- `0` → Non-spam
- `1` → Spam

The dataset contains email-related features, including word-frequency features such as `word_freq_money` and `word_freq_credit`.

## 🔍 Project Workflow

### 1. Load the Dataset

The Spambase dataset is loaded using `ucimlrepo`.

### 2. Data Preparation

The notebook:

- Creates a Pandas DataFrame
- Checks for duplicate rows
- Removes duplicate rows
- Checks for missing values

### 3. Exploratory Data Analysis

The project examines selected features and uses visualizations to compare their values across spam and non-spam emails.

### 4. Feature Selection

Selected email-related features are used as inputs for the Machine Learning models.

The target variable is the `Class` column.

### 5. Train/Test Split

The dataset is divided into training and testing data using a stratified split so that the class distribution is maintained.

### 6. K-Nearest Neighbors

A KNN classifier is trained and evaluated.

The notebook also tests different values of `K` to find a suitable value based on model performance.

### 7. Decision Tree

A Decision Tree classifier is trained with a maximum depth of 6 and evaluated on the training and testing data.

## 📊 Model Evaluation

The models are evaluated using:

- **Accuracy** — overall proportion of correct predictions
- **Precision** — proportion of predicted spam emails that are actually spam
- **Recall** — proportion of actual spam emails correctly identified
- **F1-score** — balance between precision and recall
- **Confusion Matrix** — shows correct and incorrect classifications by class

## 📁 Project Structure

```text
spam-classification/
│
├── spam_classification.ipynb
└── README.md
```

## 🎯 What I Learned

Through this project, I practiced:

- Working with a real-world classification dataset
- Data cleaning using Pandas
- Exploratory data analysis
- Feature selection
- Train/test splitting
- K-Nearest Neighbors classification
- Decision Tree classification
- Evaluating classification models
- Comparing model performance

## 🚀 Future Improvements

Possible improvements include:

- Testing additional classification algorithms
- Performing feature scaling for KNN
- Improving feature selection
- Hyperparameter tuning
- Comparing more evaluation metrics
- Building a simple application for spam prediction

## 👨‍💻 Author

**[Your Name]**

If you find this project useful, feel free to ⭐ the repository.

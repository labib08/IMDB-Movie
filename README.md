# Features
## Project Highlights
* Comprehensive comparison of **ZeroR, Decision Tree, Logistic Regression**, and **K-NN** models.
* Advanced data preprocessing, including **FastText** and **Doc2Vec** embeddings for non-numeric features.
* Extensive evaluation techniques such as **10-fold cross-validation** and **holdout strategies**.
* Hyperparameter tuning and feature engineering to maximize model performance and accuracy.
# Technologies Used
* **Python:** Core programming language.
* **Scikit-learn:** Model implementation and evaluation.
* **FastText:** Embedding generation for textual features.
* **Doc2Vec:** Vector representation for non-numeric data.
* **Logistic Regression, K-NN, Decision Trees:** Machine learning models for prediction.
# Methodologies
**1. Data Preprocessing:**

* Embedded non-numeric features using FastText and Doc2Vec.
* Performed feature selection to identify the most relevant attributes.
* Handled missing values and normalized numerical features.
**2. Model Comparison:**

## 1. Implemented four supervised learning models:
* ZeroR: Baseline model.
* Decision Trees: Interpretable tree-based model with varying depths.
* Logistic Regression: Grid-searched hyperparameters for optimal performance.
* K-NN: Tuned distance metrics and K-values.
  
## 2. Evaluated models using:
* **10-fold cross-validation.**
* **Holdout strategy** for unseen data.

## 3. Conducted error analysis and statistical comparison of results.

**3. Critical Analysis:**

* Addressed overfitting in decision trees using various train-test splits.
* Investigated model performance metrics such as accuracy, precision, recall, and F1 score.
* Discussed strengths and weaknesses of each model.

# Getting Started
Follow these steps to run the project locally:

**1. Clone the Repository:**
```
https://github.com/labib08/IMDB-Movie.git
```
**2. Navigate to the Directory:**
```
cd imdb-movie-prediction
```
**3. Install Dependencies:**
```
pip install -r requirements.txt
```
**4. Keep the training and test dataset in the same directory as the main.py file, as well as the features_doc2vec folder that was already given**

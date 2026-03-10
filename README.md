# Spam Email Classifier

This project is a **Machine Learning application** designed to classify emails as either **Spam** or **Ham (not spam)**.  
It uses the **Multinomial Naive Bayes algorithm** and **TF-IDF Vectorization** to achieve high classification performance.

---

## Project Overview

The classifier is built using a dataset of **5,572 messages**.

The workflow includes:

### 1. Data Preprocessing
Mapping text labels (`ham`, `spam`) to binary numerical values (`0`, `1`).

### 2. Feature Extraction
Converting raw text into numerical features using **TfidfVectorizer**.

### 3. Model Training
Utilizing the **Multinomial Naive Bayes (MultinomialNB)** algorithm, which is well-suited for discrete features like word counts in text classification.

### 4. Real-time Prediction
A user-friendly input interface allows users to test custom messages and see whether they are spam or not.

---

## Performance Metrics

The model was evaluated on a **test set (20% of the dataset)**.

| Metric | Value |
|------|------|
| Accuracy | **96.23%** |

---

## Libraries Used

- **Pandas** – Data manipulation and analysis  
- **Scikit-learn** – Machine learning, vectorization, and model evaluation

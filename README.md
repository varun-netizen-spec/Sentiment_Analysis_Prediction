# 🧠 Mental Health Sentiment Analysis using Deep Learning

This project presents an end-to-end **machine learning and deep learning pipeline** for **mental health sentiment analysis**, covering **data exploration, data cleaning, preprocessing, visualization, model training, and evaluation**. The model demonstrates **improved accuracy through iterative training and optimization**.

---

## 📌 Project Highlights

- ✔ Exploratory Data Analysis (EDA)
- ✔ Data cleaning and preprocessing
- ✔ Data exploration and visualization
- ✔ Deep learning–based text classification
- ✔ Improved model training accuracy
- ✔ Comprehensive model evaluation

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and distribution of the dataset:
- Sentiment class distribution
- Text length analysis
- Identification of data imbalance
- Visualizations using bar plots and histograms

Data visualization helped uncover patterns and informed preprocessing decisions.

---

## 🧹 Data Cleaning & Preprocessing

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Ensured consistent data formatting

### Data Preprocessing
- Tokenization and padding
- Label encoding
- Vocabulary size control
- Train–test split

---

## 🧠 Deep Learning Model

The sentiment classification model was built using **TensorFlow / Keras** with the following architecture:


### Training Configuration
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 20
- Batch Size: 32
- Learning rate scheduling applied

---

## 📈 Model Training & Accuracy Improvement

- Training accuracy improved from **~85% to over 92%**
- Validation accuracy stabilized around **~80%**
- Learning rate reduction improved convergence
- Training and validation curves indicated controlled overfitting

---

## 📊 Model Evaluation

The trained model was evaluated on unseen test data using:
- Accuracy
- Precision
- Recall
- F1-score

### 🔹 Test Performance

-Test Accuracy: ~80.17%
-The evaluation results indicate good generalization on unseen data.
---

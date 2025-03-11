# NLP Project - news Classification

## Overview

This project is a Natural Language Processing (NLP) task focused on text classification. The goal is to classify the news as either **real** or **fake** using various machine learning models. The project includes data preprocessing, feature extraction, and model evaluation.

## Dataset

- The dataset is loaded from a CSV file.
- It contains labeled text data where:
  - **0 represents Fake**
  - **1 represents Real**

## Project Structure

The notebook follows these main steps:

1. **Importing Libraries**

   - Essential Python libraries such as `pandas`, `re`, `matplotlib`, `sklearn`, and `wordcloud` are used.

2. **Loading the Dataset**

   - Reads a CSV file and displays information about the dataset.

3. **Exploratory Data Analysis (EDA)**

   - Visualizing class distribution using bar charts.
   - Creating WordClouds for both fake and real text labels.

4. **Data Preprocessing**

   - Removing stop words.
   - Cleaning and tokenizing text.

5. **Feature Extraction**

   - Using **TF-IDF Vectorization** to transform text into numerical features.

6. **Model Training & Evaluation**

   - Machine learning models used:
     - **Logistic Regression**
     - **Naïve Bayes**
     - **Random Forest**
     - **Support Vector Machine (SVM)**
   - Evaluating models using:
     - **Accuracy Score**
     - **Classification Report**
     - **Confusion Matrix**

## Requirements

To run this notebook, install the necessary dependencies:

```bash
pip install pandas numpy matplotlib wordcloud scikit-learn
```

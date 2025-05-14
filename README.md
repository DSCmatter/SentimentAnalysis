# 🎬 IMDB Movie Reviews Sentiment Analysis

This project performs sentiment analysis on the [IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data) of 50,000 movie reviews. The dataset is labeled with binary sentiments: **positive** or **negative**.

We go through a full machine learning pipeline using **Natural Language Processing (NLP)** techniques to classify review sentiment.

---

## Dataset

- **File:** `IMDB Dataset.csv`
- **Columns:**
  - `review`: Text content of a user review
  - `sentiment`: Label (`positive` or `negative`)

---

## Project Steps

1. **Data Loading**
   - Read and display the structure of the dataset.

2. **Data Preprocessing**
   - Remove HTML tags, punctuation, stopwords
   - Tokenization, lowercasing, and stemming

3. **Exploratory Data Analysis**
   - Sentiment distribution
   - Word clouds for positive and negative reviews
   - Review length analysis

4. **Text Vectorization**
   - Using **TF-IDF** for numerical feature extraction

5. **Model Training**
   - Trained a **Logistic Regression** model
   - Achieved accuracy over ~85% on test data

6. **Evaluation**
   - Classification report
   - Confusion matrix visualization

---

## Visualizations

- Sentiment distribution bar plot
- Histogram of review lengths
- Confusion matrix heatmap

---

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

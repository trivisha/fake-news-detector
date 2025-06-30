# 📰 Fake News Detection with Machine Learning

This project uses Natural Language Processing (NLP) and a machine learning classifier to detect whether a news article is fake or real — built entirely in Python on Google Colab.

> 99.5% accuracy  
> NLP + TfidfVectorizer  
>  Passive Aggressive Classifier  
> Perfect for beginners exploring AI/ML and text classification

---

## 📌 About the Project

Fake news has become a critical issue in today’s digital era. This project aims to build a simple, fast, and effective machine learning model that classifies news articles as either **fake** or **real** based on their content.

You’ll learn how to clean text, convert it into machine-readable form, and train a real classifier using publicly available data.

---

## 📁 Dataset

- **Source:** [Kaggle – Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Data Points:** ~20,000 articles
- **Files:**
  - `Fake.csv`: Fake news articles
  - `True.csv`: Real news articles

---

## 🧠 Approach

### 1. Combine and Label the Data
Both CSV files are merged, and a label is added:
- `0` for fake news
- `1` for real news

### 2. Preprocess the Text
Using **NLTK**, the text is:
- Lowercased
- Stripped of punctuation
- Cleaned of stopwords
- Stemmed for root-word consistency

### 3. Vectorize the Text
Using **TfidfVectorizer**, each news article is transformed into a numerical vector, representing how important each word is in the context of all articles.

### 4. Train the Model
We use **PassiveAggressiveClassifier**, a fast and efficient algorithm ideal for binary text classification.

### 5. Evaluate Accuracy
The dataset is split into training and test sets (80/20), and we achieved:
- **✅ 99.55% accuracy** on the test set

---

## 💻 Tech Stack

| Tool / Library         | Purpose                          |
|------------------------|----------------------------------|
| `Python`               | Main programming language        |
| `pandas`               | Data handling                    |
| `NLTK`                 | Text preprocessing (NLP)         |
| `TfidfVectorizer`      | Feature extraction from text     |
| `PassiveAggressiveClassifier` | Machine learning model     |
| `Google Colab`         | Development environment (cloud)  |

---

## 🧪 Results

| Metric     | Value     |
|------------|-----------|
| Accuracy   | **99.55%** |
| Classifier | PassiveAggressiveClassifier |
| Features   | Top 5000 words (TF-IDF) |

---

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Upload `Fake.csv` and `True.csv`
3. Run all cells to train and evaluate the model

---

## 📂 Project Structure

├── Fake_News_Detector.ipynb ← Main notebook
├── README.md ← This file
├── Fake.csv ← Dataset file (Fake news)
├── True.csv ← Dataset file (Real news)


---

## 👤 Author

**Shivangi Dubey**  
💻 [GitHub](https://github.com/trivisha)

---

## ⭐ Final Thoughts

This project is a great starting point for anyone interested in:
- Natural Language Processing
- Binary text classification
- Real-world applications of AI and ML




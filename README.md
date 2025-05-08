# 📰 Fake News Classifier

This project is a **Fake News Detection System** built using Natural Language Processing (NLP) and Machine Learning techniques. The aim is to automatically identify whether a given news article is **real** or **fake** based on its textual content.

## 📌 Objective

In the age of digital media, misinformation spreads quickly. This project tackles this challenge by building a model that classifies news articles as *fake* or *real*, helping improve content credibility and reduce the spread of false information.

## 🧰 Technologies & Tools Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **NLTK**, **Scikit-learn** – NLP and ML
- **TfidfVectorizer** – Text feature extraction
- **PassiveAggressiveClassifier** – Classification algorithm

## 🗂️ Dataset

The dataset used for this project contains two main columns:
- `text`: The content of the news article
- `label`: Classification label (`FAKE` or `REAL`)

> The dataset is preprocessed to remove stopwords, punctuation, and to normalize text.

## 📊 Workflow

1. **Data Preprocessing**
   - Tokenization, stopword removal, and text cleaning.
2. **Vectorization**
   - Transforming text into TF-IDF features.
3. **Model Training**
   - PassiveAggressiveClassifier trained on the processed dataset.
4. **Model Evaluation**
   - Accuracy, confusion matrix, and precision/recall scores.

## ✅ Results

- Achieved high accuracy in classifying fake and real news.
- Model capable of generalizing to unseen news articles.

## 🧠 Skills Demonstrated
- Natural Language Processing
- Binary Text Classification
- Feature Extraction with TF-IDF
- Model Evaluation Metrics

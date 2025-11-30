# 🎧 Sentiment Analysis: Spotify App Reviews (Indonesian Market)

![Language](https://img.shields.io/badge/Language-Python-blue)
![Data](https://img.shields.io/badge/Data-20k+_Reviews-green)
![Model](https://img.shields.io/badge/Best_Model-SVM_(95%25)-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Project Overview
This project performs an end-to-end sentiment analysis on user reviews of the **Spotify** application from the Google Play Store. Focusing on the Indonesian market, the study aims to classify user feedback into **Positive, Negative, or Neutral** sentiments to understand user satisfaction trends.

I successfully scraped over **20,000 reviews** and built a machine learning pipeline to benchmark multiple algorithms, ultimately achieving high accuracy in text classification.

## 🚀 Key Features & Workflow

### 1. Data Acquisition (Scraping)
* Developed a custom scraping script using `google-play-scraper`.
* Collected **20,000 raw reviews** specifically with the Indonesian language locale (`lang='id'`).
* Attributes collected include: `content`, `score`, `thumbsUpCount`, and `at` (timestamp).

### 2. Data Preprocessing & Feature Extraction
* **Text Cleaning:** implemented a pipeline to remove emojis, special characters, and stopwords.
* **Feature Extraction:** Utilized **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert unstructured text data into numerical vectors for machine learning.

### 3. Model Benchmarking
I trained and evaluated three distinct Machine Learning algorithms to find the best classifier:
* **Support Vector Machine (SVM)**
* **Logistic Regression**
* **Random Forest**

## 🛠️ Tech Stack
* **Language:** Python
* **Scraping:** `google-play-scraper`
* **Data Processing:** Pandas, NumPy
* **NLP & ML:** Scikit-Learn, NLTK
* **Visualization:** Matplotlib, Seaborn

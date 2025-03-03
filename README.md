# 📊 Sentiment Analysis of Tweets on the 2024 US Presidential Election

This project analyzes tweets related to the 2024 US Presidential Election using Natural Language Processing (NLP) and sentiment analysis techniques. By leveraging web mining and visualization, it aims to uncover patterns and public sentiment towards the candidates.

---

## 📌 Abstract

This project employs web mining and NLP techniques to analyze tweets related to the 2024 US Presidential Election. The VADER sentiment analysis tool is used to classify tweets into positive, neutral, or negative sentiments. Data visualization is implemented using Matplotlib and Seaborn to derive meaningful insights. The analysis predicts that Trump has a higher positive sentiment ratio based on the dataset.

---

## 📖 Introduction

Social media platforms like Twitter are powerful tools for capturing public sentiment. This project leverages these platforms to analyze trends and opinions related to the 2024 US Presidential Election. Using data preprocessing, sentiment analysis, and visualization, the project aims to present a structured view of public sentiment.

---

## 📊 Dataset Overview

- **Dataset Size:** 44,996 entries and 28 columns.
- **Key Features:**
  - Tweets and metadata such as date, user info, and hashtags.
  - Preprocessing steps include removing non-English tweets, URLs, mentions, and irrelevant columns.
- **Processed Files:**
  - `may_july_chunk_1.csv` - Raw data.
  - `cleaned data 1.csv` - Preprocessed and cleaned data.

---

## ⚙️ Methodology

### 📋 Data Preprocessing
- Removed URLs, mentions, and special characters.
- Dropped irrelevant columns (e.g., retweetedTweetID, retweetedUserID, location).
- Filtered tweets to include only English language content.
- Tokenization and removal of stop words using NLTK.

---

### 📈 Sentiment Analysis
- **Tool Used:** VADER (Valence Aware Dictionary and Sentiment Reasoner).
- **Sentiment Classification:**
  - Positive: Score > 0.05
  - Neutral: -0.05 ≤ Score ≤ 0.05
  - Negative: Score < -0.05
- **Output:**
  - Created new columns: `sentiment score`, `sentiment label`, and `cleaned text`.

---

### 📊 Visualization and Insights
- **Libraries Used:** Matplotlib and Seaborn.
- Visualizations include:
  - Sentiment distribution by candidate.
  - Positive sentiment distribution comparison.
  - Hashtag analysis for trending topics.

---

### 🏷️ Classification
- **Model Used:** Support Vector Machine (SVM).
- **Metrics:**
  - Precision: 83% (positive), 82% (negative).
  - Accuracy: 81.80%.

---

### 🔮 Prediction
- **Model:** SVM with a prediction accuracy of 82%.
- **Outcome:** Donald.J.Trump showed a higher positive sentiment ratio based on the dataset.

---

## 🔍 Exploratory Data Analysis (EDA)
- **Sentiment Distribution:** Bar graphs to illustrate positive, neutral, and negative tweet counts.
- **Hashtag Analysis:** Extracted top 10 trending hashtags and their sentiment distribution.

---

## 📊 Analysis Results
- **Sentiment Analysis:** Pie charts showing sentiment distribution for each candidate.
- **Key Findings:**
  - Higher positive sentiment for Trump.
  - Visualizations provided a clear summary of public opinion.

---

## 💬 Discussion
- Highlights the power of social media as a sentiment barometer.
- Discusses challenges such as:
  - Sampling bias.
  - Bot activity.
  - Platform-specific dynamics.

---

## 🏁 Conclusion
This project demonstrates the effectiveness of web mining and NLP techniques for sentiment analysis on social media data. By integrating data cleaning, sentiment analysis, and visualization:
- **Key Insights:**
  - Clear sentiment trends for 2024 US Presidential candidates.
  - Effective use of VADER for sentiment classification.
  - Data visualization simplified interpretation of public opinion.

---

## 📚 References
- **Natural Language Toolkit (NLTK)**
- **Matplotlib & Seaborn for Data Visualization**
- **VADER Sentiment Analysis Tool**

---

## 📦 Appendix
- **Code Files:** Python scripts for data preprocessing, sentiment analysis, and visualization.
- **Datasets:** Raw and cleaned CSV files.

---

**Developed by:** [AbhiChandraDondapati](https://github.com/AbhiChandraDondapati)  

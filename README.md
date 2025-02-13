# 📌 Sentiment Analysis Model Towards Webtoon Application

![Sentiment Analysis](https://webtoons-static.pstatic.net/image/pc/home/og_id.jpg?dt=2021111201)

## 📖 Overview
This project focuses on **Sentiment Analysis** for the Webtoon application using **Machine Learning**. The dataset is collected through **web scraping** from the Google Play Store, analyzing user reviews to determine sentiment polarity (positive or negative).

## 📊 Dataset
The dataset consists of user reviews scraped from the **Webtoon** app on Google Play Store, categorized into:
- **Positive Reviews** (Ratings: 4★ - 5★)
- **Negative Reviews** (Ratings: 1★ - 2★)

The dataset is preprocessed and used to train a sentiment classification model.

## 🚀 Features
- **Web Scraping**: Extracting real-world user reviews
- **Preprocessing**: Cleaning and transforming text data
- **Model Training**: Building a sentiment classification model
- **Evaluation**: Assessing model performance

## 🔧 Technologies Used
- Python 🐍
- Google Play Scraper 📱
- Pandas 📊
- Scikit-learn 🤖
- Natural Language Processing (NLP) 🗣

## 📌 Project Structure
```
📂 Sentiment-Analysis-Webtoon
 ┣ 📁 data              # Scraped dataset
 ┣ 📁 notebooks         # Jupyter Notebooks
 ┣ 📁 models           # Trained ML models
 ┣ 📜 README.md        # Project documentation
 ┣ 📜 requirements.txt  # Dependencies
```

## 📈 Results
The sentiment analysis model successfully classifies Webtoon reviews with **high accuracy**. Below is an example of predictions made by the model:

| **User Review** | **Predicted Sentiment** |
|----------------|-----------------------|
| "I love the Webtoon stories!" | 😊 Positive |
| "Too many ads, it's annoying!" | 😡 Negative |

## 🔍 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-webtoon.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the sentiment analysis model:
   ```bash
   python model.py
   ```

---
✨ **Star this repository** if you found it useful!

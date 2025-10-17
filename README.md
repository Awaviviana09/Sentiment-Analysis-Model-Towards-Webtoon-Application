<h1 align="center">💬 Sentiment Analysis Model Towards Webtoon Application</h1>

<p align="center">
  <b>Machine Learning | Natural Language Processing (NLP)</b><br>
  Analyzing user sentiments from Webtoon app reviews using Python and Scikit-learn
</p>


![Sentiment Analysis](https://webtoons-static.pstatic.net/image/pc/home/og_id.jpg?dt=2021111201)

---

## 📖 Overview
This project focuses on performing **Sentiment Analysis** for the **Webtoon Application** using **Machine Learning** and **Natural Language Processing (NLP)** techniques.  User reviews were collected through **web scraping** from the **Google Play Store**, then analyzed to determine their **sentiment polarity** — either **positive** or **negative**.  

The model aims to understand how users perceive the Webtoon app and to provide data-driven insights for app improvement.

---

## 📊 Dataset
The dataset consists of **user reviews** scraped directly from the **Webtoon App on Google Play Store**.  

| Sentiment | Rating Range | Description |
|------------|--------------|--------------|
| 😊 **Positive** | ⭐ 4–5 | Satisfied users expressing positive experiences |
| 😡 **Negative** | ⭐ 1–2 | Users expressing complaints or dissatisfaction |

The dataset undergoes preprocessing to clean and normalize text data before being used for model training.

---

## 🚀 Features
- 🕸 **Web Scraping** – Automatically extracts user reviews from Google Play Store  
- 🧹 **Data Preprocessing** – Cleans, tokenizes, and transforms text into model-ready format  
- 🤖 **Model Training** – Builds a classification model to detect sentiment polarity  
- 📈 **Evaluation** – Measures accuracy and model performance using validation metrics  

---


## 🔧 Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming Language** | Python 🐍 |
| **Data Collection** | Google Play Scraper 📱 |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn 🤖 |
| **Natural Language Processing** | NLTK, Regex, TF-IDF |
| **Development Environment** | Jupyter Notebook / Google Colab |

---

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

The trained model demonstrates strong predictive capability and can be extended for real-time sentiment analysis applications.

---

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

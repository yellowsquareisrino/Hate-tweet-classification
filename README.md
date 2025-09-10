# Hate Tweet Classification

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify tweets as **hate speech** or **not hate speech**.  
It demonstrates a complete workflow from **data cleaning**, **preprocessing**, **feature extraction**,to **model training and evaluation**.

---

## Project Structure
hate-tweet-classification
─ hate_tweet_classification.ipynb # Jupyter notebook with full code
─ requirements.txt # Libraries required
─ README.md # This file
─ dataset/ # Optional: dataset folder (small datasets only)

---

## How It Works

1. **Load Dataset** – CSV dataset of tweets with labels (`hate` or `not hate`).  
2. **Preprocess Text** – Cleaning, tokenization, stopword removal, and lemmatization.  
3. **Feature Extraction** – Convert tweets into **TF-IDF features**.  
4. **Train Models** – Logistic Regression and Naive Bayes models are trained.  
5. **Evaluation** – Accuracy, classification report, and sample predictions.  
6. **Test Predictions** – Try new tweets and see predicted labels.  

---

## Libraries Required

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- nltk  

Install dependencies using:  

```bash
pip install -r requirements.txt
--

## Sample Predictions
Tweet	Prediction
| Tweet                                | Prediction |
| ------------------------------------ | ---------- |
| "I love everyone, have a great day!" | Not Hate   |
| "You are so stupid, I hate you."     | Hate       |
Dataset

The dataset can be downloaded from Kaggle: https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech

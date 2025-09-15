

---

# 📊 Financial Tweet Sentiment Analysis ()

Classify financial news-related tweets as **Bullish 🟢**, **Bearish 🔴**, or **Neutral ⚪** using a fine-tuned DistilBERT model.

---

## ⚙️ Features

* Fine-tunes a transformer model (DistilBERT) for sentiment classification
* Supports **** and ** Trainer**
* Uses labeled finance-related tweets (training + validation sets)
* Outputs accuracy, F1-score, and confusion matrix

---

## 🚀 Quick Start

```bash
# Clone repo
git clone https://github.com/Mahwash75/Sentiment_Analysis-/financial-sentiment-distilbert.git


cd financial-sentiment-distilbert

# Install dependencies
pip install -r requirements.txt

# Train model
python src/train.py --trainer hf    # or --trainer lightning

# Evaluate
python src/evaluate.py
```

---

## 📌 Future Improvements

* Try other models like  RoBERTa or BERT ;
* Hyperparameter tuning
* Deploy as API or web app

---



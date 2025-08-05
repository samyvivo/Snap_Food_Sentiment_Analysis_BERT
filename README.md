# Snap_Food_Sentiment_Analysis_BERT

🚀 Fine-Tuning BERT on Persian Food Reviews 🇮🇷🍔
Today I explored training a sentiment analysis model for SnapFood user reviews in Persian (Farsi) 

🧠 Goal:
Classify 52,000 Persian reviews as Positive or Negative using BERT.

⚙️ Tech Stack:
🤗 transformers (HooshvareLab/bert-fa-base-uncased)

🧹 Preprocessing: tokenization, padding

⚖️ Evaluation: Accuracy, F1, AUC

🧠 Model: BertForSequenceClassification

🧪 Compare training:

🔥 My local machine: i7, 16GB RAM, GTX 1660 Ti

❄️ Google Colab: Tesla T4 GPU

⚔️ Results:
T4 (Colab) was 40–60% faster, thanks to FP16 & cooling.

My laptop reached 79°C — I had to literally cool it with ice 😅

Code is fully in Persian (Farsi RTL), and Streamlit app is also deployed ✅

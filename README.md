# SENTIMENT-ANALYSIS-OF-STAKEHOLDER-COMMENTS-e-Consultation-Module
# 🚀 Sentiment Analysis of Stakeholder Comments

*(e-Consultation Module)*

## 📌 Overview

An AI-powered web application that analyzes stakeholder comments using Natural Language Processing (NLP).

The system provides:

* ✅ Sentiment Analysis (Positive / Neutral / Negative)
* 😊 Emotion Detection (Joy, Anger, Fear, etc.)
* 📝 Automatic Text Summarization
* ☁️ Word Cloud Visualization

---

## 🧠 Tech Stack

* **FastAPI** – Backend framework
* **Hugging Face Transformers** – Pre-trained NLP models
* **PyTorch** – Deep learning inference
* **NLTK** – Text preprocessing
* **WordCloud & Matplotlib** – Visualization

---

## ⚙️ Run Locally

```bash
git clone https://github.com/Sudharshanjatothu/SENTIMENT-ANALYSIS-OF-STAKEHOLDER-COMMENTS-e-Consultation-Module.git
cd SENTIMENT-ANALYSIS-OF-STAKEHOLDER-COMMENTS-e-Consultation-Module

python -m venv .venv
.venv\Scripts\activate   # Windows

pip install -r requirements.txt
uvicorn app:app --reload
```

👉 Open:
http://127.0.0.1:8000

---

## 📊 API Docs

FastAPI auto-generates docs:

👉 http://127.0.0.1:8000/docs

---

## ✨ Features

* 🔍 Analyze user input or uploaded files
* ⚡ Real-time sentiment classification
* 🎭 Emotion detection with emoji output
* 📄 Extractive text summarization
* ☁️ Word cloud generation

---

## 📁 Project Structure

```
SENTIMENT-ANALYSIS/
│── app.py
│── requirements.txt
│── .gitignore
│
├── templates/
├── uploads/
├── wordclouds/
├── sentiment-model/
```

---

## ⚡ Performance

* Initial model loading may take a few seconds
* Response time depends on input length
* Optimization possible using lightweight models

---

## 📌 Future Enhancements

* 🚀 Faster inference using optimized models
* 🎨 Improved frontend UI
* 🌐 Cloud deployment (Render/AWS)
* 📊 Analytics dashboard

---

## 👨‍💻 Author

**Sudharshan Jatothu**

---

## ⭐ Support

If you found this useful, consider giving it a ⭐ on GitHub!

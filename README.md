# Fake-News-Classifier
#  And You Believed That? - Fake News Classifier

![Streamlit](https://img.shields.io/badge/streamlit-v1.0-brightgreen?style=flat-square)
![Transformers](https://img.shields.io/badge/huggingface-transformers-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

##  What is TruthLens AI?

**TruthLens AI** is a real-time fake news detection tool built using the power of **Natural Language Processing (NLP)** and **Zero-Shot Learning** from HuggingFace Transformers. With a simple, interactive **Streamlit** interface, users can input any headline or article to instantly verify its authenticity.

---

##  Features

-  **Zero-Shot Fake News Classification** using `facebook/bart-large-mnli`
-  **Image Upload Support** (optional screenshot of article)
-  **Confidence Score** displayed for transparency
-  **Keyword Frequency Analysis** sidebar
-  **Past Predictions** log
-  **Downloadable CSV Logs**
-  **Feedback Collection**
-  **Rating System**
-  **Email Alerts** for high-confidence fake news (configurable)

---

##  Tech Stack

- [Streamlit](https://streamlit.io/) - UI & Frontend
- [Hugging Face Transformers](https://huggingface.co/transformers/) - AI/NLP backend
- [Facebook BART Large MNLI](https://huggingface.co/facebook/bart-large-mnli) - Pre-trained zero-shot model
- [Pandas](https://pandas.pydata.org/) - Data manipulation
- [SMTP](https://docs.python.org/3/library/smtplib.html) - Email alerts

---

##  Installation Guide
1.Install dependencies:
pip install streamlit transformers torch pandas scikit-learn email-validator

2.Run the app:
streamlit run mytool.py

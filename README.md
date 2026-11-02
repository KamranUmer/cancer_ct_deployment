<div align="center">

# 🫁 Lung Cancer CT Classifier · Streamlit

**Classify chest CT scans into four lung cancer categories, with an AI assistant to explain the result.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"> <img src="https://img.shields.io/badge/Groq%20%C2%B7%20Llama%203-F55036?style=for-the-badge" alt="Groq · Llama 3"> <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini">

</div>

## 📌 Overview

A deployment of the lung CT classifier from [lungs-cancer-classification-ct-scan](https://github.com/KamranUmer/lungs-cancer-classification-ct-scan). Upload a CT slice and the app predicts one of four classes; a chat assistant (Llama 3 on Groq, with Gemini support) can answer follow-up questions about the result.

## ✨ Features

- Classes: **Normal**, **Adenocarcinoma**, **Large Cell Carcinoma**, **Squamous Cell Carcinoma**
- Object-oriented app: `MyModel` (load + predict) and `Ui` (Streamlit layout)
- Prediction confidence shown with the result
- LangChain chat assistant in `chat_bot.py`

## 🚀 Getting Started

```bash
git clone https://github.com/KamranUmer/cancer_ct_deployment.git
cd cancer_ct_deployment
pip install -r requirements.txt
streamlit run main.py
```

## 📁 Project Structure

```
cancer_ct_deployment/
├── main.py           # Streamlit app (model + UI)
├── chat_bot.py       # LLM assistant
└── requirements.txt  # dependencies
```

## ⚠️ Disclaimer

This project is for research and learning only. It is **not** a medical device and must not be used for diagnosis or treatment decisions.

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>

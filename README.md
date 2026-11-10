# 🤖 FAQ Chatbot

## 📌 Project Description

This project is an AI-based FAQ Chatbot developed using Python.
It uses Natural Language Processing (NLP) and text similarity
techniques to understand user questions and provide the most
relevant answers from a predefined FAQ dataset.

## 🎯 Objective

The main objective of this project is to provide quick and
automatic answers to frequently asked questions without
requiring manual assistance.

## 🛠️ Technologies Used

- Python
- Natural Language Processing (NLP)
- NLTK
- TF-IDF
- Cosine Similarity
- Scikit-learn
- Tkinter

## ⚙️ How It Works

1. User enters a question.
2. The question is converted to lowercase.
3. Unnecessary characters are removed.
4. The text is tokenized using NLTK.
5. TF-IDF converts the FAQ questions into numerical vectors.
6. Cosine Similarity compares the user's question with stored FAQs.
7. The chatbot finds the most similar question.
8. The corresponding answer is displayed.
9. If no suitable match is found, the chatbot displays a fallback message.

## 📂 Project Structure

```text
FAQ_Chatbot/
│
├── app.py
├── faqs.py
├── requirements.txt
├── README.md
└── __pycache__/
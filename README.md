# 📧 Spam Email Classifier

A machine learning web application that classifies whether an email subject line is **Spam** or **Not Spam** using a **Multinomial Naive Bayes** model. The application is built using **Python, Flask, HTML/CSS, and scikit-learn**.

---

## 🧩 Problem Statement

Spam emails have become a major problem for email users, often filling inboxes with unwanted messages and potentially containing phishing links or malicious content.

The goal of this project is to demonstrate how **Machine Learning and Natural Language Processing (NLP)** techniques can be used to automatically identify spam messages and provide a quick classification result.

This application takes an email subject line as input and predicts whether it is **Spam** or **Not Spam** using a trained machine learning model.

---

## 🚀 Project Overview

The **Spam Email Classifier** provides a simple web interface where users can enter an email subject line.

The entered text is processed using a machine learning pipeline consisting of:

- **CountVectorizer** for converting text into numerical features
- **Multinomial Naive Bayes** for classification

After processing the input, the application instantly displays the prediction as either:

> 🛑 **Spam**

or

> ✅ **Not Spam**

The project demonstrates the integration of **Machine Learning with a Flask web application**.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Backend development and machine learning |
| **Flask** | Web application framework |
| **HTML** | Web page structure |
| **CSS** | User interface styling |
| **scikit-learn** | Machine learning model and NLP pipeline |
| **Pandas** | Dataset handling and preprocessing |
| **Jupyter Notebook** | Model development and experimentation |

---

## ✨ Features

- 🔍 **Real-time spam detection**
- 📧 Classifies email subject lines as **Spam** or **Not Spam**
- 🧠 Uses **Multinomial Naive Bayes**
- 🔤 Uses **CountVectorizer** for text feature extraction
- 🌐 Flask-based web application
- 🎨 Clean and responsive glass-themed user interface
- 🔄 Uses the **Post/Redirect/Get** pattern to prevent duplicate submissions after refreshing
- 📦 Lightweight and easy to run locally
- 🚀 Easy to extend and deploy

---

## 🧠 Machine Learning Workflow

```text
Email Subject
      ↓
Text Preprocessing
      ↓
CountVectorizer
      ↓
Numerical Feature Extraction
      ↓
Multinomial Naive Bayes
      ↓
Prediction
      ↓
Spam / Not Spam

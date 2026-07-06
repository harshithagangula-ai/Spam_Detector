# 📧 Spam Detector

A Machine Learning-based Spam Detector that classifies messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP).

---

## 📌 Features

- Detects whether a message is Spam or Ham
- Text preprocessing using NLP techniques
- TF-IDF Vectorization
- Trained Machine Learning model
- Simple and easy-to-use interface

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Pickle

---

## 📂 Project Structure

```
SpamD/
│── datasets/
│── src/
│── model.pkl
│── vectorizer.pkl
│── requirements.txt
│── README.md
│── .gitignore
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd SpamD
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python src/main.py
```

> Replace `main.py` with your actual Python file if it has a different name.

---

## 📊 Machine Learning Pipeline

1. Load dataset
2. Clean and preprocess text
3. Convert text into numerical features using TF-IDF
4. Train the Machine Learning model
5. Save the trained model using Pickle
6. Predict whether new messages are Spam or Ham

---

## 📁 Dataset

The dataset contains SMS messages labeled as:

- Spam
- Ham (Not Spam)

---

## 📦 Model Files

- `model.pkl` – Trained Machine Learning model
- `vectorizer.pkl` – TF-IDF Vectorizer

---

## 📌 Requirements

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## 📜 License

This project is developed for educational purposes.

# Duplicate Question Pairs Detection

A machine learning and Natural Language Processing (NLP) web application that checks whether two questions have the same meaning. The application is deployed using Streamlit.

## 🚀 Live Demo

Try the application here:

[Duplicate Question Pairs Detection – Streamlit App](https://duplicatequestionpairs-pe92vzfdkfmjxekztejyiw.streamlit.app/)

## 📌 Project Overview

People often ask the same question using different words. For example:

- **Question 1:** How can I learn Python?
- **Question 2:** What is the best way to start learning Python?

Although the wording is different, both questions have a similar meaning.

This project aims to identify whether a pair of questions is **duplicate** or **not duplicate** using Natural Language Processing and machine learning.

## ✨ Key Features

- Accepts two questions as input.
- Analyzes the questions to identify similarity.
- Predicts whether the questions are duplicate or not duplicate.
- Provides a simple, interactive interface built with Streamlit.
- Accessible online through the deployed application.

## 🛠️ Technologies

The project is intended for a Python-based NLP/ML workflow:

- **Python** – primary programming language
- **Streamlit** – web application interface
- **Pandas and NumPy** – data handling
- **Scikit-learn** – machine learning utilities
- **NLP techniques** – text preprocessing and question-pair analysis

*Update this list to match the exact libraries and model used in your implementation.*

## ⚙️ Run the Project Locally

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd <your-project-folder>
```

### 2. Create and activate a virtual environment (recommended)

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

If your project contains a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

Otherwise, install the packages required by your source code.

### 4. Start the Streamlit application

Replace `app.py` with the name of your main Streamlit Python file if it is different.

```bash
streamlit run app.py
```

The application will usually open at:

```text
http://localhost:8501
```

## 🧪 Example

| Question 1 | Question 2 | Expected meaning |
|---|---|---|
| How do I improve my English? | What can I do to speak English better? | Similar |
| What is machine learning? | How can I make a chocolate cake? | Different |

The actual prediction depends on the model and input processing used by the application.

## 📁 Suggested Project Structure

```text
Duplicate-Question-Pairs/
│
├── app.py                 # Streamlit application
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── model/                 # Trained model files (if applicable)
└── data/                  # Dataset files (if applicable)
```

Your actual folder and file names may be different.

## 🎯 Objective

The objective of this project is to explore how machine learning and NLP can understand the relationship between two text questions and help identify semantically similar or duplicate questions.

## 👨‍💻 Author

**Tanmay Paul**

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.

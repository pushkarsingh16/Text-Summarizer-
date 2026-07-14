# 📝 Text Summarizer

A simple Text Summarization web application built with **FastAPI** and **Hugging Face Transformers (T5)**. Paste a dialogue or long text, and the model generates a concise summary.

## 🚀 Features

- Text summarization using **T5-Base**
- FastAPI backend
- Simple HTML frontend
- Automatic text cleaning before summarization
- Supports CPU, CUDA, and Apple Silicon (MPS)

## 🛠️ Tech Stack

- Python
- FastAPI
- Hugging Face Transformers
- PyTorch
- Jinja2
- HTML/CSS/JavaScript

## 📂 Project Structure

```
.
├── app.py
├── index.html
├── requirements.txt
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/pushkarsingh16/Text-Summarizer-.git
cd Text-Summarizer-
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
uvicorn app:app --reload
```

Open your browser:

```
http://127.0.0.1:8000
```

## 📌 API Endpoint

**POST** `/summarize/`

Request:

```json
{
  "dialogue": "Your text here..."
}
```

Response:

```json
{
  "summary": "Generated summary..."
}
```

## 📸 Preview

Add a screenshot of the application here.

## 📄 License

This project is licensed under the MIT License.

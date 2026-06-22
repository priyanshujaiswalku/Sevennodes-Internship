# Sevennodes-Internship

# 📄 PDF-LLM Chatbot

A web-based application that enables users to upload PDF documents, extract and process their content, and interact with the document through an intelligent chatbot interface.

## 🚀 Features

* 📂 **PDF Upload & Processing**
  Upload PDF files and extract textual content efficiently.

* 🧾 **Table Extraction**
  Extract structured tables from PDFs using Camelot.

* 🤖 **Chatbot Interface**
  Ask questions and interact with the document in a conversational manner.

* 📝 **Text Summarization (Optional)**
  Summarize long documents using DeepSeek R1 and Hugging Face Transformers.

* 💻 **User-Friendly UI**
  Built with Next.js for a smooth and interactive frontend experience.

---

## 🛠️ Tech Stack

* **Backend:** Python
* **Frontend:** Next.js
* **Libraries & Tools:**

  * Camelot – PDF table extraction
  * Hugging Face Transformers – Summarization pipeline
  * DeepSeek R1 – LLM-based summarization

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/pdf-chatbot.git
cd pdf-chatbot
```

### 2. Set Up Virtual Environment

```bash
python -m venv venv
```

#### Activate Environment:

* **Windows:**

```bash
venv\Scripts\activate
```

* **Mac/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

---

## ⚠️ Known Limitations

* Summarization may be slower for large documents when enabled.
* Performance depends on system resources and model size.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Contribution

Feel free to fork this repository and contribute by submitting a pull request.

---

# 📄 LangChain Document Loader

## 🚀 Overview

A simple project demonstrating how to load data from:

* 📁 Text files
* 🌐 Web pages

using **LangChain Document Loaders**.

---

## 🛠️ Tech Stack

* Python
* LangChain

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/langchain-document-loader.git
cd langchain-document-loader
pip install -r requirements.txt
```

---

## ▶️ Usage

### Load Text File

```bash
python text_loader.py
```

### Load Web Page

```bash
python web_loader.py
```

---

## ⚠️ Notes

* Install PyTorch if needed:

```bash
pip install torch
```

* Set User-Agent to avoid blocking:

```python
import os
os.environ["USER_AGENT"] = "Mozilla/5.0"
```

* Some sites (Flipkart, Amazon) may block requests with CAPTCHA.

---

## 📌 Future Scope

* Add LLM integration
* Build chatbot over documents
* Support PDFs

---

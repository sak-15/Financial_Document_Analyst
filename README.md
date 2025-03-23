# 📊 Financial Document Analyzer using RAG (Locally Powered)

Welcome to your **own private financial document analyst** – running completely **locally**, powered by **Retrieval-Augmented Generation (RAG)**. Upload PDFs, ask financial questions, and get intelligent, contextual responses in real-time – no data ever leaves your machine.

> 🔐 *Private. Smart. Fast. All yours.*


<img width="1469" alt="image" src="https://github.com/user-attachments/assets/61054554-f671-401f-ac55-2d60aea1a854" />

---

## 🚀 What does this app do?

This Streamlit app allows users to:

- Upload any **financial PDF documents** (e.g., 10-Q, 10-K, annual reports) or **Select from existing documents from Vector DB**.

  <img width="1470" alt="Screenshot 2025-03-23 at 9 57 39 PM" src="https://github.com/user-attachments/assets/9f14ea00-6877-461a-a2c0-af8027f44caa" />

- Visually explore all pages as images in the sidebar.

  <img width="1470" alt="Screenshot 2025-03-23 at 9 57 13 PM" src="https://github.com/user-attachments/assets/2f8fb120-f540-48ab-ac6e-428cee71d341" />

- Chunk, embed, and store them in a **FAISS-based vector database**.
- Ask **natural language questions**, and get **context-aware answers** using **LangChain** and **Ollama's LLMs**.

  <img width="1470" alt="Screenshot 2025-03-23 at 10 03 21 PM" src="https://github.com/user-attachments/assets/83bd20a9-7fea-494e-b706-1a739b236978" />

<img width="1470" alt="Screenshot 2025-03-23 at 10 03 34 PM" src="https://github.com/user-attachments/assets/6d8b81b3-ec52-4307-8b7f-cb80e1cb219c" />


- Reuse previously processed documents without uploading again.
  
---
## ⚙️ Workflows

![Document_ingestion drawio](https://github.com/user-attachments/assets/4511fad5-4b03-4941-ab0e-1583815ef86c)

![Retrieval drawio (1)](https://github.com/user-attachments/assets/3388fcb7-a945-45d0-a8bc-cc1a087251ca)

---

## 🧠 How does it work?

This app is built using:

- **Streamlit** for the front-end interface.
- **LangChain** to manage the document-processing and RAG pipeline.
- **Ollama** to host local language models like `deepseek-r1:1.5b` and `nomic-embed-text`.
- **FAISS** for fast and local similarity search on embedded document chunks.
- **pdf2image** and **Pillow** to visualize each PDF page.
- **docling** to convert complex documents into clean Markdown for better processing.

---

## 📁 Project Structure

```plaintext
├── app.py                  # Main Streamlit app
├── rag.py                  # All document processing, vector DB, and RAG logic
├── requirements.txt        # All required packages
├── .gitignore              # Ignore virtual environments and temp files
├── venv/                   # Your virtual environment (not uploaded to Git)
├── vector_db/              # Where vector stores and PDFs are saved
├── LICENSE (MIT)           # MIT License – free to use and deploy
```
---

## 💬 Sample Questions You Can Ask

- What is the company’s profit for 2023?
- What were the main expenses in Q3?
- How much did the company earn in total revenue?
- Has the company posted any losses?

---

## 🔮 What’s Next?

1. Add multiple PDF upload support
2. Add export to PDF/Excel
3. Add PDF summarization feature
4. Add more file format support ( eg. excel, json, etc.)

---

## 📝 License
This project is licensed under the MIT License – feel free to fork it, deploy it, and build on top of it!

---

#### If you liked this project, give it a ⭐!

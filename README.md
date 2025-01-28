# Chat with Multiple PDFs using GROQ

This Streamlit app allows you to upload multiple PDF files, process their content into chunks, and query the information using a conversational AI model powered by **GROQ's Llama3-8b-8192**.

---

## Features

- Upload multiple PDF files.
- Extract and process text into searchable chunks.
- Store vector embeddings using FAISS for efficient similarity search.
- Ask questions and get detailed answers based on the PDF context.
- Uses HuggingFace embeddings and GROQ for seamless performance.

---

## Requirements

- Python >=3.10
- Required Python packages:
  ```bash
  streamlit
  PyPDF2
  langchain
  langchain_community
  langchain_groq
  python-dotenv

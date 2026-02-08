# PDF RAG Chatbot

A **Retrieval-Augmented Generation (RAG)** chatbot to ask questions on **PDF documents**. Answers are **grounded in your document**, using **BERT embeddings + GPT-2/T5 + ChromaDB**.

---

## Features

* Upload and process PDFs
* Semantic search with **BERT**
* Answer generation with **GPT-2/T5**
* Vector storage in **ChromaDB**
* Only answers from the document (no hallucinations)

---

## Installation

```bash
git clone https://github.com/0samaHaider/pdf-rag-chatbot.git
cd pdf-rag-chatbot
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter notebook:

```bash
jupyter notebook rag_chatbot.ipynb
```

Ask questions about your PDF.
If the answer is not in the document, the bot will say:

```
I cannot find this information in the provided documents.
```

---

## Future Improvements

* Streamlit frontend
* Multiple PDF support
* Chat history
* Larger open-source LLMs

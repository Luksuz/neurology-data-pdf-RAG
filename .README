# 🧠 LLM RAG Application

## 🚀 Overview

This repository contains a Retrieval-Augmented Generation (RAG) application built with a Language Model (LLM) for querying a neurology PDF. The application loads data into a Pinecone vector database and performs similarity searches using a Google Cloud Functions API, with a simple web interface for querying.

## 📂 Contents

- **`dataloader.ipynb`**: Loads text data from a neurology PDF into Pinecone.
- **`similarity_search.ipynb`**: Executes similarity searches and generates responses using a Google Cloud Functions API.
- **`index.html`**: Web interface for querying the RAG system.

## 🛠 Installation

### Prerequisites

- 🐍 Python 3.7+
- 🌲 [Pinecone API Key](https://www.pinecone.io/)
- 🤖 [OpenAI API Key](https://openai.com/api/)
- ☁️ [Google Cloud SDK](https://cloud.google.com/sdk)

### Install Dependencies

```bash
pip install -r requirements.txt
```

## 📖 Usage

### 📊 Data Loading

Run `dataloader.ipynb` to chunk and store PDF text in Pinecone.

### 🔍 Similarity Search

Run `similarity_search.ipynb` to perform searches and generate responses via the API.

### 🌐 Web Interface

Open `index.html` in a browser to interact with the RAG system.

## ☁️ Deployment

### Google Cloud Functions

Deploy the API with:

```bash
gcloud functions deploy generate --runtime python310 --trigger-http --allow-unauthenticated
```

Enjoy exploring the RAG system! 🎉

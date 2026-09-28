# YouTube Chatbot

An AI-powered chatbot that allows users to **ask questions about the content of a YouTube video**. The system extracts the video's transcript, converts the transcript into searchable vector representations, retrieves the most relevant parts using **semantic search**, and generates an answer using a Large Language Model (LLM).

## 🚀 Features

* Extracts transcripts from YouTube videos
* Splits long transcripts into smaller chunks
* Generates vector embeddings for transcript chunks
* Performs **semantic search** to retrieve relevant information
* Uses retrieved context to generate answers
* Enables question answering over YouTube video content

## 🏗️ Architecture

```text
YouTube Video
      ↓
Transcript Extraction
      ↓
Text Cleaning
      ↓
Text Chunking
      ↓
Embedding Generation
      ↓
Vector Database / Similarity Search
      ↓
User Question
      ↓
Question Embedding
      ↓
Semantic Search
      ↓
Relevant Transcript Chunks
      ↓
LLM
      ↓
Generated Answer
```

## 🔧 Technologies Used

* **Python**
* **YouTube Transcript API** – Extracts video transcripts
* **Hugging Face** – Provides embedding/LLM models
* **LangChain** – Handles text processing and retrieval workflow
* **Vector Similarity Search** – Retrieves semantically relevant transcript chunks

## 🔍 How Semantic Search Works

The transcript is divided into smaller chunks.

For every chunk:

```text
Tran
```

Personal Knowledge Chat App

Overview

This project is a Retrieval-Augmented Generation (RAG) application that allows users to ask questions about documents stored in a directory. The application leverages LangChain, Ollama embeddings, and Groq's LLM (LLaMA-3.3-70B-Versatile) to generate responses based on document context. It also features a Gradio interface for user interaction.

Features

Automatic PDF Loading: Reads documents from a specified directory.

Text Splitting: Uses RecursiveCharacterTextSplitter for efficient chunking.

Embeddings with Ollama: Generates embeddings to facilitate retrieval.

Vector Store with Chroma: Stores document chunks for quick retrieval.

Chat Interface: Uses Gradio for user-friendly question answering.

Fast Response Times: Measures and displays response latency.

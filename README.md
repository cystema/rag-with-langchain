# Google Gemini API & LangChain - RAG Chain for PDF Querying

This repository contains a simple Jupyter notebook that walks through the process of integrating Google’s Gemini API with LangChain to create a Retrieval-Augmented Generation (RAG) system for querying PDFs. It starts with the basics of using the Google Gemini API and progressively builds up to a full workflow, including text extraction, embedding creation, and building a chain to answer queries based on document content.

## Features
- Google Gemini API Basics: Learn how to set up and interact with the Google Gemini API for text generation.
- PDF Text Extraction: Utilize LangChain to extract text from a PDF document and prepare it for further processing.
- Embedding Creation: Create vector embeddings from the extracted text using Google Generative AI models via LangChain.
- RAG Chain Construction: Build a Retrieval-Augmented Generation (RAG) chain to perform question-answering over the document, leveraging the power of embeddings and language models.

## How to Use
- Clone the repository and open the provided Jupyter notebook.
- Install the necessary dependencies (LangChain, PyPDF, Chroma, Google Generative AI SDK, etc.).
- Follow along with the notebook to see how to integrate Google Gemini API with LangChain for document-based Q&A.

## Prerequisites
- Python 3.x
- API Key for Google Gemini
- Jupyter Notebook
- PDF document for testing

## Getting Started
- Clone the repository:
```
git clone https://github.com/your-repo/google-gemini-langchain-pdf-qa.git
```
- Install dependencies:
```
pip install -r requirements.txt
```
- Open the notebook and start following the steps to build your RAG system!

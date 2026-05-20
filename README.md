# RAG Document Summarizer

An AI-powered document summarization system built using Retrieval-Augmented Generation (RAG) techniques. The application allows users to upload documents and generate intelligent summaries using LLM-based processing.

## Features

* Upload and process documents
* AI-generated document summaries
* Retrieval-Augmented Generation (RAG) pipeline
* FastAPI backend integration
* Docker support for deployment
* Clean and lightweight frontend interface

## Tech Stack

* Python
* FastAPI
* HTML/CSS/JavaScript
* Docker
* LLM APIs
* RAG Architecture

## Project Structure

```bash
├── app.py
├── rag_engine.py
├── index.html
├── requirements.txt
├── Dockerfile
└── .gitignore
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/amaankhan-ai/<repository-name>.git
cd <repository-name>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

## Docker Setup

Build Docker image:

```bash
docker build -t rag-document-summarizer .
```

Run Docker container:

```bash
docker run -p 5000:5000 rag-document-summarizer
```

## Future Improvements

* Multi-document support
* Chat with documents
* PDF parsing enhancements
* Vector database integration
* Cloud deployment support

## Author

Mohammed Amaan Khan

* LinkedIn: https://linkedin.com/in/amaankhan971
* GitHub: https://github.com/amaankhan-ai


# Multi-Document Agent System with LLaMA and Mistral

This project implements a multi-document agent system using advanced language models, vector stores, and document summarization techniques. The goal is to facilitate the querying and summarizing of documents, such as contracts, using vector-based searches and large language models (LLMs).

## Features
- **Document Loading and Querying:** Load documents from directories, split them into manageable chunks, and create vector stores for querying.
- **Summarization:** Provide a holistic summary of documents using LLaMA 3.1 and Mistral large language models.
- **Vector Search:** Use FAISS and ChromaDB to perform efficient similarity searches on documents.
- **Custom Agent System:** Retrieve relevant tools and apply them to execute queries based on context.
- **LLMs Integration:** Support for multiple LLMs like LLaMA 3.1 and Mistral for enhanced document understanding.

## Installation

To set up the project, follow the steps below:

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

    faiss-cpu
    chromadb
    langchain
    llama-index
    ollama
    mistral
    llama-index
    llama-index-llms-huggingface
    Unstructured[md]
    llama-index-vector-stores-chroma
    llama-index-llms-groq
    einops
    accelerate
    sentence-transformers
    llama-index-llms-mistralai
    llama-index-llms-openai

    ```

3. Set up environment variables:
    ```bash
    export MISTRAL_API_KEY="your_api_key"
    ```

4. Ensure that your ChromaDB is set up correctly for persistence.




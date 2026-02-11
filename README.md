# RAG Assignment – PDF-based Retrieval Augmented Generation

## Project Overview
This project implements a Retrieval Augmented Generation (RAG) system that answers user queries using information retrieved from a corpus of research PDF documents. The system combines vector similarity search with a large language model to generate grounded and accurate responses.

## Dataset
- Public research papers in PDF format
- Topics: Transformer models and large language models

## Tools & Libraries Used
- Python
- LangChain
- FAISS
- HuggingFace Sentence Transformers
- OpenRouter API
- Google Colab

## How to Run the Notebook
1. Upload the PDF files to the working directory in Google Colab.
2. Set the `OPENROUTER_API_KEY` as an environment variable using Colab Secrets.
3. Run all cells in the notebook from top to bottom.
4. Execute the test queries provided at the end of the notebook.

## Output
The system retrieves relevant document chunks and generates answers grounded in the source PDFs, displaying both the response and the source pages.

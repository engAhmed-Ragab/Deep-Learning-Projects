# 📘 Book Assistant with BART + RAG

A deep learning project that builds an AI assistant for PDF books using **BART** and **RAG (Retrieval-Augmented Generation)**.

## Features
- Upload a PDF book
- Extract text from the PDF
- Split text into chunks
- Generate embeddings using Sentence Transformers
- Store and search chunks using FAISS
- Generate book summaries with BART
- Answer questions based on the uploaded book using RAG
- Simple Streamlit interface

## Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- Sentence Transformers
- FAISS
- PyMuPDF
- Streamlit

## Project Workflow
1. Upload a PDF book
2. Extract text from the PDF
3. Split the text into chunks
4. Create embeddings for each chunk
5. Build a FAISS vector index
6. Retrieve the most relevant chunks for a user question
7. Use BART to generate:
   - a summary
   - an answer based on retrieved context

## Model Used
- **BART** for summarization and answer generation
- **all-MiniLM-L6-v2** for text embeddings

## Notes
- The current version works better with text-based PDFs
- Scanned PDFs may require OCR for better extraction quality

## Future Improvements
- Add OCR support for scanned PDFs
- Improve answer quality with better prompt design
- Add page number references in answers
- Support multi-book conversations

## Author
Yomna Ragab

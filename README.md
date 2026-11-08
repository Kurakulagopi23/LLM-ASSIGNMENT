Tuvalu IMF PDF-to-Dashboard Analysis

## Project Overview
This project implements an end-to-end AI-powered pipeline to extract, analyse and visualise macroeconomic indicators and financial stability risks from the **IMF Tuvalu 2025 Article IV Consultation Report (No. 25/257)**.

## Tools and Technologies
- **Environment:** Python, Google Colab
- **LLM:** Gemini 3.5 Flash-Lite
- **PDF Processing:** PyMuPDF, tiktoken
- **RAG:** Sentence-Transformers (all-MiniLM-L6-v2), FAISS
- **Data Analysis:** Pandas, NumPy
- **Visualisation:** Matplotlib

## Implementation
The notebook contains **15 sequential cells** covering:

1. **PDF Processing:** Text extraction, cleaning, token-aware chunking and section summarisation.
2. **Structured Extraction:** Seven financial stability themes, numerical JSON indicators, strengths, vulnerabilities and historical trends.
3. **RAG:** Local dense embeddings, FAISS retrieval and evidence-grounded question answering.
4. **Dashboard:** Four high-resolution visualisations with

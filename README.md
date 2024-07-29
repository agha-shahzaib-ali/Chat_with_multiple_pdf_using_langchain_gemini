# Chat with Multiple PDFs using Gemini

This Streamlit application allows users to interact with multiple PDF files through a conversational interface powered by Google Gemini's generative AI. Users can upload PDF documents, which are then processed to enable question-answering functionality based on the content of the PDFs.

## Features

- **Upload Multiple PDFs:** Users can upload multiple PDF files for processing.
- **Extract and Process Text:** The application extracts text from the uploaded PDFs and splits it into manageable chunks.
- **Vector Store Creation:** The extracted text is embedded and stored in a local FAISS vector store for efficient retrieval.
- **Conversational Interface:** Users can ask questions, and the system will provide detailed answers based on the content of the PDFs.

## Requirements

- Python 3.7 or higher
- Streamlit
- PyPDF2
- LangChain
- Google Generative AI
- FAISS
- `python-dotenv`

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Bilal7855/English-Text-to-Sql-query-Converter.git
   cd English-Text-to-Sql-query-Converter

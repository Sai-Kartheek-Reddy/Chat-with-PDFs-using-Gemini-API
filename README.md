# Chat with Multiple PDFs using Gemini-powered Q&A

## Project Description

This project harnesses the power of the Gemini API to enable conversational interactions with PDF documents. By integrating Gemini API key, users can engage in chat-based queries and receive detailed responses directly from their uploaded PDFs. It streamlines the process of extracting information from multiple PDFs and facilitates seamless communication with the documents' contents.

## Installation

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
```

## Usage

- Upload your PDF files.
- Ask questions related to the uploaded PDFs.
- Receive detailed responses based on the content of the PDF documents.

## Code Structure

- get_pdf_text(pdf_docs): Extracts all text from the uploaded PDFs, akin to a comprehensive highlighter.
- get_text_chunks(text): Divides the extracted text into smaller, more manageable segments.
- get_vector_store(text_chunks): Converts the segmented text into a specialized code for computational understanding, resembling a secret language for text.
- get_conversational_chain(): Serves as the core engine, formulating queries to the computer based on the PDFs and retrieving elaborative answers.
- user_input(user_question): Translates user questions into the secret computer language, seeks answers from the document content using the core engine, and presents the responses in plain English.
- main(): Entry point for executing the program.

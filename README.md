# NLP_20216

# Question Answering System

This system leverages AI to extract and answer questions from a PDF document. It uses OpenAI's GPT models for generating answers and hnswlib for indexing and searching text. This solution is designed to help users quickly find information contained within lengthy PDFs without reading the entire document.

## Features

- *PDF Text Extraction*: Converts PDF files into text.
- *Text Tokenization*: Splits text into manageable chunks for better processing.
- *Text Embedding*: Converts text chunks into embeddings using OpenAI's models.
- *Efficient Search*: Utilizes hnswlib for fast retrieval of relevant text chunks.
- *Question Answering*: Generates answers to user queries based on the context extracted from the PDF.

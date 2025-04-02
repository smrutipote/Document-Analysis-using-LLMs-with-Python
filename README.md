# Document Analysis using LLMs with Python

## Overview
This project demonstrates how to analyze documents using Large Language Models (LLMs) in Python. It covers text extraction from PDFs, summarization, question generation, and answering using state-of-the-art NLP models.

## Features
- Extract text from PDF files
- Summarize documents using a pre-trained model
- Split text into sentences and passages for better analysis
- Generate questions based on document content
- Answer generated questions using a question-answering model

## Installation
### Prerequisites
Ensure you have Python 3.7 or higher installed on your system. Then, install the required dependencies:

```bash
pip install pdfplumber transformers nltk torch
```

Title: Document Analysis using LLMs with Python

Description:

Perform document analysis using Large Language Models (LLMs) in Python.

Tasks include text extraction, summarization, question generation, and answering.

🚀 Features
📄 Extract text from PDFs using pdfplumber.

✂ Summarize long documents using t5-small.

📑 Split documents into manageable passages.

❓ Generate questions from document content using valhalla/t5-base-qg-hl.

🤖 Answer questions using a pre-trained roberta-base-squad2 model.


📌 Generated Questions
1. What are the Google Terms of Service about?  
2. When were the terms last modified?  
3. What does this document explain?
   
🤝 Contributing
Fork the repository

Create a new branch (git checkout -b feature-name)

Make changes & commit (git commit -m "Added feature XYZ")

Push to your branch (git push origin feature-name)

Submit a Pull Request

## Results
This project successfully extracts text from a PDF, summarizes it, generates relevant questions, and provides answers. The combination of NLP models enhances the document analysis process, making it more efficient and insightful.

## Repository Structure
```
|-- document_analysis_llms/
    |-- extracted_text.txt    # Text extracted from PDF
    |-- document_analysis.py  # Main script for document analysis
    |-- README.md             # Project documentation
```

## Conclusion
Large Language Models (LLMs) are highly effective for document analysis. This project showcases their ability to summarize, generate questions, and provide answers, making document processing more automated and insightful.


## Medium Article
(https://medium.com/@smruti.po1106/document-analysis-using-llms-with-python-ba34817969e7)

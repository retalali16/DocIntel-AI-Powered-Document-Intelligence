# DocIntel | AI-Powered Document Intelligence

An AI-powered document processing platform combining **Azure AI Document Intelligence, custom model training, and intelligent document conversations** in one application.

### Core Capabilities

- **Document Understanding:** Extract text, layout, and structured information from multiple document types using Azure AI Document Intelligence.
- **Custom Model Training:** Train and use custom extraction models to extract structured data from CVs and other supported documents.
- **Batch Processing:** Process multiple PDF documents and use different trained models within the same workflow.
- **Multilingual Support:** Analyze documents in multiple languages.
- **Chat with Your Documents:** Ask questions about uploaded documents and receive AI-generated, context-grounded answers in the same language as your query.
- **Azure Blob Storage:** Store uploaded documents in the cloud and retrieve them for analysis and question answering.
- **Caching:** Cache processing results to reduce redundant operations and improve efficiency.
- **Visual Document Analysis:** Identify document sections and visualize extracted information directly on PDF pages.

### Built With

Python · Streamlit · Azure AI Document Intelligence · Azure OpenAI · Azure Blob Storage · PyMuPDF

### Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

Configure the required Azure credentials and deployment settings in your local `.env` file before running the application.

# DocIntel | AI-Powered Document Intelligence

An intelligent document processing platform that combines **Azure AI Document Intelligence, custom CV extraction, and AI-powered document conversations** in one application.

### Core Capabilities

- **Document Understanding:** Extract text and layout information from different types of documents using Azure AI Document Intelligence.
- **Custom CV Extraction:** Train and deploy custom models to extract structured information from CVs.
- **Chat with Your Documents:** Ask questions about uploaded documents and receive AI-generated answers grounded in their content.
- **Azure Blob Storage:** Store uploaded documents in the cloud and retrieve them for analysis and question answering.
- **Visual Document Analysis:** Classify document sections and visualize extracted content directly on PDF pages.

### Built With

Python · Streamlit · Azure AI Document Intelligence · Azure OpenAI · Azure Blob Storage · PyMuPDF

### Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

Configure the required Azure credentials and deployment settings in your local `.env` file before running the application.

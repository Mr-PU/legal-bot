# Legal Document Analyzer

A Streamlit web application that uses AI agents to analyze legal documents and provide insights through a team of specialized AI legal assistants.

## Features

- **Document Processing**: Upload and analyze PDF legal documents
- **AI Legal Team**: Coordinated team of specialized agents:
  - Legal Researcher: Finds relevant cases and precedents
  - Contract Analyst: Reviews contract terms and identifies issues
  - Legal Strategist: Develops legal strategies and recommendations
  - Legal Team Lead: Coordinates analysis between team members

- **Analysis Types**:
  - Contract Review
  - Legal Research
  - Risk Assessment
  - Compliance Check
  - Custom Query

## Setup & Requirements

1. **API Keys Required**:
   - OpenAI API key
   - Qdrant API key (for vector database)
   - Qdrant URL (default provided but configurable)

2. **Dependencies**:
   - streamlit
   - phi
   - openai
   - qdrant-client

## Usage

1. Configure API credentials in the sidebar
2. Upload a legal document (PDF format)
3. Select analysis type
4. For custom queries, enter your specific question
5. Click "Analyze" to process the document
6. View results in three tabs: Analysis, Key Points, and Recommendations

## Technical Details

The application uses:
- Phi library for AI agent workflows
- Qdrant vector database for document embedding storage
- PDF knowledge base for document analysis
- OpenAI models (gpt-4o) for analysis
- DuckDuckGo integration for additional research

## Note

This application requires valid API credentials to function properly. Configure all credentials before attempting document analysis.

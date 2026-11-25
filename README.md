# Azure AI Chatbot

A Python command-line chatbot built on Azure OpenAI in Microsoft Foundry.

## Features
- Uses the OpenAI Responses API with a model deployed in Microsoft Foundry
- Conversation memory using previous_response_id, so follow-up questions keep context
- Streaming responses, so answers appear word by word
- Settings and API key loaded from a local .env file (never committed)

## Setup
1. Install the libraries: `pip install -r requirements.txt`
2. Create a `.env` file with:
   - AZURE_OPENAI_ENDPOINT
   - MODEL_DEPLOYMENT
   - AZURE_OPENAI_API_KEY
3. Run: `python chat-app.py`

## Roadmap
- Browser-based web interface
- Retrieval-augmented generation (RAG) over my own documents
- Tool use and agent capabilities
- Microsoft Entra ID authentication instead of API keys

Built while studying for Microsoft AI-103 (Azure AI Apps and Agents).

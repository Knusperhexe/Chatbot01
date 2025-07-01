# Chatbot01

This project provides a simple GPT‑powered chatbot using LangChain. A sample n8n workflow is included to demonstrate how you can run the chatbot with context memory.

## Prerequisites

- **n8n** installed locally or running in Docker
- An **OpenAI API key** with access to `gpt-4.1-mini`

## Loading `chatbot-with-memory.json`

The workflow file can be found in the `flows` directory.

1. Start n8n and open the editor UI.
2. Click **Import** and select `flows/chatbot-with-memory.json` from this repository.
3. Save the workflow. You can now execute it or activate it to respond to chat messages.

## Chatbot capabilities

The flow contains a chat trigger, an AI agent node, an OpenAI chat model configured for `gpt-4.1-mini`, and a buffer memory node. Together, they allow the chatbot to remember recent conversation history and generate contextual replies.

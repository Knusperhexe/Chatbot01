# AGENTS Instructions

Create a simple n8n flow for a chatbot with context memory (using LangChain nodes and OpenAI).
- The flow should have:
  - A chat trigger node (waits for chat messages)
  - An AI agent node
  - An OpenAI chat model node (gpt-4.1-mini)
  - A memory node (buffer or window)
- Connect the nodes so that:
  - The chat trigger sends messages to the AI agent
  - The AI agent uses the OpenAI chat model and the memory node
- Save the flow as flows/chatbot-with-memory.json in standard n8n format.
- If a flows/ folder does not exist, create it.
- Do NOT add unrelated example nodes.
- Use only the minimal required configuration for each node.

## Format

## Example sections

### Code Style

### Testing

### Commit Messages

### PR Messages
- Provide a brief overview of the changes and mention any tests run.

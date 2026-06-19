
# n8n AI Agent — Conversational Memory & Code Tool Workflow

## Description
This is an n8n AI Agent workflow built as part of a self-paced AI/automation course assignment. The agent can hold a conversation, remember context across messages using memory, and execute custom logic through a code tool.

## How It Works
1. **Chat Trigger** — Listens for an incoming chat message
2. **AI Agent** — The core reasoning engine that decides how to respond
3. **Google Gemini Chat Model** — Powers the AI Agent's language understanding and generation
4. **Simple Memory** — Stores conversation history so the agent remembers earlier messages (e.g., user's name) within a session
5. **Code Tool** — A custom JavaScript tool the AI Agent can call to perform calculations or custom logic (e.g., estimating earnings)
workflow:
<img width="1359" height="723" alt="Screenshot 2026-06-18 182526" src="https://github.com/user-attachments/assets/ffe8262d-7f0f-4de4-afc2-ee370d64ea87" />
## Example Interaction
**User:** "Hi, what is my name and how much money can I earn in the AI field?"
**Agent:** Recalls the name from memory and uses the Code Tool to generate an earnings estimate.

## Tools Used
- n8n (self-hosted)
- Google Gemini API (Chat Model)
- n8n Simple Memory node
- n8n Code Tool node

## Key Learnings
- Difference between a simple workflow and an AI Agent
- How Tools (sub-nodes) extend an AI Agent's capabilities
- How Memory enables context-aware, multi-turn conversations
- Connecting Tool/Memory/Model sub-nodes correctly to the AI Agent node

## Status
✅ Working — Agent responds correctly using memory and custom code tool

## Note
This project is part of a personal AI automation learning course.


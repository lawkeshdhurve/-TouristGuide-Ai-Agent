# TouristGuide-Ai-Agent

🧳 Tourist Guide AI Agent (Built with n8n.io)

An AI-powered Tourist Guide built using n8n.io
.
This agent helps users discover popular India tours, suggests itineraries, and integrates with Google Sheets to store and update queries for future reference.

✨ Features

🗺️ Suggests popular India tours (Golden Triangle, Kerala Backwaters, Goa, etc.)

🤖 AI-powered responses using OpenAI Chat Model

💬 Real-time chat interface for tourists

📊 Google Sheets integration to log user queries and preferences

🧠 Memory-enabled conversations for contextual replies

🛠️ Tech Stack

n8n.io – Workflow automation platform

OpenAI – AI chat model integration

Google Sheets – Storing and updating user queries

Custom Webhook Chat UI – For tourist interactions

⚙️ Workflow Overview

Trigger: Chat message received (Webhook)

AI Agent: Processes query with OpenAI Chat Model

Memory: Keeps session context across conversations

Google Sheets: Logs & updates user input/output

Response: Sends results back to chat interface

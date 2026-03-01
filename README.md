🤖 AI WhatsApp Restaurant Bot (Built with n8n)
An AI-powered WhatsApp chatbot for restaurants that automates order taking, table reservations, and customer support using n8n workflow automation and OpenAI API.
This bot enables restaurants to handle customer interactions 24/7 without manual effort.

🚀 Features
📋 Digital menu sharing
🛒 Automated order placement
📅 Table reservation system
🤖 AI-powered natural language conversation
📦 Order confirmation messages
📊 Order data storage (Google Sheets / Database)

🛠️ Tech Stack
-n8n – Workflow automation
-WhatsApp Business API / Twilio – Messaging integration
-Google Gemini API – AI conversation handling
-Google Sheets / Database – Order storage
-Webhook – Real-time message trigger

⚙️ How It Works
Customer sends a message on WhatsApp.
WhatsApp API forwards the message to an n8n Webhook.
n8n processes the message:
-If it’s an order → Saves to database.
-If it’s a reservation → Stores booking details.
-If it’s a general query → Sends it to Gemini for AI response.
-The bot sends a response back to the customer via WhatsApp API.

📌 Workflow Overview
WhatsApp → Webhook (n8n) →
AI Processing (OpenAI)
Order Storage (Google Sheets)
Confirmation Message → WhatsApp Reply

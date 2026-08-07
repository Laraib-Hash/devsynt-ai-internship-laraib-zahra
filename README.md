# SlotWise — AI Booking Concierge Bot

SlotWise is an AI-powered salon appointment booking assistant built as part of the **AI Automation Engineering Internship — Project 1**.

The bot allows users to book salon appointments through a natural conversational flow using **Discord, n8n, an LLM, and Google Sheets**.

## 🚀 Features

- 🤖 AI-powered conversational booking
- 💬 Discord chatbot integration
- 🧠 AI Agent with conversation memory
- 💇 Salon service selection
- 📅 Date and time selection
- 🕐 Available appointment slots
- ✅ Booking confirmation
- 📊 Automatic Google Sheets booking logging
- 👤 Stores Discord username and user ID
- 🔄 Basic handoff for complaints and unsupported requests
- 📝 Separate logging of handoff requests

## 🛠️ Technologies Used

- **n8n** — Workflow automation
- **Discord** — User interface / chatbot platform
- **Groq LLM** — AI conversational processing
- **Google Sheets** — Booking and handoff logging
- **Python** — Discord bot integration
- **ngrok** — Webhook connectivity

## 💇 Available Services

The bot currently supports:

- Haircut
- Facial
- Manicure
- Pedicure
- Hair Coloring

## 🕐 Available Time Slots

The mock booking system provides:

- 10:00 AM
- 2:00 PM
- 5:00 PM

## 💬 Booking Flow

The conversation follows a short booking flow:

```text
User
  ↓
Discord
  ↓
n8n Webhook
  ↓
AI Agent
  ↓
Service Selection
  ↓
Date Selection
  ↓
Time Selection
  ↓
Booking Confirmation
  ↓
Google Sheets
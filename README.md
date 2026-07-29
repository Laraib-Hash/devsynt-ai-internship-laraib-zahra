# Task 2 – WhatsApp Automation (Phase 1)

## Niche

Dental Clinic Appointment Booking

## Objective

The goal of this task was to design a bilingual WhatsApp chatbot and connect Meta WhatsApp Cloud API with n8n using a production webhook.

## Completed Work

- Designed the complete conversation flow.
- Created bilingual (English & Arabic) bot message scripts.
- Configured Meta WhatsApp Cloud API Sandbox.
- Connected Meta Webhook to n8n using a static ngrok domain.
- Successfully received live WhatsApp messages inside n8n.

## Human Handoff

Medical questions, complaints, pricing negotiations, and other off-script conversations are transferred to a human representative instead of allowing the chatbot to guess or provide inaccurate information. This ensures customer safety and a better user experience.

## Bilingual Behaviour

The chatbot detects whether the customer is writing in English or Arabic and responds in the same language. If the customer switches languages during the conversation, the chatbot automatically continues in the new language.

## Repository Structure

```text
task2-whatsapp-phase1/
│
├── workflow.json
├── messages.md
│
└── assets/
    ├── flow-diagram.png
    ├── flow-diagram.mmd
    └── webhook-test-screenshot.png
```

## Security Note

This repository does **not** contain the Meta Access Token or Verify Token.

To run this workflow:

1. Create your own Meta Developer App.
2. Configure WhatsApp Cloud API.
3. Add your own credentials inside n8n.
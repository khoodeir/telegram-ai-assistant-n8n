# 🤖 Telegram AI Assistant with n8n

An AI-powered Telegram assistant built using n8n and Google Gemini.

This workflow can understand different message types from Telegram and generate intelligent responses.

---

## ✨ Features

- 💬 Text conversations
- 🖼️ Image analysis using Google Gemini Vision
- 🎤 Voice transcription
- 🧠 AI-powered responses
- 🔀 Automatic routing using Switch node
- 📩 Telegram integration
- ⚡ Low-code workflow with n8n

---

## Workflow

![Workflow](images/workflow.png)

---

## Tech Stack

- n8n
- Google Gemini
- Telegram Bot API
- AI Vision
- Speech-to-Text

---

## Workflow Overview

Telegram Trigger

↓

Switch

├── Text

├── Image → Analyze Image

└── Voice → Transcribe Audio

↓

AI Processing

↓

Telegram Reply

---

## Requirements

- n8n
- Telegram Bot Token
- Google Gemini API Key

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/telegram-ai-assistant-n8n.git
```

2. Open n8n

3. Import

```
workflow/telegram-ai-assistant.json
```

4. Add your credentials

- Telegram
- Google Gemini

5. Activate the workflow

---

## Environment Variables

```
TELEGRAM_BOT_TOKEN=

GEMINI_API_KEY=
```

---

## Screenshot

Add a screenshot of your workflow inside

```
images/workflow.png
```

---

## Future Improvements

- WhatsApp Integration
- Memory Support
- RAG with PDF
- Multi-language Responses
- OCR
- Document Analysis
- Function Calling

---

## Author

Ahmed Khodeir

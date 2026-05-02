# 🤖 I.R.I.S: Agentic AI Voice Assistant
HuggingFace : https://huggingface.co/spaces/alexntssa/IRIS/tree/main

<img width="1380" height="660" alt="586520806-f8ab91bb-4747-4cf9-8a33-229f88734952" src="https://github.com/user-attachments/assets/7cc82675-59bb-4a86-a210-84773485e0fa" />

---

# 🤖 I.R.I.S: Agentic AI Voice Assistant

**I.R.I.S** is an autonomous **Agentic AI** designed to revolutionize parent-child communication. By leveraging state-of-the-art **Large Language Models (LLMs)** and **Voice Synthesis**, I.R.I.S acts as a personalized bridge between family members, delivering affectionate, context-aware responses and automated **Voice Notes (VN)** via WhatsApp.

## 🚀 Technical Core & Toolstack

This project utilizes a high-performance stack to ensure low-latency response generation and reliable delivery:

*   **LLM Engine**: **Gemini 1.5 Flash** for ultra-fast, "manja" (affectionate) personality mapping and intent recognition.
*   **Backend Framework**: **FastAPI** for an asynchronous, high-concurrency **Webhook** architecture.
*   **Communication Gateway**: **Whapi.cloud API** to interface with WhatsApp for sending **Voice Notes (VN)** and text.
*   **Voice Synthesis**: **Google Text-to-Speech (TTS)** API for converting AI text into high-fidelity Indonesian audio.
*   **Deployment**: Hosted on **Hugging Face Spaces** for 24/7 autonomous operation.
*   **Automation**: **Asyncio-based Scheduler** for routine "check-in" messages and autonomous engagement.

## 🛠️ Key Features

*   **Agentic Autonomy**: Not just a chatbot—I.R.I.S proactively initiates conversations based on time-blocks (Morning/Afternoon/Evening).
*   **Voice-First Interface**: Converts text responses into **WhatsApp Voice Notes** automatically for a more personal touch.
*   **Contextual Memory**: Built with specific "Soul" instructions to maintain a consistent persona (Jakarta-slang, affectionate, and caring).
*   **Smart Scheduling**: Intelligent message throttling (37 messages/block) to maintain natural engagement patterns.

## 📂 Project Structure
```bash
├── app.py              # Main FastAPI application & Agent logic
├── requirements.txt    # Project dependencies (FastAPI, Google-GenAI, etc.)
└── README.md           # Project documentation

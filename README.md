# IRIS-mychild

graph LR
    subgraph "WhatsApp Interface"
        A[fa:fa-whatsapp User: Ayah/Bunda] -- "Ketik 'iris' / Chat Rutin" --> B
    end

    subgraph "Cloud Backend (Hugging Face)"
        B[fa:fa-server FastAPI Webhook] --> C{fa:fa-brain AI Logic}
        C -- "Context Processing" --> D[fa:fa-robot Gemini 1.5 Flash]
        D -- "Text Response" --> E[fa:fa-comment-dots Text-to-Speech]
        E -- "Generate Audio" --> F[fa:fa-microphone Google TTS API]
    end

    subgraph "Gateway & Delivery"
        F --> G[fa:fa-bolt Whapi.cloud API]
        G -- "Send Voice Note" --> H[fa:fa-volume-up WhatsApp VN]
    end

    H --> A

graph TD
    %% Nodes
    User[fa:fa-user User Ayah/Bunda]
    WhatsApp[fa:fa-whatsapp WhatsApp App]
    HF[fa:fa-server Hugging Face Space]
    Gemini[fa:fa-brain Google Gemini AI]
    TTS[fa:fa-microphone Google TTS]
    Whapi[fa:fa-bolt Whapi.cloud Gateway]

    %% Alur Kerja
    User -- "Kirim chat 'iris'" --> WhatsApp
    WhatsApp -- "Webhook Trigger" --> HF
    HF -- "Generate Respon Manja" --> Gemini
    Gemini -- "Text to Audio" --> TTS
    TTS -- "Audio Stream" --> Whapi
    Whapi -- "Kirim Voice Note" --> WhatsApp
    WhatsApp -- "Diterima Bunda" --> User

    %% Styling
    style User fill:#f9f,stroke:#333,stroke-width:2px
    style Gemini fill:#4285F4,stroke:#fff,color:#fff
    style HF fill:#FFD21E,stroke:#333
    style WhatsApp fill:#25D366,stroke:#fff,color:#fff

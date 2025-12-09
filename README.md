accessibility-voice-assistant/
├─ backend/
│  ├─ package.json
│  ├─ index.js
│  ├─ supabase.js
│  ├─ logger.js
│  ├─ routes/
│  │  ├─ stt.js
│  │  ├─ tts.js
│  │  ├─ vision.js
│  │  └─ chat.js
│  └─ uploads/          (folder for temporary uploads - .gitignore)
├─ frontend/
│  ├─ package.json
│  ├─ index.html
│  └─ src/
│     ├─ main.jsx
│     ├─ App.jsx
│     ├─ components/
│     │  ├─ SpeakButton.jsx
│     │  ├─ ReadAloud.jsx
│     │  ├─ UploadImage.jsx
│     │  ├─ ChatArea.jsx
│     │  └─ Monitoring.jsx
├─ docs/
│  ├─ db_schema.sql
│  ├─ architecture_diagram_placeholder.png
│  └─ API_TRADEOFF.md
├─ DEMO_GUIDE.md
├─ README.md   (use the README you already accepted — I’ll include a short README here too)
└─ .env.example

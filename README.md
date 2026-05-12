# 🌍 Multilingual AI Voice Assistant
### Powered by Google Gemini via Puter.js — 100% FREE

No API key. No credit card. No signup. Just open `index.html` and talk.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🌐 Any language | Auto-detects and responds in your language |
| 🎙️ Voice input | Click mic, speak in any language |
| 🤖 Gemini models | 2.5 Flash, 2.5 Pro, 2.0 Flash, 3 Flash |
| 💡 4 Modes | Casual · Learning · Travel · Professional |
| 😊 Emotion detection | Detects happy/sad/angry/stressed/neutral |
| 💬 Context memory | Remembers conversation across turns |
| 📝 Translation insight | Shows English interpretation of your message |
| 🌙 Dark mode | Auto-follows your OS preference |
| 💸 Cost | Completely FREE via Puter.js |

---

## 🚀 Quick Start — No Setup Needed!

1. **Unzip** the project folder
2. **Open** `index.html` in Chrome or Edge
3. **Start talking!**

That's it. No config files, no API keys, no servers.

> **Why does it work for free?**
> [Puter.js](https://puter.com) is a free cloud platform that provides access to AI models including Google Gemini at no cost to users. It handles authentication and billing transparently.

---

## 🎙️ Voice Input

- Click the microphone button to start recording
- Speak in **any language** — it auto-detects
- Click again or wait for silence to stop
- Your speech is automatically sent to Gemini
- **Best browser:** Chrome or Edge (Firefox has limited Web Speech API support)

---

## 🌐 Supported Languages (examples)

Tamil · Hindi · Arabic · Japanese · Chinese (Simplified/Traditional) · Korean · French · Spanish · Portuguese · German · Italian · Russian · Turkish · Dutch · Polish · Vietnamese · Thai · and many more.

---

## 🤖 Available Gemini Models

| Model | Best for |
|---|---|
| `gemini-2.5-flash` | Fast, smart, great for most tasks (recommended) |
| `gemini-2.5-pro` | Strongest reasoning, more detailed responses |
| `gemini-2.0-flash` | Reliable, fast, multimodal |
| `gemini-3-flash-preview` | Latest generation, experimental |

---

## 📁 Project Structure

```
multilingual-voice-assistant/
├── index.html        ← Open this in your browser
├── css/
│   └── style.css     ← All styles (light + dark mode)
├── js/
│   └── app.js        ← Core logic + Puter.js integration
└── README.md         ← This file
```

---

## 🔧 Modes Explained

- **Casual** — Friendly, conversational, relaxed responses
- **Learning** — Teaches vocabulary, grammar, explains translations
- **Travel** — Short practical responses, useful phrases, directions
- **Professional** — Formal, precise, business-appropriate language

---

## 🛠️ How It Works

```
User types/speaks  →  Puter.js  →  Google Gemini API (free)
     ↑                                      ↓
Response in         ←  JSON parsed   ←  Multilingual AI response
user's language                           with emotion + translation
```

1. User inputs text or voice in any language
2. App sends a structured prompt to Gemini via Puter.js
3. Gemini detects language, translates, generates response, translates back
4. App parses the JSON and displays the response with metadata

---

## 🌍 Running Locally vs Online

| Method | Works? | Notes |
|---|---|---|
| Double-click `index.html` | ✅ Yes | Direct file open works |
| `python3 -m http.server 8080` | ✅ Yes | Local server |
| `npx serve .` | ✅ Yes | Node.js server |
| VS Code Live Server | ✅ Yes | Extension needed |
| Upload to GitHub Pages | ✅ Yes | Free hosting |
| Upload to Netlify/Vercel | ✅ Yes | Free hosting |

---

## ⚠️ Troubleshooting

**"Puter.js failed to load"** → Check your internet connection (Puter.js loads from a CDN)

**Model unavailable error** → Switch to a different model using the model selector buttons

**Microphone not working** → Allow microphone access in browser settings; use Chrome or Edge

**Response not in my language** → Rephrase your message; Gemini occasionally responds in English for very short inputs

---

## 📜 License

MIT — free for personal and commercial use.

---

## 🙏 Credits

- **Google Gemini** — AI language models
- **[Puter.js](https://puter.com)** — Free AI API access layer
- **Web Speech API** — Browser-native voice recognition

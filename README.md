# Oi – Voice-Powered AI Chatbot 🤖🎙️

Oi is an intelligent, voice-based chatbot that enables **real-time conversations** using **Speech-to-Text (STT)**, **GPT-4 text generation**, and **Text-to-Speech (TTS)** — all packed into a sleek web interface.

Built to explore the future of voice-based AI interaction. Just speak, and Oi listens, thinks, and talks back!

---

## 🧠 Features

- 🎤 **Voice Input** via Speech Recognition (Whisper or Web Speech API)
- 💬 **AI-Powered Responses** using GPT-4 (via OpenAI API)
- 🔊 **Voice Output** using Text-to-Speech (browser or ElevenLabs)
- 🌐 **WebSocket Communication** for real-time streaming
- 🎨 **Custom Frontend** with animated waveform, chat bubbles, and optional 3D avatar
- ⚡ Low-latency experience with seamless speech-to-speech flow

---

## 🛠️ Tech Stack

| Frontend        | Backend           | AI / APIs        |
|-----------------|-------------------|------------------|
| HTML, CSS, JS   | Python, FastAPI    | OpenAI GPT-4     |
| WebSockets      | Uvicorn (ASGI)     | Whisper STT      |
| Web Audio API   | Socket.IO (JS/Py)  | TTS (Browser API / ElevenLabs) |

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/Shivu2727/oi-voice-chatbot.git
cd oi-voice-chatbot
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` isn’t available yet, install manually:

```bash
pip install fastapi uvicorn openai websockets
```

### 3. Run the Backend

```bash
uvicorn controller:app --reload
```

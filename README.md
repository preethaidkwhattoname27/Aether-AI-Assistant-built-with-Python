# ✨ Aether — AI Assistant

Aether is a futuristic AI assistant built with Python and Streamlit. It combines conversational AI, web search, and voice interaction in one application.

## 🚀 Features

- 🤖 **Local AI Chat:** Qwen 2.5 3B running through Ollama.
- 🌐 **Web Search:** Tavily Search API for retrieving online information.
- 🔗 **Source Links:** View relevant sources for search-based answers.
- 🎙️ **Voice Input:** Speech-to-text using faster-whisper.
- 🔊 **Voice Output:** Text-to-speech using gTTS.
- 💬 **Conversation History:** Retains messages during the active session.
- 🎨 **Futuristic Interface:** Interactive chat interface built with Streamlit.

## 🛠️ Technology Stack

- Python
- Streamlit
- Ollama
- Qwen 2.5 3B
- Tavily Search API
- faster-whisper
- gTTS

## ⚙️ Installation and Setup

### 1. Install the requirements

Install Python and Ollama on your computer.

### 2. Download the AI model

```bash
ollama pull qwen2.5:3b
```

Make sure Ollama is running.

### 3. Install Python dependencies

Install the packages listed in `requirements.txt` after it is added to this repository.

### 4. Configure the API key

Create a local `.env` file and add your Tavily API key:

```text
TAVILY_API_KEY=your_tavily_api_key_here
```

Never upload your actual API key to GitHub.

### 5. Run Aether

```bash
streamlit run app.py
```

## 🔮 Future Improvements

- Persistent conversation storage
- Improved source-grounded answers
- Additional language support
- Further AI and robotics integrations

## 📌 Project Status

Educational AI assistant prototype under development.

## 👩‍💻 About

A hands-on project exploring AI engineering, Python application development, web search, and speech technologies.

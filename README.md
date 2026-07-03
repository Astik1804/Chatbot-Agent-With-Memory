# 🤖 Chatbot Agent with Memory

An intelligent conversational AI chatbot built with **LangChain**, **OpenAI GPT**, and **Conversation Memory** that remembers previous interactions to provide context-aware, personalized responses throughout a conversation.

## 🚀 Overview

Traditional chatbots treat every user message independently, often losing context between interactions. This project solves that problem by implementing conversational memory, enabling the chatbot to remember previous messages and generate more natural, coherent, and human-like conversations.

The chatbot leverages LangChain's memory components and OpenAI's language models to maintain conversation history and improve response quality.

---

## ✨ Features

- 🧠 Context-aware conversations using conversation memory
- 💬 Multi-turn dialogue support
- ⚡ Fast response generation with OpenAI GPT models
- 🔄 Automatic conversation history management
- 📝 Natural language understanding
- 🎯 Personalized responses based on previous interactions
- 🔧 Modular and extensible architecture
- 📦 Simple setup and deployment

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| LLM | OpenAI GPT |
| Framework | LangChain |
| Memory | ConversationBufferMemory |
| Environment | Python Virtual Environment |
| Package Manager | pip |

---

## 📂 Project Structure

```
Chatbot-Agent-With-Memory/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
└── assets/
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Astik1804/Chatbot-Agent-With-Memory.git
```

```bash
cd Chatbot-Agent-With-Memory
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file and add your OpenAI API key.

```env
OPENAI_API_KEY=your_api_key_here
```

### Run the application

```bash
python app.py
```

---

## 💡 How It Works

1. User sends a message.
2. Conversation history is stored using LangChain Memory.
3. Previous messages are injected into the prompt.
4. OpenAI GPT generates a context-aware response.
5. Memory updates after every interaction.
6. The chatbot continues the conversation while remembering previous exchanges.

---

## 🧠 Memory Flow

```
User Message
      │
      ▼
Conversation Memory
      │
      ▼
Prompt Construction
      │
      ▼
OpenAI GPT
      │
      ▼
AI Response
      │
      ▼
Update Memory
```

---

## 📸 Demo

Example Conversation

```
👤 User:
Hi, my name is Astik.

🤖 Bot:
Hello Astik! Nice to meet you.

------------------------

👤 User:
What's my name?

🤖 Bot:
Your name is Astik.
```

---

## 🎯 Future Improvements

- Long-term memory with vector databases
- Retrieval-Augmented Generation (RAG)
- PDF document chat
- Voice-enabled chatbot
- Multi-user conversation support
- Chat history persistence
- Streamlit web interface
- Docker deployment

---

## 📈 Learning Outcomes

This project demonstrates practical experience with:

- LangChain
- Prompt Engineering
- LLM Integration
- OpenAI API
- Conversational AI
- Context Management
- AI Agent Development
- Memory-based Chatbots

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Astik Kushwaha**

- GitHub: https://github.com/Astik1804
- LinkedIn: https://www.linkedin.com/in/astikkushwaha

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!

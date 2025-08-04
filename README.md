# 🧠 Multi-Usecase AI ChatBot using LangGraph & Streamlit

Welcome to the **AI ChatBot** – a modular, extensible chatbot framework built using **LangGraph**, **LangChain**, and **Streamlit**. This project supports multiple use cases like:

- 🗣️ Basic Chat


> Designed with modularity and real-time streaming in mind, this project demonstrates how to combine powerful agentic workflows with a beautiful and responsive front end.

---

## 🚀 Features

### ✅ Multi-Usecase Support
- **Basic Chatbot**: Simple chat powered by LLMs.


### 🔁 Real-time Streaming
Thanks to `graph.stream()` and `st.write_stream`, all LLM responses are streamed live to the UI for a smooth and interactive experience.

### 🧱 Built on Modern Stack
- **LangGraph**: Graph-based execution for agent workflows.
- **LangChain**: LLM orchestration.
- **Streamlit**: Beautiful front-end with `st.chat_message` UI blocks.
- **OpenAI/Groq**: Model provider support (easily extensible).

---

## 🛠️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/aijulhussain/ChatBot.git

python -m venv venv
On Windows: venv\Scripts\activate
Create a .env file and add your keys (Groq):
streamlit run frontend/app.py


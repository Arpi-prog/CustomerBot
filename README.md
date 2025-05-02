# 🤖 AI Customer Support Assistant

A smart, multimodal customer support assistant built with **Gradio**, **LangGraph**, **LangChain**, **Groq LLM**, **OCR**, and **Voice Input**. This assistant can understand queries via text, voice, or file upload (PDF/image), classify them, detect sentiment, and route the query to the right support path.

---

## 🔍 Features

- 🎤 **Voice Input** via Google SpeechRecognition API  
- 📎 **File Upload** support (PDF, PNG, JPG, JPEG) with OCR extraction  
- 💬 **LLM-Powered Routing** using LangGraph (sentiment + category-based)  
- 📊 **Feedback Collection** per query  
- 📥 **CSV Export** of query and feedback history  
- 🌐 **Beautiful UI** with custom CSS and Gradio Blocks

---

## 🛠️ Tech Stack

| Component        | Technology             |
|------------------|------------------------|
| Frontend         | Gradio (with custom CSS) |
| LLM              | Groq Llama 3-70B via LangChain |
| Workflow Routing | LangGraph (StateGraph) |
| OCR              | Tesseract + PyMuPDF    |
| Voice Input      | SpeechRecognition      |
| File Handling    | PDF/Image              |
| Output Export    | CSV                    |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/customer-support-bot.git
cd customer-support-bot

step2- pip install gradio langchain langgraph langchain-groq pytesseract PyMuPDF SpeechRecognition

3. Set up Groq API key

python

groq_api_key="your_groq_api_key"

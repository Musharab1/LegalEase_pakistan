# ⚖️ LegalEase Pakistan  

A **GenAI-powered legal assistant** designed to simplify **Pakistani law** for everyday citizens.  
Built with **Google Gemini LLM**, **RAG (DuckDuckGo Search)**, and **Streamlit**, it provides **easy-to-understand explanations** of legal rights, processes, and regulations in Pakistan.  

---

## ✨ Features  

- 📘 **Pakistan Law Focused** – Detects and prioritizes queries related to Pakistani law.  
- 🔍 **Real-time Knowledge Retrieval** – Uses DuckDuckGo Search with caching (RAG pipeline).  
- 🤖 **AI-Powered Responses** – Domain-specific answers via **Google Gemini**.  
- 📚 **Digest Summarization** – Combines multiple sources into one structured, professional answer.  
- 🎨 **User-Friendly Interface** – Clean and interactive UI built with Streamlit.  
- ⚠️ **Disclaimer System** – Reminds users that responses are *general legal information*, not official legal advice.  

---

## 📂 Project Structure  
LegalEase-Pakistan/
│── app.py # Streamlit frontend
│── backend.py # Core chatbot logic (Gemini + RAG + domain filtering)
│── .env # API key storage
│── requirements.txt # Python dependencies
│── logs.txt # Streamlit logs


---

## 🚀 Quick Start  

### 1️⃣ Clone Repo & Install Dependencies  
```bash
git clone https://github.com/yourusername/legalease-pakistan.git
cd legalease-pakistan
pip install -r requirements.txt 

### 2️⃣ Add API Key

Create a .env file and add your Gemini API key:

Rag_API_Key=your_api_key_here

### 3️⃣ Run the App
streamlit run app.py

### 4️⃣ Access Publicly (Optional)

If running in Colab or on a local server, use LocalTunnel:

npm install -g localtunnel
npx localtunnel --port 8501


This will generate a public shareable URL.

🛠 Tech Stack

LLM: Google Gemini (google-generativeai)

Retriever: DuckDuckGo Search (duckduckgo-search)

Framework: Streamlit (Frontend UI)

Deployment: LocalTunnel (for Colab / local sharing)

💡 Example Usage

User:
What is the process for khula in Pakistan?

Chatbot:
📜 Legal Summary

Explains Khula under Family Law Ordinance.

Provides step-by-step court process.

Advises consulting a lawyer for official proceedings.

Adds disclaimer: 📌 This is general legal information, not a substitute for professional legal advice




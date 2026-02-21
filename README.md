##  WhizBot - RAG Based AI Chatbot

WhizBot is a Retrieval-Augmented Generation (RAG) chatbot built using Streamlit.  
It allows users to ask context-based questions about WhizBot powered by Groq LLM.

---

##  Features

-  PDF Document Upload
-  Text Chunking
-  Vector Search using FAISS
-  Context-aware responses
-  Fast LLM responses via Groq (llama-3.1-8b-instant)
-  Clean Streamlit UI with Robot Interface

---

##  Tech Stack

- Frontend/UI: Streamlit
- LLM: Groq (llama-3.1-8b-instant)
- Embeddings: Sentence Transformers (all-MiniLM-L6-v2)
- Vector Database: FAISS
- Backend Logic: LangChain

---

## 📂 Project Structure

whizbot-rag/
│
├── app.py
├── requirements.txt
├── README.md
├── src/
│ ├── loader.py
│ ├── chunker.py
│ ├── embeddings.py
│ ├── vector_db.py
│ ├── retriever.py
│ └── llm.py
│
├── data/
└── robot.png

---

##  Setup Instructions (Local)

1. Clone the repository
2. Create virtual environment
3. Activate environment
4. Install dependencies
5. Create a .env file
6. Run the app

---

##  Deployment

This project is deployed on Render as a private repository.

Environment Variable required:

---

##  Security Note

- API keys are stored as environment variables.
- .env file is not pushed to GitHub.

---



# 🇵🇰 TaxMate – Pakistani Tax Assistant Chatbot

TaxMate is a web-based AI chatbot that helps users understand
Pakistani tax-related queries such as FBR registration, NTN,
tax notices, salary tax, and general guidance.

This project uses a frontend hosted on GitHub Pages
and a secure n8n backend for AI processing.

---

## 🚀 Live Demo
https://ahmadhaseb.github.io/TaxMate/

---

## 🧠 How It Works

- Frontend (HTML/CSS/JS) collects user queries
- Queries are sent to an n8n webhook
- n8n handles:
  - AI logic (Gemini)
  - Language handling (Urdu / English)
  - RAG (Supabase vector search)
- Response is returned to frontend securely

---

## 🔐 Security & Environment Variables

- ❌ No API keys are stored in the frontend
- ✅ All API keys are securely stored in n8n credentials
- Frontend only communicates via a webhook URL
  

https://github.com/user-attachments/assets/f7aba869-e465-43a9-addc-0ea2418dd3e5



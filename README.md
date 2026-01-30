🇵🇰 TaxMate – AI-Powered Pakistani Tax Assistant
TaxMate is a sophisticated AI chatbot designed to simplify Pakistani tax laws for the general public. It provides instant, accurate, and Urdu-language guidance on FBR registration, NTN inquiries, salary tax, and official tax notices.

🚀 Live Demo
Explore TaxMate Live

🎬 Project Demo & Technical Walkthrough
Below is a detailed demonstration of how TaxMate processes queries and utilizes its knowledge base:

https://github.com/user-attachments/assets/f7aba869-e465-43a9-addc-0ea2418dd3e5

Key features shown in the demo:

Automated Tax Logic: Real-time processing via n8n webhooks.

RAG Framework: Live retrieval of data from FBR documents using Supabase Vector Store.

Multilingual Support: Seamless interaction in Urdu for better accessibility.

🧠 System Architecture
The project is built on a robust RAG (Retrieval-Augmented Generation) architecture to ensure legal accuracy:

Frontend: A clean HTML/CSS/JS interface hosted on GitHub Pages.

Orchestration: n8n serves as the backend engine, managing the flow between the user and the AI.

AI Brain: Google Gemini 1.5 Flash generates responses based on retrieved context.

Knowledge Base: Official documents like the Income Tax Ordinance 2001 and Finance Act 2024-25 are indexed in Supabase using Gemini Embeddings.

Memory: Integrated n8n Window Buffer Memory to maintain conversation context.

🔐 Security & Environment
Zero Client-Side Keys: All sensitive API keys (Gemini, Supabase) are managed securely within n8n Credentials.

Webhook Communication: The frontend interacts only with a secure n8n endpoint, preventing any direct access to the backend logic.

🛠️ Tech Stack
Automation: n8n

AI Model: Google Gemini 1.5 Flash

Vector Database: Supabase

Embeddings: Google Gemini Embeddings

Hosting: GitHub Pages

How to Deploy Locally?
Import the provided .json workflow into your n8n instance.

Configure your credentials for Google Gemini and Supabase.

Update the webhook URL in the frontend script.js file.

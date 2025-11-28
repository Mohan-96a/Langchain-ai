LangChain-AI: Modern RAG Starter Kit
<div align="center"> <img src=".github/images/logo-dark.svg" alt="LangChain Logo" width="60%"/> </div>

A refreshed, modern, developer-focused starter template built on top of LangChain, designed to help you experiment quickly with Retrieval-Augmented Generation (RAG), embeddings, and vector search workflows. This repository gives you a clean, structured, and practical foundation to prototype AI features locally or deploy them to the cloud.

🚀 What This Repo Offers

A streamlined, opinionated toolkit that helps you:

Build your own RAG chatbot in minutes.

Understand how ingestion → embeddings → vector store → retriever → LLM connect.

Experiment with FAISS locally (and swap to any vector DB easily).

Learn from minimal, readable, production-inspired code.

📦 Tech Stack

Language: Python 3.9+

Core Libraries: LangChain, FAISS, Embeddings Providers

Use Cases: RAG Chatbots, Vector Search, Local AI Prototyping

🗂 Repository Overview

Document ingestion (PDF/Text splitting + embedding)

Embeddings interface (switch providers without changing code)

FAISS vector store utilities (create, persist, load indices)

Retriever + Prompt templates

Minimal CLI chatbot for local testing

⚡ Quick Start
1. Setup Environment
python -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\activate

2. Install Dependencies
pip install -r requirements.txt

3. Build Vector Index
python scripts/ingest.py --source data/docs --index-path data/faiss.index

4. Run Chat CLI
python scripts/chat_cli.py --index-path data/faiss.index

⚙️ Configuration

Add API keys to .env

Customize embedding model in src/embeddings.py

Change vectorstore backend in src/vectorstore.py

💡 Why This Template?

Beginner friendly but powerful

Structured and modular, easy to extend

Future-proof — swap any component without rewriting code

Ideal for learning RAG & experimenting with LLMs

🧪 Development

Run tests:

pytest -q


Lint & format:

ruff check .
black .

🤝 Contributing

Open issues for bugs & feature requests

PRs welcome — keep them focused and well documented

📜 License

See the LICENSE file in the project root.

✨ Contributors & Author
<div align="center">
👑 Author & Maintainer
🔥 Mohan Chandu 

Creator • Architect • Core Developer
💼 Turning AI + LangChain concepts into clean, modern, production-ready templates.

🔗 GitHub: https://github.com/Mohan-96a

🌟 Contributors

Exceptional collaborators who helped strengthen this project.

🟩 Suman yadav Tati

🔗 GitHub: https://github.com/sumancoder-cloud

💡 Backend Enhancements • Code Optimizations • Infra Setup

🟦 Yaswanth Kumar

🔗 GitHub: https://github.com/Yaswanth676

🎨 UI/UX Improvements • Frontend Components • Workflow Enhancements

❤️ Built with passion, clean code & collaboration.

If this project helped you, consider ⭐ starring the repository!

</div>

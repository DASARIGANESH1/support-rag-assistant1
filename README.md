Support RAG Assistant
=====================

Small tool for uploading Excel and Word files and asking questions over them.

Stack
-----
- FastAPI backend
- React + Vite frontend
- Pinecone for vector storage
- OpenAI embeddings and chat models
- Docker and docker-compose

Quick start
-----------
Create a file named `.env` in the project root:

PINECONE_API_KEY=your_pinecone_key
PINECONE_ENV=your_pinecone_env
PINECONE_INDEX=support-rag-index
OPENAI_API_KEY=your_openai_key

Then run:

docker-compose up --build

Open http://localhost:3000 in the browser.

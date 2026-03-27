# Voice RAG Chatbot

A fully open-source multilingual voice chatbot with RAG document Q&A.

## Features
- Speech-to-Text: OpenAI Whisper
- LLM: Groq LLaMA 3.3 70B (free API)
- Text-to-Speech: Microsoft Edge TTS
- RAG: FAISS + Multilingual Embeddings
- Languages: Urdu, English, Arabic, French, Spanish
- OCR: Tesseract for scanned Urdu PDFs

## Run on Google Colab
1. Install dependencies from requirements.txt
2. Set GROQ_API_KEY in Colab Secrets
3. Upload app.py and run

## Deploy on HuggingFace Spaces
Upload app.py, requirements.txt, packages.txt
Add GROQ_API_KEY secret in Space Settings

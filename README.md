## Doctor-Chatbot-Using-LLM

#Project Title: Doctor Chatbot using Fine-Tuned LLM

Description:
This repository contains the code and resources for an AI-powered doctor chatbot. The project focuses on leveraging Large Language Models (LLMs) from Hugging Face, specifically through a fine-tuning process on a medical dataset. The goal is to create a chatbot that can provide accurate information and symptoms for a given disease, acting as a preliminary source of information for health-related queries.


Features:

LLM Fine-Tuning: Fine-tuning an open-source LLM (e.g., Llama 2, Falcon) on a medical conversation dataset using Hugging Face's trl and peft libraries.

Quantization: Utilizing techniques like 4-bit quantization to reduce the model size and memory footprint, making it suitable for deployment on consumer-grade hardware.

Retrieval-Augmented Generation (RAG): (Optional but highly recommended) Implementing a RAG system with a vector database (e.g., FAISS, Pinecone) to ensure the chatbot's responses are grounded in a reliable, external knowledge base of medical information, thereby reducing hallucinations.

Conversational Interface: A simple, intuitive user interface (e.g., built with Flask, Streamlit, or Chainlit) for easy interaction with the chatbot.

Tech Stack:

Python

Hugging Face Transformers

Hugging Face peft and trl libraries

PyTorch

Gradio/Streamlit

NLTK/SpaCy 

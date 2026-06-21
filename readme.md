# SymptoSense – AI Based Healthcare Chatbot

SymptoSense AI is an intelligent healthcare chatbot that helps users understand symptoms, analyze medical reports, and receive AI-powered health guidance using Retrieval-Augmented Generation (RAG) and Large Language Models.

## Features

* User Registration & Login System
* Multi-Conversation Chat Interface
* PDF Medical Report Upload
* AI-Powered Medical Report Analysis
* Retrieval-Augmented Generation (RAG)
* Llama 3.3 70B via Groq API
* Chroma Vector Database
* Automatic Chat Title Generation
* Conversation Management (Create/Delete Chats)
* Modern Healthcare-Themed User Interface
* Secure Password Storage

## Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

### Backend

* Python
* Flask
* SQLAlchemy

### AI & Machine Learning

* LangChain
* ChromaDB
* HuggingFace Embeddings
* Groq API

### Database

* SQLite

## Project Structure

```text
SymptoSense/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── upload.html
│   ├── conversations.html
│   └── chat.html
│
├── uploads/
├── reports/
├── chroma_db/
└── instance/
```

## Workflow

1. User registers and logs into the system.
2. User uploads a medical report in PDF format.
3. The system extracts and analyzes report information.
4. Medical report content is stored in the vector database.
5. The user starts a conversation with the chatbot.
6. The AI retrieves relevant report information and generates responses.
7. Conversations are saved and can be accessed later.

## Future Enhancements

* Voice-Based Interaction
* Doctor Appointment Recommendations
* Multi-Language Support
* Medical Image Analysis
* User Health Dashboard

## Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical advice, diagnosis, or treatment.

# Intelligent Enterprise Assistant

### Name : Titus Ratna Kumar Karivella 
### Register number : 212224230292


## Problem Title
Intelligent Enterprise Assistant: Enhancing Organizational Efficiency through AI-driven Chatbot Integration

---
# SCREENSHOTS 

<img width="1536" height="1024" alt="09dacc7e-d95d-4a6c-9994-3583d4efb6a2" src="https://github.com/user-attachments/assets/5fffd58f-b7d9-498a-b652-889f1b3e9000" />



# Problem Statement

Develop an AI-powered enterprise chatbot capable of answering employee queries related to:

- HR Policies
- IT Support
- Company Events
- Organizational Information

The chatbot also supports:

- Document Upload
- PDF Text Extraction
- Document Summarization
- Keyword Extraction
- Email-based 2FA Authentication
- Bad Language Filtering
- Multi-user Support

---

# Features

## AI Chatbot
- HR query support
- IT support assistance
- Organizational FAQ responses

## Document Processing
- Upload PDF documents
- Extract text from documents
- Summarize uploaded documents
- Extract keywords

## Authentication
- Email OTP verification
- Secure login system

## Safety Features
- Bad language filtering
- Secure API access

## Scalability
- Supports multiple users simultaneously
- Optimized backend response time

---

# Tech Stack

## Frontend
- React.js
- Tailwind CSS

## Backend
- FastAPI
- Python

## AI/NLP
- Hugging Face Transformers
- Sentence Transformers
- spaCy
- NLTK

## Database
- MongoDB

## Authentication
- JWT
- Email OTP

---

# System Architecture

```text
User → Frontend → Backend API → AI Engine → Database
```

Modules:
- Authentication Module
- Chatbot Engine
- Document Processing Module
- Profanity Filter
- Vector Search Engine

---

# Project Structure

```bash
Intelligent-Enterprise-Assistant/
│
├── frontend/
├── backend/
│   ├── chatbot/
│   ├── auth/
│   ├── document_processing/
│   ├── filters/
│   ├── main.py
│   └── requirements.txt
│
├── datasets/
├── docs/
└── README.md
```

---

# Installation Guide

## Clone Repository

```bash
git clone https://github.com/yourusername/SIH1706-Intelligent-Enterprise-Assistant.git
```

---

# Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend runs at:

```bash
http://127.0.0.1:8000
```

---

# Frontend Setup

```bash
cd frontend

npm install

npm start
```

Frontend runs at:

```bash
http://localhost:3000
```

---

# API Endpoints

## Chat API

```bash
POST /chat
```

## Upload PDF

```bash
POST /upload
```

## OTP Verification

```bash
POST /verify-otp
```

---

# Screenshots

## 1. Login Page

Email OTP authentication page.

```md
![Login Page](docs/screenshots/login.png)
```

---

## 2. OTP Verification

Secure OTP verification screen.

```md
![OTP Verification](docs/screenshots/otp.png)
```

---

## 3. Chat Interface

AI chatbot for HR and IT support.

```md
![Chat Interface](docs/screenshots/chat.png)
```

---

## 4. PDF Upload

Upload and analyze company documents.

```md
![Upload PDF](docs/screenshots/upload.png)
```

---

## 5. Document Summary

AI-generated summary and keyword extraction.

```md
![Document Summary](docs/screenshots/summary.png)
```

---

## 6. Bad Language Filter

Profanity detection and filtering.

```md
![Bad Language Filter](docs/screenshots/filter.png)
```

---

## 7. Swagger API Documentation

FastAPI Swagger UI documentation.

```md
![Swagger UI](docs/screenshots/swagger.png)
```

---

# Demo Video

Add your YouTube demo link here.

Example:

```bash
https://youtube.com/
```

---

# Future Enhancements

- Voice Assistant
- Multi-language Support
- AI Ticket Generation
- Mobile Application
- Analytics Dashboard

---


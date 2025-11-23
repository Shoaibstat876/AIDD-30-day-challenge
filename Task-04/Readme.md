# Study Notes Summarizer & Quiz Generator
AI-Driven Development — 30-Day Challenge  
Task 4 — Submitted by: Muhammad Shoaib  

## 📘 Overview
This project is a Study Notes Summarizer and Quiz Generator built using:

- OpenAgents SDK  
- Streamlit  
- OpenRouter API (Gemini model)  
- PyPDF for PDF text extraction  
- Gemini CLI (for theory + CLI screenshot requirement)

The app allows a student to upload a PDF, extract study text, generate a clean summary, and finally create an exam-style quiz.

---

## ✨ Features
### 1. PDF Summarizer
- Upload any PDF  
- Text extracted using PyPDF  
- Summary generated using agent instructions  
- Displayed in clean section with headings + bullets  

### 2. Quiz Generator
- Uses original PDF text  
- Generates:
  - 5 MCQs (A–D)
  - 5 Short Questions
- Strict exam-style formatting

---

## 🧠 AI Models Used
- **google/gemini-2.0-flash-001** (through OpenRouter)

---

## 📂 Project Structure
task4_study_notes_agent/
│── app.py
│── agent.py
│── pdf_utils.py
│── requirements.txt
│── README.md
│── .env (NOT included)
└── Screenshots/

---

## 🖼 Screenshots
All screenshots required by the instructor are placed in:


Screenshots/

This includes:
- App UI  
- PDF Upload  
- Summary  
- Quiz  
- Gemini CLI prompt screenshot  

---

## 🧪 How to Run
1. Create a virtual environment  
2. Install dependencies:

pip install -r requirements.txt
3. Run Streamlit

streamlit run app.py

---

## 📎 CLI Screenshot
Included inside `/Screenshots/`.

---

## ✔ Status
Project fully complete and ready for submission.




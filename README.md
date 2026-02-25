# 🎓 Real-Time AI Teaching Assistant

An AI-powered academic assistant built using Groq LLMs to support engineering education.  
This system provides syllabus-based answers, programming execution, diagram support, voice assistance, and student performance tracking.

---

## 📌 Project Overview

The Real-Time AI Teaching Assistant is designed to:

- Provide syllabus-restricted answers
- Generate and execute programming code (Python, C, C++, Java)
- Search and display diagrams
- Track student performance
- Provide voice-based explanation
- Prevent answer stacking in UI

This project simulates a mini EdTech AI platform.

---

## 🛠 Tech Stack

- **Python 3.12+**
- **Streamlit** (Web UI)
- **Groq API (LLaMA 3.1 8B Instant)**
- **Subprocess-based Code Execution**
- **MinGW (GCC Compiler for C/C++)**
- **CSV-based Student Tracking**
- **DuckDuckGo Image Search**
- **Windows PowerShell Speech Synthesizer**

---

## 🚀 Features

### 📘 Academic Interface
- Select Semester
- Enter Subject Code
- Ask Question
- View Syllabus
- Syllabus-Based Answer
- Quick Engineering Answer
- Programming Execution
- Diagram / Flowchart Search
- Voice Assistant
- Student Progress Dashboard

---

### 💻 Multi-Language Programming Execution

Supports:
- ✅ Python
- ✅ C
- ✅ C++
- ✅ Java

Features:
- Automatic language detection
- Markdown cleaning (removes ```c, ```python etc.)
- Safe subprocess execution
- Timeout protection
- Unique temporary file generation

---

### 🎯 Syllabus-Based Answering

Loads syllabus from:

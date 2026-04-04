# 🌐 Multi-Modal Language Translator

A powerful **Multi-Modal Language Translator** that enables seamless communication across languages using **text, speech, and image inputs**. This project integrates advanced NLP, OCR, and speech processing techniques into a unified desktop application with a modern GUI.

---

## 🚀 Overview

The **Multi-Modal Language Translator** is designed to break language barriers by supporting:

- 📝 Text-to-Text Translation  
- 🎤 Speech-to-Text Translation  
- 🖼️ Image-to-Text Translation  

It combines **Python-based processing** with a **C++ Qt GUI**, ensuring both performance and usability.

---

## ✨ Features

- 🌍 Multi-language translation support  
- 🔄 Multiple input modes (Text, Speech, Image)  
- 🖥️ Modern GUI built with Qt/QML  
- 🌙 Dark mode / Light mode support  
- 🧠 Offline translation using Argos Translate  
- 🗂️ Translation history (SQLite database)  
- 📂 Image upload for OCR-based translation  
- ⚡ Fast and responsive hybrid architecture  

---

## 🛠️ Tech Stack

### 🔹 Frontend
- C++
- Qt Framework (QML)

### 🔹 Backend
- Python

### 🔹 Libraries Used
- Argos Translate (offline translation)
- SpeechRecognition (speech-to-text)
- EasyOCR (image-to-text)
- OpenCV (image processing)
- SQLite3 (data storage)

👉 The system uses a hybrid architecture where **Python handles processing** and **C++ manages the GUI**.

---

## 🧠 How It Works

### 🔁 Workflow

1. User selects input mode (Text / Speech / Image)  
2. Input is captured via GUI  
3. Data is sent to Python backend  
4. Processing:  
   - Text → Argos Translate  
   - Speech → SpeechRecognition → Translate  
   - Image → OpenCV + EasyOCR → Translate  
5. Output displayed in GUI  
6. Translation stored in history  

---

## 🏗️ Architecture

This project uses a **Hybrid Architecture**:

- 🖥️ Qt/QML (Frontend)  
- ⚙️ C++ (Middleware)  
- 🧠 Python (Processing Engine)  

### Key Concepts:
- Pybind11 / IPC for Python-C++ communication  
- Monolithic structure for unified processing  
- Real-time data exchange between components  

📌 This ensures **high performance + flexibility**.

---

## ⚙️ Installation

### 1️⃣ Clone Repository
```bash
git clone https://github.com/NitinThapa30/Multimodel-Language-Translator-with-GUI.git
cd Multimodel-Language-Translator-with-GUI


# 📊 NL2SQL Chat App (iOS + FastAPI Backend)

A simple iOS app that lets users ask natural language questions and get SQL query results via a chatbot UI — with the ability to download results as Excel files.

## 🚀 Features

- Natural language to SQL conversion via FastAPI backend
- Chatbot-style interface using SwiftUI
- Query results displayed in text format
- Download result as `.xlsx` Excel file
- Works on real device and simulator

## 🧱 Technologies

- **Frontend:** SwiftUI, Swift 5
- **Backend:** Python, FastAPI, SQLAlchemy, xlsxwriter (on Render.com)
- **Networking:** `URLSession` for API and file download

## 📸 Screenshots

| Chat & SQL Result | Download Button |
|------------------|-----------------|
| ![Chat](https://github.com/user-attachments/assets/3b6d9b7d-79fb-424e-a612-f882df75458c) | ![Download](https://github.com/user-attachments/assets/fc703a58-2cc5-4bde-b29e-ac4722e6315a) |


## 🛠️ Setup Instructions


### iOS (Frontend)
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/NL2SQLChatApp.git
   cd NL2SQLChatApp//github.com/YOUR_USERNAME/NL2SQLChatApp.git
   cd NL2SQLChatApp

Backend (Optional Local Testing)
Navigate to backend directory:

bash
Copy
Edit
cd backend
Create virtual environment and install:

bash
Copy
Edit
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
Run locally:

bash
Copy
Edit
uvicorn main:app --reload
📥 Excel File Saving
Downloaded Excel files are stored in the app’s Documents directory and shared via UIActivityViewController.

📦 Deployment
Backend is hosted on:
🔗 https://nl2sql-api.onrender.com

## 🔗 Backend

This app connects to a FastAPI backend for NL2SQL processing.

- API Repository: [nl2sql-api](https://github.com/kimleak/nl2sql-api)


📄 License
MIT License

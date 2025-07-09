# 📄 AI Resume Analyzer

A modern, AI-powered resume analysis tool that compares resumes against job descriptions and generates a match score with improvement suggestions — built using Google Gemini API and Streamlit.

## 🚀 Live Demo
👉 [Click here to try the app](https://airesumeanalyser-7kebc3uwtsvan6nydk7uzt.streamlit.app)

---

## 🧠 Features
- Upload resume as PDF
- Paste job description text
- Uses Gemini API to evaluate match
- AI-generated feedback and improvement tips
- Match score with progress bar
- Downloadable analysis report

---

## 🛠️ Tech Stack
- **Frontend/UI**: Streamlit
- **AI Model**: Google Gemini API
- **PDF Parsing**: PyMuPDF
- **Deployment**: Streamlit Cloud
- **Language**: Python

---

## 📂 Project Structure
├── app.py # Main Streamlit app
├── requirements.txt # Dependencies
└── .streamlit/ (optional) # Configs if needed


---

## 📦 Installation (Run Locally)
```bash
git clone https://github.com/07-Umar/AI_Resume_Analyser.git
cd AI_Resume_Analyser
pip install -r requirements.txt


Create a .env file and add:
GOOGLE_API_KEY=your_gemini_api_key_here
PROMPT=You are an AI hiring assistant...


Then run:
streamlit run app.py


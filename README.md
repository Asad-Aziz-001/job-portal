# Flask AI Job Portal

A comprehensive job portal application built with Flask featuring AI-powered resume parsing and intelligent chatbot for recruiters.

## ✨ Features

### 👔 For Employers
- Post, edit, and manage job listings
- View all applicants with detailed profiles
- AI Chatbot for natural language queries:
  - "Show me Python developers"
  - "Who applied for Data Scientist role?"
  - "Give me resume summary of Ali"
- Update application status (pending, reviewed, shortlisted, rejected, hired)

### 👤 For Candidates
- Browse and search jobs
- Upload resume (PDF/DOCX) with auto-fill
- Track application status
- Withdraw applications
- Professional profile management

### 🤖 AI Features
- Smart resume parsing (skills, education, experience extraction)
- Natural language processing for recruiter queries
- Auto-fill application forms from resume

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Database**: SQLite/PostgreSQL with SQLAlchemy
- **Frontend**: HTML, TailwindCSS, JavaScript
- **AI/ML**: spaCy, NLTK, Custom Resume Parser
- **Authentication**: Flask-Login

## 🚀 Quick Start

1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate environment: `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Download spaCy model: `python -m spacy download en_core_web_sm`
6. Initialize database: `python init_db.py`
7. Run the app: `python app.py`
8. Visit: `http://localhost:5000`

## 📝 Demo Credentials

- **Employer**: admin@demo.com / demo123
- **Candidate**: candidate@demo.com / demo123




## 📄 License

MIT

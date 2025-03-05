# Cvue – Smart AI Resume Analyzer 🔍📄

**Cvue** is an AI-powered resume analyzer that helps users evaluate and optimize their resumes using NLP, machine learning, and interactive visualizations. Built with Streamlit for simplicity and Python for flexibility, Cvue is designed to improve resumes for Applicant Tracking Systems (ATS) and real-world job relevance.

---

## 🚀 Features

- 📄 Upload and parse PDF/Word resumes
- 🤖 AI-based resume scoring and optimization
- 💬 GPT-based resume feedback and suggestions
- 🧠 Skill extraction and keyword matching
- 📊 Visual skill gap analysis using charts
- 📝 Editable resume components
- 🔐 Local database storage using SQLite3

---

## 🛠️ Tech Stack

### 🌐 Frontend

| Technology   | Role                                                   |
|--------------|--------------------------------------------------------|
| **Streamlit** | Builds interactive and user-friendly web apps          |
| **HTML**      | Provides structural layout for content                |
| **CSS**       | Adds design and styling elements                      |
| **JavaScript**| Enables interactivity and dynamic behavior            |

### ⚙️ Backend

| Technology   | Role                                                   |
|--------------|--------------------------------------------------------|
| **Streamlit** | Powers backend logic and handles routing              |
| **Python**    | Core language for functionality and ML integration    |

### 🗄️ Database

| Technology   | Role                                                   |
|--------------|--------------------------------------------------------|
| **SQLite3**   | Stores and retrieves resume data                      |

### 📦 Key Python Modules

| Module           | Role                                                                 |
|------------------|----------------------------------------------------------------------|
| **spaCy**        | Natural Language Processing (NLP), keyword extraction, ATS checks    |
| **PyPDF2**       | Reads and extracts text from PDF resumes                            |
| **python-docx**  | Edits and parses Word resumes                                        |
| **NLTK**         | Tokenization, stemming, text preprocessing                          |
| **scikit-learn** | Drives machine learning models for scoring resumes                   |
| **Plotly**       | Builds interactive skill gap charts and data visualizations         |
| **openpyxl**     | Reads/writes Excel files for exporting analysis                     |

---

## 🧪 How It Works

1. 📂 Upload your resume (PDF or DOCX)
2. 🤖 Resume is parsed using NLP (spaCy, PyPDF2, etc.)
3. 📊 Scores are generated based on skills, experience, and layout
4. 🧠 GPT-based suggestions are provided for optimization
5. 📈 Visualizations and exportable reports are generated

---

## 📥 Installation

```bash
git clone https://github.com/your-username/Cvue.git
cd Cvue
python -m venv venv
source venv/bin/activate    # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python -m spacy download en_core_web_sm

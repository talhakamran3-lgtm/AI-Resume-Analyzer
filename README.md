# AI Resume Analyzer

An AI-powered Resume Analyzer built using Python, Streamlit, NLP, spaCy, and MySQL. The application analyzes resumes, extracts skills, predicts career domains, recommends courses, scores resumes, and provides an admin dashboard for analytics.

## Features

- Resume PDF Upload
- Resume Parsing using NLP
- Skill Extraction
- Resume Scoring
- Career Domain Prediction
- Course Recommendations
- Resume Preview
- User Data Storage in MySQL
- Admin Dashboard
- Data Visualization with Plotly

## Tech Stack

- Python
- Streamlit
- MySQL
- spaCy
- PyResParser
- Pandas
- Plotly
- NLTK
- PDFMiner

## Installation

### Clone Repository

```bash
git clone https://github.com/talhakamran3-lgtm/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download NLTK Data

```bash
python -c "import nltk; nltk.download('stopwords')"
```

### Setup MySQL Database

```sql
CREATE DATABASE cv;
USE cv;
```

Create the required tables according to the project schema.

### Run Application

```bash
streamlit run App.py
```

## Project Structure

```
AI-Resume-Analyzer/
│
├── App.py
├── Courses.py
├── requirements.txt
├── Logo/
├── Uploaded_Resumes/
└── README.md
```

## Screenshots

### User Dashboard
(Add screenshot here)

### Resume Analysis
(Add screenshot here)

### Admin Dashboard
(Add screenshot here)

## Future Improvements

- ATS Compatibility Score
- AI Resume Suggestions
- Job Recommendation System
- Resume Keyword Optimization
- Multi-language Resume Support

## Author

Talha Kamran

GitHub:
https://github.com/talhakamran3-lgtm
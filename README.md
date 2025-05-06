📄 AI-Powered Resume Ranker
Analyze resumes using NLP and rank them against job descriptions using intelligent scoring.

🚀 Overview
This project helps recruiters or job seekers evaluate how well a resume matches a specific job description. It uses Natural Language Processing (NLP) to extract key skills, compares them using TF-IDF & Cosine Similarity, and generates a match percentage, along with suggestions for improvement.

🧠 Features
🔍 Extracts and parses resumes (PDF/Text)

📑 Accepts job description input

✅ Calculates matching score between resume and JD

📈 Displays matched and missing keywords

💡 Gives improvement tips for better alignment

📁 Optionally supports multiple resume comparisons

🌐 Simple Web UI using Flask (Optional)

📦 Tech Stack
Category	Tools Used
Language	Python 3
NLP	spaCy / NLTK, Scikit-learn
PDF Processing	PyMuPDF / pdfplumber / PyPDF2
Vector Similarity	TF-IDF + Cosine Similarity
Visualization/UI	Flask + Bootstrap (optional)
Storage (opt)	SQLite / MongoDB (optional)

⚙️ How It Works
Upload Resume (PDF or .txt)

Paste Job Description

Preprocessing:

Extract text

Remove stopwords

Lemmatization (spaCy)

Vectorization:
TF-IDF is used to turn text into vectors

Comparison:
Cosine similarity gives a match %

Result:

Match Score (%)

Skills matched / missing

Recommendations


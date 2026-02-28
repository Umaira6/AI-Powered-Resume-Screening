Overview
This project implements an AI-based resume screening system that automatically evaluates and ranks candidate resumes based on their relevance to a given job description using NLP techniques.
Features
Resume text extraction and preprocessing
Keyword and similarity-based matching
Automated candidate ranking
Reduced manual screening effort
Tech Stack
Python
Pandas
Scikit-learn
NLP (TF-IDF / Text preprocessing)
NumPy
How It Works
Preprocess resume text (lowercasing, removing stopwords, cleaning text).
Convert text into numerical format using TF-IDF.
Calculate similarity score between resume and job description.
Rank resumes based on similarity score.
How to Run
Install dependencies:

pip install -r requirements.txt
Run the main script:
python main.py

Outcome
The system automates resume filtering and helps shortlist candidates efficiently based on relevance to job requirements.

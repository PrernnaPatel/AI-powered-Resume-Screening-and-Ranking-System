# AI-Powered Resume Screening and Ranking System

An AI-based system that **screens resumes and ranks them** based on how well they match a given job description. This tool helps recruiters quickly find the most suitable candidates.

---

## 🔹 Features

- Extract text from resumes (PDF/DOCX)
- Input a job description for comparison
- Compute similarity scores between resumes and job description using NLP
- Rank resumes from best match to least match
- Simple and interactive UI (Streamlit)

---

## 🔹 Technology Stack

- **Python** – Core programming language
- **NLTK / Spacy / Scikit-learn** – NLP for text processing and similarity
- **Streamlit** – Frontend UI
- **PyPDF2 / docx** – Resume text extraction
- **Cosine Similarity / TF-IDF Vectorizer** – Resume ranking algorithm

---

## 🔹 How It Works

1. Upload resumes (PDF/DOCX files)
2. Input the job description
3. The system extracts text from each resume
4. Computes similarity scores between resumes and job description
5. Displays ranked resumes with their similarity scores

---

## 🔹 Install required packages:

pip install -r requirements.txt


## 🔹 Run the Streamlit app:

streamlit run main.py

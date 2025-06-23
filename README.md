# 🧠 AI Resume Screener Project

This project uses **Python**, **Pandas**, and **NLP techniques** to automatically extract and analyze information from PDF resumes to match them with a job description (JD). It simulates how HR tech can help in **shortlisting candidates based on skills**.

## 🔧 Technologies Used
- **Python**, **Pandas**, **NumPy**
- **NLTK** (Natural Language Toolkit)
- **PyPDF2** (for PDF extraction)
- Jupyter Notebook

## 📌 Features
- Reads and parses multiple-page resumes (PDF format)
- Extracts text using `PyPDF2` and cleans it using `NLTK`
- Compares candidate skills with job description (JD)
- Calculates a **matching score** based on overlapping keywords
- Displays matched vs. missing skills

## 🔍 Matching Logic
1. Predefined `skills_list` is checked in both:
   - Resume text
   - Job description text
2. Common keywords are extracted and printed
3. Basic skill match can be extended into scoring model

## 📁 Files
- `ResumeScreener_Project-2.ipynb`: Main Jupyter notebook
- `resumesample1.pdf`: Sample resume
- `jd_sample.pdf`: Sample job description

## 🚀 Future Improvements
- Add **Streamlit UI** for uploading resumes and JDs
- Enhance NLP with **SpaCy** or **BERT**
- Resume formatting checker (contact info, layout, ATS score)
- Export shortlisted candidates to Excel or DB

## 📌 NOTE
All data is **self-generated** — no third-party datasets used. This project reflects real-world application with original resume and job data.

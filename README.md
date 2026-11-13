# 🤖 AI-Powered Study Buddy

---

## 🔍 Overview
AI-Powered Study Buddy is an intelligent learning assistant designed to help students understand academic content more effectively. The system processes study material and provides automated summaries, question-answering support, and flashcard generation.

---

## 📌 Internship Context
This project was developed as part of the **Edunet Foundation – IBM SkillsBuild Artificial Intelligence and Machine Learning Internship (6 Weeks)**.  
The project demonstrates the practical application of NLP techniques for building an AI-powered study assistant.

---

## 🧠 Features
- Text and PDF-based input processing
- Extractive text summarization using TF-IDF
- Question Answering from study material
- Automatic flashcard generation for revision
- Implemented using Python and NLP techniques

---

## ⚙️ How It Works
1. Extract text from the PDF using PyPDF2
2. Clean and split the text into sentences using NLTK
3. Score sentences with TF-IDF (scikit-learn) and pick the top ones for the summary
4. For a question, find the sentences most similar to it and return them as the answer
5. Turn key sentences into question-answer flashcards

---

## 🖼️ Sample Output

**Input:** a 2-page PDF on [topic, e.g. "Computer Networks basics"]

**Summary (TF-IDF, top 3 sentences):**
> [paste the real summary your notebook produced]

**Question:** [your question]
**Answer:** [the answer it gave]

**Flashcard:**
- Q: [question]
- A: [answer]

![Summary output](screenshots/summary.png)
![Flashcards output](screenshots/flashcards.png)

---

## 📂 Dataset
A custom Kaggle dataset was created by uploading a study-material PDF. The dataset is processed directly within the Kaggle notebook to extract text and generate learning aids.

---

## 🛠️ Technologies Used
- Python
- Kaggle Notebook
- NLTK
- Scikit-learn (TF-IDF)
- PyPDF2

---

## 🚀 How to Run
1. Open the notebook in Kaggle or Jupyter Notebook
2. Attach the dataset (PDF) to the notebook
3. Run all cells to generate outputs

---

## 📊 Results
The system successfully generates summaries, answers questions based on the content, and creates flashcards to assist in exam preparation.

---

## ⚠️ Current Limitations
- Summaries are extractive (selected sentences, not rewritten)
- Question answering is retrieval-based, so answers can be weak when the question's wording differs from the text
- Tested on a limited set of study PDFs; not yet a deployed app

---

## 🔮 Future Work
- Improve QA using sentence embeddings or a pretrained QA model
- Add a simple web interface (Streamlit or Gradio)
- Evaluate on more documents

---

📘 Kaggle Notebook
➡ View the full Kaggle notebook:
https://www.kaggle.com/code/venishreet/ai-powered-study-buddy

---

## 👩‍💻 Author
Venishree T

---

## 📜 License
This project is licensed under the Apache License 2.0.

---

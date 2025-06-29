# 💬 Task 2 – Chatbot for FAQs

Intelligent FAQ Chatbot using NLP and Cosine Similarity (Task 2 - CodeAlpha AI Internship)

This project is developed as part of my *Artificial Intelligence Internship at CodeAlpha (June–July 2025)*.  
The goal of this task is to build a chatbot that can automatically respond to frequently asked questions using Natural Language Processing techniques.

---

## 📌 Project Objective

- Build a chatbot that understands and responds to user questions  
- Collect and structure FAQ data  
- Preprocess and vectorize text using NLP techniques  
- Match user queries with the most similar FAQ using *cosine similarity*  
- Display appropriate responses based on user intent  
- Create a minimal and interactive UI for user experience

---

## 🗃 Dataset / Input
- Each entry contains:
  - *Question*
  - *Answer*

---

## 🧠 Core Functionality

- Accept user input (query)  
- Clean and preprocess text using *NLTK / SpaCy*  
- Vectorize questions using *TF-IDF*  
- Match user input to the most relevant question using *cosine similarity*  
- Display the most accurate answer  
- Optional: Implement a basic chatbot interface using Streamlit

---

## 🧪 Workflow

1. Load and preprocess FAQ dataset  
2. Vectorize questions using TF-IDF  
3. Capture user question  
4. Compute cosine similarity between input and existing FAQs  
5. Return the best matching answer  
6. Display it in a chatbot-style UI

---

## 🖥 Demo Video

🎥 [Click to Watch Demo](https://drive.google.com/file/d/1nhuU6CSu1IS0n3JiZtUV_w_WwVI0jXgj/view?usp=sharing)

---

## 🔗 LinkedIn Post

🔗 [View LinkedIn Post](https://www.linkedin.com/posts/naveena-sivaiah-91b0b6326_aiinternship-codealpha-faqchatbot-activity-7343240777180807168-_pGU?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFI9iKcBwcCFvahb-MaFocwHJSF22yC6mYE&utm_campaign=copy_link)

---

## 📁 Files in This Repository

- codealpha_task_2.py – Python code for chatbot logic  
- README.md – Project overview  

---

## 🧰 Tools & Technologies Used

- Python  
- NLTK / SpaCy  
- Scikit-learn  
- Pandas  
- Streamlit (optional UI)  
- TF-IDF Vectorizer  
- Cosine Similarity

---

## 🚀 How to Run

1. Install dependencies:
   pip install pandas nltk scikit-learn streamlit

2. Run the app:
   streamlit run codealpha_task_2.py


---

## 📌 Tags

#CodeAlpha #AIInternship #Chatbot #FAQBot #NLP #TFIDF #CosineSimilarity #PythonProject #InternshipTasks #IntelligentSystems #StreamlitApp

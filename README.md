### 🎓 EduGuide Sri Lanka – University Guidance Chatbot (Semantic Search + NLP)

This repository contains the intelligent university recommendation system that powers the **University Guidance Chatbot** in the EduGuide Sri Lanka project. It uses **semantic search** and **sentence embeddings** to match student skills and Z-score profiles with relevant degree programs in both government and private universities.

#### 📌 Features:
- 🔍 **Semantic Search** using **Sentence-BERT** for understanding free-text skill inputs  
- 🎯 Matches students with relevant **career paths**, **private degrees**, and **government universities**
- 🧠 Utilizes **Z-score filtering**, district, and stream to enhance government recommendations 
- 🔁 Includes fallback logic for unmatched inputs and low-similarity queries
- 🗃️ Preloaded with:
  - **Career-to-skill dataset**
  - **Private university dataset**
  - **Government university dataset with cutoff marks**

#### 📂 Contents:
- `University Guidance Chatbot.ipynb` – Core script with semantic search logic
- `university_recommender.pkl` – Saved model and pre-encoded embeddings
- `career_dataset.csv`, `private_unis.csv`, `government_unis.xlsx` – Cleaned datasets used in the system

#### 🧠 Objective:
To guide Sri Lankan students in discovering degree programs that align with their skills and performance, by providing **personalized**, **AI-powered** recommendations.

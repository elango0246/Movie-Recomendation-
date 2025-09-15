# 🎬 Movie Recommendation System using Machine Learning

## 📌 Project Overview
This project recommends movies to users based on similarity of movie features such as title, genres, cast, crew, and description.  
It was developed as part of the **Unified Mentor Internship (Machine Learning Intern)**.

The system uses **Natural Language Processing (NLP)** and **Cosine Similarity** to find movies that are most similar to a given movie.

---

## 🚀 Tech Stack
- Python  
- NumPy, Pandas  
- Scikit-learn (CountVectorizer, Cosine Similarity)  
- NLTK (text preprocessing)  
- Jupyter Notebook / Google Colab  

---

## 📊 Methodology
1. **Data Collection** → Movies dataset (TMDB 5000 Movies or MovieLens dataset).  
2. **Data Preprocessing** → Cleaning text, combining features (overview, cast, genres).  
3. **Feature Extraction** → Bag of Words / TF-IDF vectorization.  
4. **Similarity Calculation** → Cosine Similarity between movie vectors.  
5. **Recommendation Function** → Suggests Top 5 movies similar to the input movie.  

---

## 📈 Results
Example Input: **Avatar (2009)**  
Recommended Movies:  
- Guardians of the Galaxy  
- Star Trek  
- John Carter  
- Star Wars: The Force Awakens  
- The Fifth Element  

---

## 📂 Repository Structure

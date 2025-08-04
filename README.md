
# 🎬 Movie Recommender System

This is a content-based movie recommender system built using the TMDB 5000 Movie Dataset.  
It recommends movies based on metadata such as overview, genres, keywords, cast, and crew.

----

## 📁 Dataset
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`
> Dataset Source: [Kaggle - TMDB Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## 🔧 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- CountVectorizer
- Cosine Similarity

---

## 📊 Features
- Clean and merge movie & credits data
- Extract key features (overview, genres, cast, crew, keywords)
- Build tags from text data
- Recommend 10 similar movies using cosine similarity

---

## ▶️ How to Run

### Google Colab (Recommended)
Run the project directly in your browser using Colab:  
[Open in Colab](https://colab.research.google.com/)

### Local Setup
```bash
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender
pip install -r requirements.txt
python main.py
```

---

## 📌 Example

**Input:** `Avatar`  
**Output Recommendations:**
1. Guardians of the Galaxy
2. Star Wars: The Force Awakens  
...

---

## 📬 Feedback
Easy to moderate. Helped me understand how recommendation systems work and how to clean & combine movie metadata using NLP techniques.

---

## 📎 Links
- 🔗 [Kaggle Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- ▶️ [Google Colab](https://colab.research.google.com/drive/1bB3cb3PtmGDOHqUXtY7hXv1URi1HEZtr#scrollTo=8ty9H83G8QQu)

---

## 📌 Tags
`#Python` `#MachineLearning` `#RecommendationSystem` `#OutrixJourney` `#InternshipProject`

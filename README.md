# 🎬 Movie Recommendation System using Machine Learning

> A personalized movie recommendation system built using Python and Jupyter Notebook. The system suggests movies based on content similarity (like genres, overview, cast, keywords, etc.). The project is implemented using a real-world dataset and uses **Natural Language Processing (NLP)** techniques and **cosine similarity** for accurate recommendations.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Features](#features)
- [Recommendation Logic](#recommendation-logic)
- [Installation & Running](#installation--running)
- [Author](#author)
- [License](#license)
- [Recruiter Note](#recruiter-note)

---

## 📝 Overview

- Suggests movies similar to a user's input
- Uses movie metadata (genres, cast, overview, keywords)
- Content-based recommendation using text similarity
- Clean and modular implementation using Python in Jupyter Notebook

---

## 🧑‍💻 Tech Stack

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- NLTK (optional for text preprocessing)
- Cosine Similarity (Sklearn)

---

## 🎥 Dataset

- Source: [Kaggle TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Fields Used:
  - `title`
  - `genres`
  - `overview`
  - `cast`
  - `crew`
  - `keywords`

---

## ✅ Features

- Takes movie name as input and recommends top 5–10 similar movies
- Text feature extraction using:
  - TF-IDF or CountVectorizer
  - Combined metadata (`genres`, `overview`, etc.)
- Cosine similarity to find closeness between movies
- Clean output with movie titles and poster links (optional)

---

## 🧠 Recommendation Logic

1. Load and clean movie metadata
2. Combine relevant textual features
3. Vectorize using CountVectorizer or TF-IDF
4. Compute pairwise cosine similarity matrix
5. Input a movie name and fetch its closest matches
6. Return top N recommended movie titles

---

## ⚙️ Installation & Running

### 🔹 Clone the repo
``bash
git clone https://github.com/Ajayrawat17/movie-recommendation-system.git
cd movie-recommendation-system
🔹 Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
🔹 Run the notebook
bash
Copy
Edit
jupyter notebook


👨‍💻 Author
Ajay Rawat
🎓 B.Tech CSE – Graphic Era Hill University
📧 ajayrawat11146@gmail.com
🔗 GitHub: Ajayrawat17

📄 License
Licensed under the MIT License

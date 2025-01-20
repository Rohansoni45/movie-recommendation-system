# Movie Recommender System 🎥

A **content-based movie recommendation system** built using **Python**, **Pandas**, **NumPy**, and **Scikit-learn**. This project recommends 5 similar movies based on the input movie title, leveraging the **cosine similarity** metric for calculating content similarity. 

The system uses the **TMDb dataset** for movie information and metadata.

---

## Features ✨
- Input the name of a movie, and the system suggests **5 similar movies**.
- Utilizes **cosine similarity** for content-based recommendations.
- Processes movie metadata to find similarities based on attributes like genres, keywords, and more.

---

## Dataset 📊
The project uses the [**TMDb (The Movie Database)**](https://www.themoviedb.org/) dataset, which contains detailed movie metadata such as:
- Movie titles
- Genres
- Keywords
- Overview
- Cast and crew

---

## Technologies Used 🛠️
- **Programming Language**: Python
- **Libraries**:
  - **Pandas**: For data manipulation and cleaning
  - **NumPy**: For numerical computations
  - **Scikit-learn**: For implementing cosine similarity
- **Streamlit**: For deploying the system as a web application (optional).

---

## How It Works 🧠
1. **Data Preprocessing**:
   - Metadata columns like `genres`, `keywords`, and `cast` are cleaned and processed.
   - A new column is created to combine important attributes into a single "bag of words."

2. **Similarity Calculation**:
   - The "bag of words" is transformed into a vector space using CountVectorizer or TfidfVectorizer.
   - **Cosine similarity** is computed between all movie vectors.

3. **Recommendation**:
   - Given an input movie title, the system fetches the 5 most similar movies based on cosine similarity.

---
## Live Demo
You can try out the Movie Recommendation System by visiting the live link below:

[Live Demo](https://movie-recommendation-sy.onrender.com)

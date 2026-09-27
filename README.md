 Movie Recommender System

A content-based movie recommendation web application built with **Python**, **Pandas**, **Scikit-Learn**, and **Streamlit**. This app suggests similar movies based on user selection and fetches real-time movie posters using the TMDB API.

---

#Features

- **Interactive UI**: Clean and user-friendly interface built with Streamlit.
- **Content-Based Filtering**: Recommends the top 5 most similar movies based on metadata (genres, cast, crew, overview, keywords).
- **Poster Integration**: Dynamically fetches and displays movie posters using The Movie Database (TMDB) API.

---

## 🛠️ Tech Stack

- **Python** (Programming Language)
- **Streamlit** (Frontend Web Framework)
- **Pandas & NumPy** (Data Processing)
- **Scikit-Learn** (Cosine Similarity & Machine Learning)
- **Requests** (API Handling)

---

## 📂 Project Structure

```text
Movie Recommender/
│
├── app.py                  # Main Streamlit web application
├── movie-recomender.ipynb  # Jupyter Notebook used for data preprocessing and model building
├── movies.pkl              # Serialized pandas DataFrame containing movie details
└── README.md               # Project documentation

# 🎬 Movie Recommendation System (AI/ML Project)

## 📌 Project Overview

This project is a **Movie Recommendation System** built using Machine
Learning techniques.\
It recommends movies similar to the one selected by the user. The system
is built using:

-   Python
-   Pandas
-   Scikit-learn
-   Streamlit (for web interface)

The recommendation logic is based on a **content-based filtering
approach** using a precomputed similarity matrix.

------------------------------------------------------------------------

## 🚀 Features

-   Interactive web app built with Streamlit
-   Recommends Top 5 similar movies
-   Fast recommendations using precomputed cosine similarity
-   Clean and simple user interface
-   Jupyter Notebook included for model building process

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python 3.x
-   Pandas
-   NumPy
-   Scikit-learn
-   Streamlit
-   Pickle

------------------------------------------------------------------------

## 📂 Project Structure

    ├── app.py                              # Streamlit application
    ├── movie recommendation system.ipynb   # Model building notebook
    ├── movies.pkl                          # Movie data
    ├── similarity.pkl                      # Similarity matrix
    ├── requirements.txt                    # Dependencies
    └── README.md                           # Project documentation

------------------------------------------------------------------------

## ⚙️ How It Works

1.  Load movie dataset.
2.  Perform text preprocessing and feature extraction.
3.  Convert text data into vectors (e.g., TF-IDF).
4.  Compute cosine similarity between movie vectors.
5.  Store the similarity matrix using pickle.
6.  When a user selects a movie, the system:
    -   Finds its index
    -   Retrieves similarity scores
    -   Sorts movies by similarity
    -   Displays Top 5 recommendations

------------------------------------------------------------------------

## 💻 Installation & Setup

### 1️⃣ Clone the Repository

    git clone <your-repo-link>
    cd <your-repo-folder>

### 2️⃣ Install Dependencies

    pip install -r requirements.txt

If requirements.txt is not available:

    pip install streamlit pandas numpy scikit-learn

### 3️⃣ Run the App

    streamlit run app.py

The app will open in your browser at:

    http://localhost:8501

------------------------------------------------------------------------

## 📊 Model Type

This project uses **Content-Based Filtering** with **Cosine
Similarity**.

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Add collaborative filtering
-   Deploy on Streamlit Cloud / Heroku
-   Add movie posters using TMDB API
-   Improve UI/UX
-   Add user ratings feature

------------------------------------------------------------------------

## 📜 License

This project is open-source and available under the MIT License.

------------------------------------------------------------------------

## 👩‍💻 Author

Rashmita Mohapatra\
B.Tech CSE (AI/ML Enthusiast)

------------------------------------------------------------------------

⭐ If you like this project, don't forget to star the repository!

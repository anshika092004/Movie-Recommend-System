🎬 Movie Recommendation System — README
📌 Project Overview

The Movie Recommendation System is an intelligent web application built using Python, Machine Learning, and Streamlit.
It recommends similar movies based on features such as overview, genres, keywords, cast, and production companies.
The system uses content-based filtering, vectorization, and similarity scores to generate accurate movie suggestions.

🚀 Features

- 🎥 Recommend movies similar to a selected movie
- 📝 View complete movie details including cast, budget, release date, etc.
- 🖼 Display movie posters using TMDB API
- 🎭 Explore cast biographies
- 🔎 Search & browse through all available movies
- 💾 Uses preprocessed similarity matrices for faster recommendations

🧠 Tech Stack

- Python
- Streamlit (for UI)
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Requests API (TMDB poster & cast data)

📁 Project Structure
📦 Movie-Recommendation-System
├── main.py
├── Processing/
│   ├── preprocess.py
│   ├── display.py
├── Files/
│   ├── tmdb_5000_movies.csv
│   ├── tmdb_5000_credits.csv
│   ├── similarity_overview.pkl
│   ├── similarity_genres.pkl
│   ├── similarity_keywords.pkl
│   ├── similarity_tcast.pkl
│   ├── similarity_tprduction_comp.pkl
│   ├── new_df_dict.pkl
│   ├── movies_dict.pkl
│   ├── movies2_dict.pkl
├── requirements.txt
└── README.md

▶️ How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/repo-name.git
cd repo-name

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit App
streamlit run main.py


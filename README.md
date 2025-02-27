# Movie Recommendation System

## 📌 Overview
This project is a **content-based movie recommendation system** that suggests similar movies based on their genres, keywords, cast, and crew. It uses **TF-IDF Vectorization** and **Cosine Similarity** to find the most relevant movies based on textual data.The app is built using Streamlit for the user interface and fetches movie posters using the TMDB API.
## 📂 Dataset
The dataset used is from **[TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)** on Kaggle, which includes:
- `tmdb_5000_movies.csv`: Contains movie details like title, overview, genres, keywords, etc.
- `tmdb_5000_credits.csv`: Contains cast and crew details.


These are not available on GitHub due to the large file size.You can get it by clicking on above link.

## 🚀 Features
- Extracts relevant movie metadata (genres, keywords, top 3 actors, and director).
- Preprocesses data by converting text into lowercase and removing unnecessary details.
- Converts movie tags into **numerical vectors** using **TF-IDF**.
- Computes **Cosine Similarity** to find movies with similar tags.
- Returns the **top 10 similar movies** based on a given movie title.
- Saves the precomputed similarity matrix using **Pickle** for faster recommendations.

## 🛠️ Technologies Used
- **Python**
- **Pandas** (Data handling)
- **NumPy** (Numerical operations)
- **Scikit-learn** (TF-IDF Vectorization, Cosine Similarity)
- **Pickle** (Saving model for reuse)
  
##  Contributing:
   Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## 📜 License
This project is licensed under the MIT License.

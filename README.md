# Movie-recommender-system-tmdb-dataset
## 🎬 Movie Recommender System (TMDB Dataset)

A **content-based movie recommendation system** built using the **TMDB 5000 Movies dataset**.
This project recommends similar movies based on features such as **genres, cast, crew, keywords, and overview**, using **NLP vectorization** and **cosine similarity**.

### 📚 Overview

* Reads and processes data from `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`.
* Cleans and merges datasets for analysis.
* Extracts key features (cast, crew, genres, keywords, overview).
* Converts text data into numerical form using **CountVectorizer**.
* Calculates similarity scores using **cosine similarity**.
* Returns top 5 similar movies for any input title.

### 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* TMDB Dataset

### ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook
   ```

   and open `movie_recommender_system.ipynb`.

### 🧩 Example

Input:

```python
recommend('Avatar')
```

Output:

```
['Guardians of the Galaxy', 'Aliens', 'Star Trek', 'Star Wars: The Force Awakens', 'John Carter']
```

### 📊 Dataset

Dataset: [TMDB 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Would you like me to make this README sound **more beginner-friendly** or **more academic/research-style** (so it impresses professors)?


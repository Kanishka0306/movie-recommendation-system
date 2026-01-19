# movie-recommendation-system

🎬 Movie Recommendation System

This project is a content-based movie recommendation system built using Machine Learning and Natural Language Processing (NLP).
It suggests movies similar to a user’s chosen movie by analyzing movie details such as genre, plot overview, cast, keywords, and director.

The goal of this project is to understand how recommendation systems work using real-world data and similarity-based techniques.


🚀 Features
	•	Recommends the top 5 most similar movies for a given movie
	•	Uses content-based filtering, so no user ratings are required
	•	Supports partial movie name search (for example: “batman”, “avengers”)
	•	Built using a real and widely used movie dataset


🧠 Approach

The project follows these main steps:
	1.	Clean and preprocess the movie dataset
	2.	Combine important movie metadata into a single feature
	3.	Convert text data into numerical form using CountVectorizer
	4.	Calculate similarity between movies using Cosine Similarity
	5.	Recommend movies based on similarity scores


📊 Dataset
	•	TMDB 5000 Movie Dataset
	•	Source: Kaggle
	•	Files used:
	•	tmdb_5000_movies.csv
	•	tmdb_5000_credits.csv

This dataset provides detailed information about movies, including genres, cast, crew, and plot summaries.


🛠 Tech Stack
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Google Colab


⚙️ How It Works
	•	Movie information is transformed into numerical vectors
	•	Cosine similarity is used to measure how similar two movies are
	•	Movies with the highest similarity scores are recommended to the user


▶️ How to Run
	1.	Open the notebook in Google Colab or Jupyter Notebook
	2.	Upload the TMDB dataset CSV files
	3.	Run all cells in order
	4.	Call the recommendation function, for example:

recommend("Batman")


📈 Example Output

Input:

recommend("Batman")

Output:

Batman Begins
The Dark Knight
Batman Returns
The Dark Knight Rises
Batman & Robin


⚠️ Limitations
	•	The system does not use user ratings or preferences
	•	Recommendations are based only on movie content
	•	New or uncommon movies may not get accurate recommendations


🔮 Future Improvements
	•	Add a web interface using Streamlit
	•	Display movie posters using the TMDB API
	•	Extend the system with collaborative filtering
	•	Improve text processing using TF-IDF or embeddings


👩‍💻 Author

Kanishka

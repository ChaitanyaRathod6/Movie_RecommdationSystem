🎬 Movie Recommendation System
A Movie Recommendation System that suggests similar movies based on a given input using cosine similarity.

📌 Features
✅ Enter a movie name to get personalized recommendations
✅ Uses cosine similarity to find similar movies
✅ Works in a command-line interface (CLI)
✅ Handles movie name errors gracefully

🛠️ Technologies Used
Python

Pandas (for data handling)

Pickle (to load precomputed similarity matrix)

Scikit-learn (for similarity calculations)

📂 Dataset
This project uses a movie dataset containing:

Movie Name

Rating

Votes

Meta Score

PG Rating

Year

Duration

Cast & Director

Genre Categories

🚀 Installation & Setup
1️⃣ Install Dependencies
bash
Copy
Edit
pip install pandas scikit-learn
2️⃣ Run the Python Script
bash
Copy
Edit
python movie_recommendation.py
3️⃣ How It Works
The script will ask you to enter a movie name

It will find similar movies using cosine similarity

The recommended movies will be displayed in the terminal

📂 Project Structure
sql
Copy
Edit
📁 Movie-Recommendation-System
│-- movie_recommendation.py  # Main Python Script
│-- cosine_sim.pkl           # Precomputed similarity matrix
│-- movies.csv               # Movie dataset
📌 Future Enhancements
🔹 Add movie posters using an API
🔹 Improve recommendation algorithm with hybrid filtering
🔹 Include user ratings and reviews

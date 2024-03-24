<!DOCTYPE html>
<body>
  <h1>Movie Recommendation System using Cosine Similarity</h1>

  <p>This repository contains a movie recommendation system implemented using cosine similarity. The system suggests similar movies based on textual features such as genres, keywords, cast, and crew.</p>

  <h2>Overview</h2>

  <p>The movie recommendation system utilizes cosine similarity to recommend movies similar to a given movie title. It involves several key steps including data preprocessing, feature engineering, text processing, vectorization, and cosine similarity calculation.</p>

  <h2>Key Steps</h2>

  <ol>
    <li><strong>Data Preparation:</strong> Load and merge movie datasets ('tmdb_5000_movies.csv' and 'tmdb_5000_credits.csv') to form a comprehensive dataset.</li>
    <li><strong>Feature Engineering:</strong> Extract features such as genres, keywords, cast, and crew from the raw data and process them into a suitable format for analysis.</li>
    <li><strong>Text Processing:</strong> Process textual data including movie overviews, genres, keywords, cast, and director names using stemming and tokenization techniques.</li>
    <li><strong>Vectorization:</strong> Vectorize the processed textual data using the CountVectorizer from scikit-learn to convert textual features into numerical vectors.</li>
    <li><strong>Cosine Similarity Calculation:</strong> Compute cosine similarity between vectors representing different movies to measure their similarity.</li>
    <li><strong>Recommendation Function:</strong> Develop a recommendation function ('recc_movie') to provide movie recommendations based on a given movie title.</li>
  </ol>

  <h2>Usage</h2>

  <p>To use the recommendation system, follow these steps:</p>

  <ol>
    <li>Clone the repository:</li>
  </ol>

  <code>git clone https://github.com/shivam-singh-git/movie-recommendation-system.git</code>

  <ol start="2">
    <li>Install the required dependencies:</li>
  </ol>

  <code>pip install -r requirements.txt</code>

  <ol start="3">
    <li>Run the <code>recommend.py</code> script and pass the desired movie title as an argument:</li>
  </ol>

  <code>python recommend.py "Batman"</code>

  <p>This will recommend similar movies to the movie "Batman".</p>

  <h2>Conclusion</h2>

  <p>The movie recommendation system demonstrates the effectiveness of cosine similarity in providing accurate and relevant movie recommendations based on textual features. It showcases the potential for real-world applications in the entertainment industry.</p>
</body>
</html>

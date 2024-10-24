# Movie Ranking Project
This project ranks the top N movies based on IMDb and Rotten Tomatoes scores using Python.


# Features
IMDb and Rotten Tomatoes Scores: Merges data from IMDb and Rotten Tomatoes to rank movies.
Top N Movies: Generate rankings for the top 10, 20, 30, 50, or 100 movies.
Data Preprocessing: Cleans and preprocesses data to ensure consistency before merging datasets.
Normalization: Scales IMDb scores to match the Rotten Tomatoes 100-point scale.
Visualizations: Optionally provides visualizations (charts) of top-ranked movies.
CSV Export: Exports the ranked list of top movies to a CSV file for easy sharing or further analysis.


# Installation:

Follow these steps to install and run the project:

Clone the repository:
git clone https://github.com/YourUsername/YourProject.git
cd YourProject

Install required libraries:
pip install -r requirements.txt
Ensure the datasets are in the appropriate folder (IMDB-Movie-Data.csv and rotten_tomatoes_movies.csv).

Usage
Once everything is set up, follow these steps to run the project:

Run the main Python script:
python movie_ranking.py
Modify the number of top movies (N = 10, 20, 30, etc.) inside the script or pass as an argument if implemented.

View the output in the terminal or check the CSV file generated in the output folder.

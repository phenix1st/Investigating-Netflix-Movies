#Investigating Netflix Movies

This project is part of the DataCamp Data Scientist track, where I explored and analyzed a dataset of Netflix movies to uncover insights about movie durations, release years, and genres.

📌 Project Overview

The goal of this project was to practice data analysis with Python by:

Cleaning and exploring a dataset of Netflix movies.

Visualizing trends in movie durations over time.

Identifying popular genres and specific movie patterns.

Applying filtering, grouping, and aggregation techniques.

🛠️ Tools & Libraries

The project was implemented in Python using:

Pandas → for data manipulation and filtering.

Matplotlib → for data visualization.

Jupyter Notebook → for interactive analysis.

📊 Key Steps

Loading the dataset of Netflix movies.

Exploring basic statistics (release years, durations, genres).

Filtering movies based on specific criteria (e.g., duration < 90 mins, Action genre, release year).

Finding the most frequent durations using .mode().

Visualizing duration trends with histograms and line plots.

📈 Insights Gained

Most Netflix movies tend to be around a certain duration (found via .mode()).

The distribution of movie lengths shows that shorter movies (<90 mins) are relatively common.

Certain genres (e.g., Action, Dramas) dominate in specific time ranges.

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/netflix-movies-investigation.git
cd netflix-movies-investigation


Install dependencies:

pip install pandas matplotlib jupyter


Open the notebook:

jupyter notebook

📂 Repository Structure
├── netflix_investigation.ipynb   # Jupyter notebook with full analysis
├── data/                         # Dataset used in the project
├── README.md                     # Project description

🎯 Learning Outcome

This project strengthened my ability to:

Work with real-world datasets in Pandas.

Create clear and insightful visualizations.

Ask meaningful data-driven questions and answer them with analysis.

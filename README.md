# MICHAEL-TALUKDER

Netflix Content Popularity Analysis
Challenge 1: What Makes Content Popular on Netflix?

Business Question:
What characteristics are most common among popular Netflix titles?

Project Overview
This project analyzes a synthetic Netflix-style dataset to identify the characteristics that drive content popularity. We explore patterns across genre, release year, ratings, and viewing behavior to generate actionable business insights.

Team:

Partner A (Data Cleaning, EDA, Insights)
Partner B (Visualizations, Documentation, Reporting)
Dataset
We use three related CSV files:

File	Description	Rows
netflix_movies_100.csv	100 famous movies (1990–2019) with genre and release year	100
users.csv	User profiles	80
watch_history.csv	User viewing history + ratings	~1,176
Key Columns
Movies

movie_id, title, genre, release_year
Users

user_id, name
Watch History

history_id, user_id, movie_id, rating (1–5)
Project Structure
├── data/
│   ├── netflix_movies_100.csv
│   ├── users.csv
│   └── watch_history.csv
├── notebooks/
│   └── netflix_popularity_analysis.ipynb
├── images/                  # saved visualizations
├── README.md
└── project_plan.md
Analysis Goals
Load & Inspect the three datasets
Clean missing values and ensure data quality
Explore relationships between genre, release year, rating, and number of watches
Visualize at least 3 meaningful charts
Derive at least 3 business insights about what makes content popular
Conclude with recommendations
Key Questions We Aim to Answer
Which genres receive the highest average ratings and most watches?
Do older or newer titles tend to be more popular?
Is there a relationship between number of watches and average rating?
What characteristics appear most frequently among the top-watched titles?
Tech Stack
Python 3
pandas, numpy
matplotlib / seaborn / plotly
Jupyter Notebook
How to Run
# Clone the repository
git clone <your-repo-url>
cd netflix-popularity-analysis

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch notebook
jupyter notebook notebooks/netflix_popularity_analysis.ipynb
Sprint Goal
Deliver a complete, well-documented analysis that identifies the key characteristics of popular Netflix content and presents clear business insights through visualizations and a final report by the end of the sprint.

Project Risks & Mitigations
Risk	Impact	Mitigation
Data quality issues or missing values affect conclusions	High	Perform thorough data cleaning and validation in the first days of the sprint
Uneven workload or delayed collaboration between partners	Medium	Use the Kanban board daily, hold short check-ins, and clearly assign ownership of tasks
Deliverables Checklist

Dataset prepared (movies, users, history)

Jupyter Notebook with full analysis

At least 3 visualizations

At least 3 business insights

Final conclusions section

README and project documentation

GitHub repository with version control

(Optional) Exported PDF/HTML of notebook
Authors
[Michael Njuki Gichobi]
[Gulam Rabbi Talukder]
Course: Netflix Data Analysis Project
Challenge Selected: Challenge 1 – What Makes Content Popular on Netflix?

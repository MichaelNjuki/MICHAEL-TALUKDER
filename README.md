Github Accounts:
https://github.com/MichaelNjuki/MICHAEL-TALUKDER
                     &
https://github.com/G-R-Talukder/MICHAEL-TALUKDER

## Netflix Content Popularity Analysis

**Challenge 1: What Makes Content Popular on Netflix?**

**Business Question:**  
What characteristics are most common among popular Netflix titles?

---

## Project Overview

This project analyzes a synthetic Netflix-style dataset to identify the characteristics that drive content popularity. We explore patterns across genre, release year, ratings, and viewing behavior to generate actionable business insights.

**Team:**  
- Michael (Data loading, cleaning, EDA, insights)  
- Talukder (Visualizations, documentation, conclusions)

---

## Dataset

| File | Description | Rows |
|------|-------------|------|
| `data/netflix_movies_100.csv` | 100 famous movies (1990–2019) with genre and release year | 100 |
| `data/users.csv` | User profiles | 80 |
| `data/watch_history.csv` | User viewing history + ratings | 1,176 |

---

## Project Structure
── ProjectPlan/
── data/

│   ├── netflix_movies_100.csv

│   ├── users.csv

│   └── watch_history.csv

├── notebooks/

│   └── netflix_popularity_analysis.ipynb

├── KANBAN.md

├── README.md


---

## Sprint Goal

Deliver a complete Netflix content popularity analysis that identifies key characteristics of popular titles and presents clear business insights through visualizations and a final report.

---

## Project Risks

1. **Poor data quality may affect the accuracy of conclusions.**  
   Mitigation: Perform data validation and cleaning early.

2. **Delays in team collaboration may impact deadlines.**  
   Mitigation: Conduct short daily check-ins and track progress on the Kanban board.

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/MichaelNjuki/MICHAEL-TALUKDER.git
cd MICHAEL-TALUKDER

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Open the notebook
jupyter notebook notebooks/netflix_popularity_analysis.ipynb

Retrospective:

What went well?
Clear task division between data analysis and visualizations
Effective use of branches
Regular commits and successful merge into main

What could be improved?
Saving files before committing to avoid sync issues
Better coordination when pulling changes between branches

What should the team continue doing?
Using feature branches
Committing after each major step
Running the full notebook before merging

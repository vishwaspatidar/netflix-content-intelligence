# Netflix Content Analysis

A data analysis project exploring Netflix's content library to understand how the platform has evolved over the years. Using Python and exploratory data analysis (EDA), this project uncovers trends in content types, release patterns, genres, production countries, ratings, and movie durations to provide insights into Netflix's content strategy. The analysis is based on the Netflix Movies and TV Shows dataset containing over 8,800 titles. :contentReference[oaicite:0]{index=0}

---

## Problem Statement

Netflix hosts one of the world's largest streaming content libraries, but understanding the composition of that catalog is essential for identifying content trends and strategic opportunities. This project analyzes the Netflix dataset to answer questions such as:

- How has Netflix's content library grown over time?
- What type of content dominates the platform?
- Which countries contribute the most titles?
- What genres are most popular?
- How are content ratings and movie durations distributed?

---

## Dataset

- **Dataset:** Netflix Movies and TV Shows Dataset
- **Records:** 8,807 titles
- **Features:** 12 columns including content type, release year, country, director, cast, genre, rating, duration, and description. :contentReference[oaicite:1]{index=1}

---

## Approach

The analysis was carried out using Exploratory Data Analysis (EDA) techniques.

The workflow included:

- Exploring dataset structure and data quality
- Identifying missing values across different attributes
- Analyzing the distribution of Movies and TV Shows
- Studying content release trends over the years
- Identifying the top content-producing countries
- Exploring genre distribution across the catalog
- Analyzing audience ratings
- Finding the most frequent directors and actors
- Understanding movie duration patterns
- Examining monthly content addition trends through visualizations :contentReference[oaicite:2]{index=2}

---

## Key Insights

- Movies account for the majority of Netflix's content library, significantly outnumbering TV Shows.
- Netflix experienced rapid content growth during the late 2010s, reflecting its aggressive global expansion.
- The United States contributes the largest share of titles, followed by India and the United Kingdom.
- International Movies, Dramas, and Comedies dominate the platform's catalog.
- TV-MA is the most common maturity rating, indicating a strong focus on mature audiences.
- Most movies have durations concentrated around 90–120 minutes.
- Content additions fluctuate throughout the year, showing seasonal publishing patterns. :contentReference[oaicite:3]{index=3}

---

## Business Recommendations

- Continue investing in international content, particularly in regions with consistently high content production.
- Expand high-performing genres such as International Movies and Dramas to support global audience engagement.
- Incorporate seasonal trends into content release planning to maximize user engagement.
- Use historical catalog trends to improve content acquisition and production strategies.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Repository Structure

```text
netflix-content-analysis/
├── README.md
├── requirements.txt
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── analysis.ipynb
└── results/
    └── findings_summary.txt
```

---

## Getting Started

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook located in the `notebooks` folder and run all cells.

---

## About This Project

This project was completed as part of my Data Analytics learning journey to strengthen my skills in exploratory data analysis, data visualization, and communicating insights through data. It focuses on understanding real-world streaming platform data and translating observations into meaningful business insights.
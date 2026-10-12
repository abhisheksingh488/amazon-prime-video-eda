# Amazon Prime Video — Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Amazon Prime Video titles to understand the platform's content catalogue, including movies and TV shows, genres, release years, runtime, ratings, and people involved in production.

The goal is to explore patterns in the available data and translate them into findings that can help stakeholders better understand content distribution and trends.

## Business Problem

Streaming platforms need to understand their content libraries to make informed content and audience-engagement decisions. This analysis explores questions such as:

- How is the catalogue distributed between movies and TV shows?
- Which genres appear most frequently?
- How has content release activity changed over time?
- What patterns appear in IMDb ratings and popularity metrics?
- Which actors and directors are associated with titles in the catalogue?

## Dataset

The project uses two related datasets:

### 1. `titles.csv`
Contains title-level information, such as:

- `id` — unique title identifier
- `title` — title name
- `show_type` — movie or TV show
- `description` — title description
- `release_year` — release year
- `age_certification` — age classification
- `runtime` — movie duration or show episode runtime
- `genres` — associated genres
- `production_countries` — production country information
- `seasons` — number of seasons, where applicable
- `imdb_id`, `imdb_score`, `imdb_votes` — IMDb identifiers and metrics
- `tmdb_popularity`, `tmdb_score` — TMDB popularity and score metrics

### 2. `credits.csv`
Contains people associated with titles, including:

- `person_id` — person identifier
- `id` — related title identifier
- `name` — actor or director name
- `character_name` — character name, where applicable
- `role` — role such as actor or director

**Dataset source:** Amazon Prime Video titles and credits dataset.

## Dataset Download Links

- **Titles Dataset:** [Download titles.csv.zip](https://drive.google.com/file/d/1TSUrzzr3TUJraNSO2ShFUDMAKxeZiHJm/view?usp=sharing)
- **Credits Dataset:** [Download credits.csv.zip](https://drive.google.com/file/d/1urca2tAGuVcxtOhPurCKEmiHqbZclULl/view?usp=sharing)

## Tools & Technologies

- **Python** — analysis
- **Pandas** — data loading, cleaning, manipulation, and aggregation
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Google Colab / Jupyter Notebook** — development environment

## Analysis Workflow

1. Load the titles and credits datasets.
2. Inspect dataset dimensions, column names, data types, and sample records.
3. Identify missing values, duplicate records, and data-quality issues.
4. Clean and prepare fields needed for analysis.
5. Perform univariate, bivariate, and multivariate exploration.
6. Create visualizations to examine catalogue composition, genres, release-year trends, runtime, ratings, and popularity.
7. Summarize findings and discuss their possible business relevance.

## Key Areas Explored

- **Catalogue overview:** Movies versus TV shows
- **Genre analysis:** Distribution of titles across genres
- **Release trends:** Catalogue patterns across release years
- **Ratings analysis:** IMDb and TMDB score patterns
- **Runtime analysis:** Duration patterns across titles
- **Credits analysis:** Actors and directors associated with titles

> The exact findings and numerical values should be taken from the completed notebook and verified before publication.

## How to Run

1. Clone or download this repository.
2. Open `amazon_prime_video_eda.ipynb` in Jupyter Notebook or upload it to Google Colab.
3. Download the dataset files from the official/course-provided source.
4. Update the notebook's file paths to match where the datasets are stored.
5. Run the notebook cells from top to bottom.

## Repository Structure

```text
amazon-prime-video-eda/
├── amazon_prime_video_eda.ipynb
├── README.md
└── data/                 # Optional; add only if dataset redistribution is permitted
    ├── titles.csv
    └── credits.csv
```

## Conclusion

This EDA project explores the Amazon Prime Video catalogue and its associated title and credits information. It demonstrates a structured approach to inspecting, cleaning, analysing, and visualizing data using Python libraries. The notebook's verified findings can help describe content patterns and inform further analysis.

## Future Improvements

- Add a concise, verified summary of the strongest findings.
- Compare catalogue patterns across additional dimensions.
- Extend the analysis with a dashboard or deeper statistical analysis if required.
- Improve reproducibility by documenting dataset versions and file paths.

## Author

**Abhishek Singh**

- GitHub: [abhisheksingh488](https://github.com/abhisheksingh488)

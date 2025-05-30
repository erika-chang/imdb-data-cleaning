# 🎬 Movies Dataset Cleaning and Analysis

---

## 📌 Objective

Practice key data cleaning steps using `pandas`, including:

- Handling missing values (`NaN`)
- Identifying and removing duplicates
- Converting column types
- Making the dataset ready for analysis

---

## 📁 Dataset

[The Movies Dataset from Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) - The Movies Dataset contains over 45,000 movies with various attributes like title, genres, release year, revenue, vote count, and more.

This dataset consists of the following files:

**movies_metadata.csv**: The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.

**keywords.csv**: Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.

**credits.csv**: Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.

**links.csv**: The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.

**links_small.csv**: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.

**ratings_small.csv**: The subset of 100,000 ratings from 700 users on 9,000 movies.

---

## 🔧 Tasks Performed

- Loaded the dataset and explored columns with missing values

- Removed or imputed missing data in revenue and vote_count columns

- Converted release_date to datetime format

- Removed duplicate movie entries

- Converted numeric columns to appropriate types for analysis

- Generated basic exploratory summaries and visualizations, such as revenue distributions

---
## 📝 Project Structure
```
imdb-data-cleaning/
│
├── data/
│   └── imdb_raw.csv              
│
├── notebooks/
│   └── imdb_cleaning.ipynb       
|
├── README.md                     
├── requirements.txt              
└── .gitignore                    
```

---

## 🧠 What I learned

- Small cleaning decisions have a big impact on downstream analysis
- `isnull()`, `fillna()`, and `dropna()` are essential in daily work
- Careful type conversion improves plotting and time-based analysis

---

## ✍️ Author
[Erika](https://www.linkedin.com/in/ecdazevedo)

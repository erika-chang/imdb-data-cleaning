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

---

## 🔧 Tasks Performed

- Removed rows with missing `Revenue` and `Metascore`
- Filled missing revenue values with the mean
- Converted `Year` to datetime format
- Removed duplicate rows
- Basic exploratory summary and distribution plot of movie revenues

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

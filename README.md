# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset, uncovering trends in genres, popularity, ratings, and release history using Python and Plotly.

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset Overview

The dataset contains **9,826 rows** and **9 columns** with information about movies available on Netflix:

| Column | Description |
|---|---|
| `Release_Date` | Release date of the movie |
| `Title` | Movie title |
| `Overview` | Short plot description |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average user rating (0–10) |
| `Original_Language` | Language the movie was originally made in |
| `Genre` | Genre(s) of the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Performed

The notebook covers the following steps:

1. **Data Loading** — Loading the CSV into a Pandas DataFrame
2. **Data Preview** — Examining the first few rows and column structure
3. **Statistical Summary** — Descriptive statistics for numerical columns
4. **Data Quality Check** — Identifying duplicates and missing values
5. **Data Cleaning** — Removing duplicates and null rows
6. **Data Preprocessing** — Extracting release year, expanding multi-genre entries
7. **Visualizations** (using Plotly):
   - Most common movie genres
   - Top 10 most popular movies
   - Movie releases over time
   - Average popularity by genre
   - Distribution of popularity scores

---

## 📈 Key Insights

- **Drama** is the most common genre in the dataset.
- **Adventure** movies have the highest average popularity score.
- **Action** and **Science Fiction** also show strong audience engagement.
- Movie releases increased significantly after **2000**, reflecting the growth of the film industry.
- Popularity scores are **highly right-skewed** — most movies are average, with very few blockbusters.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data manipulation
- **Plotly Express** — interactive visualizations
- **Jupyter Notebook** — development environment (Google Colab compatible)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** If using Google Colab, update the file path in the data loading cell from `/content/NetflixData.csv` to the appropriate path after uploading the dataset.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

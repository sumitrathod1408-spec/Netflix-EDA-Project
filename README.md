# 🎬 Netflix Exploratory Data Analysis (EDA)

<div align="center">

### Exploring Netflix's Global Content Library Using Python

**Python • Pandas • NumPy • Matplotlib • Seaborn • Jupyter Notebook**

</div>

---

## 📖 Project Overview

Netflix is one of the world's leading streaming platforms, offering thousands of Movies and TV Shows across multiple countries and genres. Understanding content trends can help identify audience preferences, production strategies, and opportunities for future investment.

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **Netflix Titles Dataset** using Python. The analysis includes data cleaning, feature engineering, visualization, and business-driven insights to uncover meaningful patterns in Netflix's content library.

---

## 🎯 Project Objectives

- Understand the structure and quality of the Netflix dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Engineer useful features for analysis.
- Explore trends in Movies and TV Shows.
- Analyze content distribution across countries and genres.
- Study release year and upload trends.
- Generate actionable business insights through visualization.

---

## 📂 Dataset Information

The dataset contains information about Netflix Movies and TV Shows, including:

- Show ID
- Content Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genres
- Description

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Cleaning & Analysis |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

## 📁 Project Structure

```text
Netflix-EDA-Project/
│
├── dataset/
│   └── netflix_titles.csv
│
├── notebook/
│   └── Netflix Exploratory Data Analysis (EDA).ipynb
│
├── images/
│   ├── movies_vs_tvshows.png
│   ├── top10_countries.png
│   ├── top10_genres.png
│   ├── content_rating.png
│   ├── movie_growth.png
│   ├── tvshow_growth.png
│   ├── monthly_uploads.png
│   ├── movie_duration.png
│   ├── avg_duration_country.png
│   ├── country_rating.png
│   └── top_directors.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed before analysis:

- Checked dataset shape and structure
- Examined data types
- Identified missing values
- Removed duplicate records
- Converted `date_added` to datetime format
- Created additional date-based features
- Converted movie duration into numeric format
- Split multiple values in Country, Director, and Genre columns using `explode()`

---

# 📊 Exploratory Data Analysis

The project includes the following analyses:

### Dataset Exploration

- Dataset Shape
- Data Types
- Missing Values
- Duplicate Records
- Summary Statistics

### Univariate Analysis

- Movies vs TV Shows
- Content Ratings
- Movie Duration Distribution
- Top Countries
- Top Genres
- Top Directors

### Bivariate Analysis

- Country vs Rating
- Movies vs TV Shows by Country
- Average Duration by Country
- Average Movie Duration by Release Year

---

# 📈 Business Questions Answered

✔ Which countries should Netflix invest in?

✔ Which genre has the highest demand?

✔ Is movie production increasing over the years?

✔ Is TV Show production increasing?

✔ Which years experienced maximum content growth?

✔ Which content rating is most common?

✔ Which month has the highest number of uploads?

✔ Which country produces the most family-friendly content?

✔ What is the average movie duration by country?

✔ Which directors contributed the highest total runtime?

---

# 📊 Key Visualizations

The notebook contains visualizations for:

- Movies vs TV Shows
- Top 10 Countries Producing Netflix Content
- Top 10 Genres
- Top Directors
- Content Ratings
- Monthly Upload Trends
- Movie Production Trend
- TV Show Production Trend
- Country vs Rating
- Movie Duration Distribution
- Average Movie Duration by Year
- Average Duration by Country

> **Screenshots of these visualizations are available in the `images/` folder.**

---

# 💡 Key Insights

- Movies account for the majority of Netflix's content library.
- The United States is the largest content-producing country, followed by India.
- TV-MA is the most common content rating, indicating a strong focus on mature audiences.
- International Movies and Dramas are among the most represented genres.
- Netflix experienced rapid content growth after 2015.
- Most movies have an average runtime between **90–120 minutes**.
- Content uploads follow seasonal trends, with certain months seeing higher additions.
- Directors with the highest cumulative runtime have contributed significantly to Netflix's movie catalog.

---

# 📌 Business Recommendations

- Continue investing in high-performing markets such as the United States and India.
- Expand original productions in emerging content markets.
- Increase investment in high-demand genres.
- Strengthen family-friendly content to attract a broader audience.
- Optimize content release schedules based on historical upload patterns.

---

# 🚀 How to Run This Project

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Netflix-EDA-Project.git
```

### Navigate to the project directory

```bash
cd Netflix-EDA-Project
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open

```
Netflix Exploratory Data Analysis (EDA).ipynb
```

---

# 📌 Future Scope

- Build an interactive Power BI Dashboard.
- Develop a Streamlit web application.
- Create a Netflix Recommendation System.
- Perform sentiment analysis on content descriptions.
- Apply Machine Learning to predict content popularity.

---

# 👨‍💻 Author

## **Sumit Rathod**

**B.Tech Computer Science Engineering**

**Aspiring Data Analyst | Data Science Enthusiast**

### Connect with Me

- **LinkedIn:** https://www.linkedin.com/in/sumit-rathod-6562792a5/

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

Thank you for visiting this repository.

</div>


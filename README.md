# Netflix – Data Exploration and Business Insights

This project involves exploratory data analysis (EDA) on Netflix's catalog of TV shows and movies to uncover actionable insights. The goal is to help Netflix executives understand what types of content to focus on and how to grow in global markets.

---

## 📊 Problem Statement

Netflix wants to identify which types of content are performing well and where it should invest more (by genre, type, country, etc.). We explore the platform's media catalog to find trends in releases, content types, top contributors, and international presence.

---

## 📁 Dataset Overview

The dataset includes:
- `show_id`, `type`, `title`, `director`, `cast`
- `country`, `date_added`, `release_year`
- `rating`, `duration`, `listed_in`, `description`

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud (optional)
- Plotly (optional for interactive plots)

---

## 📈 Project Workflow

1. **Basic Exploration**
   - Dataset shape, data types, missing values
   - Converted types (e.g., `date_added` to datetime)
2. **Univariate & Bivariate Analysis**
   - Distribution of content types (Movies vs TV Shows)
   - Top countries and genres by volume
   - Year-wise trend of releases
3. **Director/Actor Popularity**
   - Most frequent contributors per genre and type
4. **Global Strategy**
   - Availability of shows/movies across countries
   - Cross-tab analysis of `country` vs `type`
5. **Visualization**
   - Bar charts, heatmaps, time series plots
   - WordClouds (optional) for genre and cast

---

## 📌 Key Insights

- Movies dominate the platform, but TV Shows are steadily increasing.
- The U.S. has the most Netflix content, followed by India and the UK.
- Most content was added between 2015–2020, peaking in 2019.
- Dramas, comedies, and documentaries are the top 3 genres.
- December is the most common month to add new content — suggesting year-end releases.

---

## 💡 Business Recommendations

- Invest more in **TV Shows** to balance growth with competitors like Prime & Disney+.
- Expand **regional content** in emerging markets like India, Brazil, and South Korea.
- Capitalize on **genre-driven launches** (e.g., horror in October, romance in February).
- Work with **high-performing directors/actors** based on genre popularity.

---

## 📂 Files Included

- `Netflix_EDA_Visualization.ipynb` – Jupyter notebook
- `netflix_titles.csv` – Dataset
- `README.md` – This file
- Optional: Visuals, WordClouds, or HTML report

---


## 🤝 Let’s Connect

Feel free to suggest improvements or collaborate! [LinkedIn](https://www.linkedin.com/in/varshil-gandhi-08470b200/)


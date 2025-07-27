# 🎬 Netflix Movies EDA Project

An Exploratory Data Analysis (EDA) project performed on a Netflix movie dataset. The goal is to analyze the trends, ratings, genres, and popularity distribution of Netflix movies to gain meaningful insights.

---

## 📁 Dataset

The dataset `netflix.csv` includes the following key columns:

- **Title**
- **Genre**
- **Release_Date**
- **Vote_Average**
- **Original_Language**
- **Overview**
- **Poster_Url**

---

## 🔍 Objectives

- Clean and preprocess the Netflix movie dataset
- Handle missing values and duplicates
- Convert date formats and simplify the dataset
- Categorize vote scores into popularity levels
- Analyze the most frequent genres, popular movies, and content trends
- Visualize insights with Seaborn and Matplotlib

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab Notebook

---

## 🧼 Data Cleaning Steps

- Removed duplicates and irrelevant columns (`Overview`, `Original_Language`, `Poster_Url`)
- Converted `Release_Date` to year-only format
- Exploded the multi-label `Genre` column for better analysis
- Categorized `Vote_Average` into 4 classes: **Popular**, **Average**, **Below Average**, **Not Good**

---

## 📊 Key Questions Answered

1. **What is the most frequent genre?**  
   ➤ Drama is the most common genre in the dataset.

2. **Which genre has the highest vote/popularity?**  
   ➤ Drama again leads in terms of user votes, showing audience preference.

3. **What movie has the highest popularity?**  
   ➤ *Spider-Man: No Way Home* is the most popular title.

4. **What movie has the lowest popularity?**  
   ➤ *Threads* ranks the lowest in popularity.

5. **Which year has the most movies?**  
   ➤ The year with the most movie releases is **2020**.

---

## 📈 Visualizations

- 📌 Count plots of genres and popularity categories
- 📌 Bar charts showing top-rated and lowest-rated movies
- 📌 Trend line of movies released per year

---





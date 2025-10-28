# 🎬 Netflix Data Analysis using Python

## 📖 Project Overview
This project focuses on analyzing **Netflix’s movie and TV show dataset** using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.  
The goal is to uncover insights about content trends, genres, ratings, release years, and regional distributions using an Excel dataset sourced from **Kaggle**.

Through this project, I aimed to strengthen my **data analysis**, **data visualization**, and **exploratory data analysis (EDA)** skills.

---

## 🎯 Project Objective
- To explore and clean the Netflix dataset.  
- To identify trends in movies and TV shows based on **genre, release year, country, and ratings**.  
- To visualize data patterns using **Matplotlib and Seaborn**.  
- To draw meaningful conclusions about Netflix’s content strategy and audience preferences.

---

## 🧾 Dataset Information
- **Source:** [Kaggle - Netflix Movies and TV Shows Dataset](https://www.kaggle.com/)  
- **File Type:** Excel (`.xlsx`)  
- **Key Columns:**  
  - `Show_ID`  
  - `Type` (Movie / TV Show)  
  - `Title`  
  - `Director`  
  - `Cast`  
  - `Country`  
  - `Release_Date`  
  - `Rating`  
  - `Duration`  
  - `Genre` (Listed_in)  
  - `Description`

---

## 🛠️ Tools & Libraries Used
- **Python** – Programming language for analysis  
- **Pandas** – Data manipulation and cleaning  
- **Matplotlib** – Basic visualization  
- **Seaborn** – Advanced data visualization  
- **Jupyter Notebook** – Development environment  
- **Excel** – Source data format and manual verification  

---

## 🔍 Steps in Analysis

1. **Importing Libraries and Dataset**
   - Loaded the Excel dataset using `pandas.read_excel()`.
   - Checked data structure using `.info()`, `.describe()`, and `.head()`.

2. **Data Cleaning**
   - Handled **missing values** using `dropna()` and `fillna()`.
   - Converted date columns to datetime format.
   - Removed duplicate entries.

3. **Exploratory Data Analysis (EDA)**
   - Count of movies vs TV shows.
   - Most common genres and ratings.
   - Top countries with the most Netflix content.
   - Trend of content addition over the years.
   - Most frequent directors and actors.

4. **Visualization**
   - Used **Matplotlib** and **Seaborn** for visual storytelling:
     - Bar plots for type and genre distribution.
     - Countplots for ratings.
     - Heatmaps for correlation.
     - Line plots for year-wise content release trend.

---

## 📊 Key Insights
- 📈 Netflix has added **more movies** than TV shows over the years.  
- 🌍 The **United States and India** are leading content producers.  
- 🎭 The most popular genres are **Dramas**, **Comedies**, and **Documentaries**.  
- 🕒 A major rise in new content was seen after **2015**.  
- 🔞 **TV-MA** and **TV-14** are the most common maturity ratings.

---

## 📈 Visualizations Showcase
Some of the visuals included:
- **Movies vs TV Shows** – Count comparison.  
- **Top 10 Countries** producing Netflix content.  
- **Trend of Releases by Year.**  
- **Most Common Ratings.**  
- **Popular Genres.**

---

## 🧠 Learnings
From this project, I learned how to:
- Perform **data cleaning and transformation** using Pandas.  
- Create **interactive visualizations** using Matplotlib and Seaborn.  
- Extract meaningful insights from large real-world datasets.  
- Communicate findings through visuals and storytelling.

---

## 🚀 Future Improvements
- Integrate **text analysis** on descriptions using NLP for genre prediction.  
- Build a **recommendation system** based on user preferences.  
- Use **Plotly or Power BI** for more interactive dashboards.

---

## 👨‍💻 About Me
**Author:** Satyasuman Sahoo  
**Role:** Data Analyst (Student Project)  
**Skills:** Python | Pandas | Matplotlib | Seaborn | Excel | Data Visualization  
**LinkedIn:** [Satyasuman Sahoo](https://www.linkedin.com/in/satyasuman-sahoo-a79685235/)

---



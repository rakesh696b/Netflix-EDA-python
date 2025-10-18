# 📊 EDA on Netflix Dataset using Python

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to identify trends in content type, genres, release countries, and duration metrics.

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud

## 🎯 Objectives

* Understand distribution of Movies vs TV Shows
* Identify top content-producing countries
* Analyze release year trends
* Explore most common categories/genres
* Find top directors and actors
* Analyze movie durations and number of seasons

## 🧹 Data Cleaning & Preprocessing

* Converted `date_added` to datetime format
* Created `year_added` and `month_added` features
* Processed duration values for movies and TV shows
* Handled missing values in director and cast columns

## 📈 Key Insights

* Movies dominate over TV Shows on Netflix
* Most content added in 2019
* United States and India lead in content production
* International Movies and Dramas are top genres
* Jan Suter and Raúl Campos appear most frequently as directors
* Average movie duration ≈ 99 minutes
* Average TV show seasons ≈ 1.77

## ☁ Genre Word Cloud

A Word Cloud visualization highlights that International Movies, Dramas, and Comedies are the most frequent content types.

## ✅ Conclusion

Netflix’s catalog is heavily movie-focused with strong representation from the US and India. Short-format TV content is prevalent, and 2019 marked the highest spike in new titles added.

## 📎 Next Steps

* Build interactive dashboards with Plotly/Streamlit
* Perform sentiment or audience rating analysis (if ratings data available)

## 📁 Project Structure (suggested)

```
|-- netflix_eda.ipynb
|-- README.md
|-- dataset/
    |-- netflix_titles.csv
```

## 🤝 Contribution

Feel free to fork and enhance the project with more visualizations or ML-based recommendations.

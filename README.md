# 🎬 IMDb Top 700 Movies | Power BI Dashboard

## 📊 Project Overview

An interactive Power BI dashboard exploring 700 top-ranked IMDb films across ratings, genres, directors, runtime, and release decades. The dashboard enables users to explore the dataset dynamically through interactive slicers, KPIs, and Top-N visualizations.

This project demonstrates skills in **Power BI, DAX, Power Query ETL, data modeling, and interactive data visualization**.

## 🎥 Dashboard Demo

> **[Watch the Power BI Dashboard Demo on YouTube](https://youtu.be/8frPzo0UH1M)**

## 🖼️ Dashboard Preview

<img width="1291" height="726" alt="Top 700 IMDb Dashboard Thumbnail mp4" src="https://github.com/user-attachments/assets/e594ac73-d5df-4fd9-9a7d-14dbfa67a113" />


## 🎯 Project Objectives

The goal of this project was to transform a raw IMDb movie dataset into an interactive analytical dashboard that makes it easy to explore patterns among highly ranked films.

The dashboard allows users to:

* Compare IMDb ratings and other metrics across decades and genres
* Identify directors with the greatest representation among top-ranked films
* Explore the highest-ranked movies within selected categories
* Analyze genre distribution and the average number of genres per film
* Search and filter by movie title, director, genre, and decade

## ⚙️ Data Architecture & Tech Stack

* **Data Source:** [IMDb Top 700 Movies – 2026 Edition (Kaggle)](https://www.kaggle.com/datasets/saitejabandaruin/imdb-top-700-movies-2026-edition)
* **Tools:** Power BI Desktop, Power Query, DAX
* **ETL:** Cleaned and transformed multi-valued genre data using column splitting, query referencing, unpivoting, and null handling
* **Data Model:** Relational model using IMDb rank as a unique movie key and a movie-genre bridge table to support filtering across multi-valued genres
* **DAX:** Created measures for dynamic rankings, aggregations, genre counts, and filter-responsive KPIs

## 📈 Dashboard Features & Insights

* **Dynamic KPIs:** Displays metrics such as average IMDb rating, runtime, genre count, and highest-ranked film based on the current filter context
* **Top-N Analysis:** Dynamically identifies leading directors and highest-ranked movies within selected subsets of the data
* **Genre Analysis:** Restructured multi-valued genre data so films can be filtered by genre regardless of whether it was listed as the primary, secondary, or tertiary genre
* **Interactive Exploration:** Director, title, genre, and decade slicers allow users to investigate specific subsets of the IMDb rankings
* **Cross-Filtering:** Dashboard visuals respond dynamically to selections, enabling comparisons across multiple dimensions

## 🛠️ How to Run This Locally

1. Clone or download this repository.
2. Open the `.pbix` report file using **Power BI Desktop**.
3. If prompted, update the data source path to point to the dataset in the `/Data` directory.
4. Refresh the report to load the data.
5. Use the dashboard slicers to explore films by director, title, genre, and decade.

## 📁 Data Source

The original dataset is available on Kaggle:

**[IMDb Top 700 Movies – 2026 Edition](https://www.kaggle.com/datasets/saitejabandaruin/imdb-top-700-movies-2026-edition)**

Dataset credit belongs to the original Kaggle dataset creator.

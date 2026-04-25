# 🎧 Spotify Track Analysis Dashboard

![Spotify Dashboard](/Users/pratitipaul/Desktop/SpotifyAnalysis/Assets/Dashboardpic.png)

## Project Overview

This project analyzes Spotify track data to uncover the key factors that influence song popularity. The interactive Tableau dashboard provides insights into how audio features, genres, and content characteristics impact listener engagement and track performance.

The dashboard supports:

* **Popularity Analysis:** Understanding what makes a track successful
* **Genre Performance:** Identifying top-performing music genres
* **Audio Feature Insights:** Evaluating how danceability, energy, and valence affect popularity
* **Content Strategy:** Analyzing the impact of explicit content on track success
* **Trend Exploration:** Visualizing relationships between features and listener behavior

---

## Snapshot of Key Performance Indicators (KPIs)

Based on the analyzed dataset:

* **Average Popularity:** 51.4
* **Average Danceability:** 0.60
* **Average Energy:** 0.62
* **Average Duration (mins):** 3.80
* **Explicit Content %:** 13.67%

---

## Interactive Visualizations

### 1. Genre Popularity Analysis
A comparative bar chart showing average popularity across different music genres, highlighting top-performing categories like *sertanejo*, *pop*, and *k-pop*.

### 2. Danceability vs Popularity
Scatter plot analyzing how danceability influences track popularity and identifying patterns among hit songs.

### 3. Energy vs Popularity
Visualization of the relationship between song energy levels and listener engagement.

### 4. Popularity Band Distribution
Breakdown of tracks into categories (**Hit, Popular, Average, Low**) to understand distribution trends.

### 5. Explicit Content Impact
Comparison of popularity between explicit and non-explicit tracks.

---

## Technical Project Details

* **Project Name:** Spotify Track Analysis Dashboard
* **Dataset Scale:** Large-scale Spotify track dataset (multiple genres and features)
* **Tool Stack:** 
  * **Tableau:** Dashboard & Visualization
  * **Excel:** Data Cleaning & Feature Engineering
  * **Python (Pandas):** Data Verification & KPI Calculation
* **Goal:** Identify key drivers of music popularity and provide actionable insights

---

## Business Problem Statement

**What factors influence the popularity of a song on Spotify, and how can artists or producers optimize these attributes to improve performance?**

---

## Data Cleaning Process

* **Column Pruning:** Removed unnecessary and index columns to streamline the dataset.
* **Feature Engineering:** Converted duration from milliseconds to minutes for better readability.
* **Categorization:** Created **Popularity Bands (Hit, Popular, Average, Low)** based on popularity scores.
* **Feature Binning:** Categorized features like energy and danceability for distribution analysis.
* **Data Integrity:** Handled missing and inconsistent values and ensured proper formatting for Tableau integration.

---

## Analytical Techniques Used

* **Aggregation:** Average and Count calculations for core metrics.
* **Feature Engineering:** Creating derived columns for deeper insights.
* **Distribution Analysis:** Understanding how tracks are spread across popularity bands.
* **Correlation Analysis:** Visual exploration of relationships between audio features.
* **KPI Scorecards:** High-level summary of key performance indicators.
* **Interactive Filtering:** Dynamic dashboard allowing users to slice data by Genre, Popularity Band, and Explicit Content.

---

## Key Insights

* **Dance & Energy:** High popularity tracks generally exhibit **higher danceability and energy** levels.
* **Genre Dynamics:** Certain genres consistently outperform others in terms of engagement and average popularity.
* **Market Competition:** Most tracks fall under **average to low popularity**, indicating a highly competitive landscape for new releases.
* **Explicit Content:** Explicit content shows varying impact depending on the genre and target audience demographics.

---

## Project Structure

* `CleanedData/` → Processed dataset used for analysis (`Spotify Track Analysis.xlsx`)
* `Dashboard/` → Final Tableau Workbook (`SpotifyDashboard.twbx`)
* `Assets/` → Dashboard images/screenshots
* `README.md` → Project documentation

---

## Final Outcome

The dashboard provides a clear, interactive, and data-driven view of music trends, helping identify what makes a track successful on Spotify. It serves as a structured analytical framework to understand and optimize music performance using data.

---

## Made with ❤️ by Pratiti Paul


[def]: /Users/pratitipaul/Desktop/SpotifyAnalysis/Assets/Dashboardpic.png
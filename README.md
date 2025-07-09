# Netflix_Business_Case_Data_Exploration_and_Visualisation_(EDA)



## About NETFLIX

Netflix is one of the most popular media and video streaming platforms. They have over **10000 movies or tv shows** available on their platform, as of mid-2021, they have over **222M Subscribers globally**. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

## Business Problem

Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries




## 1. Background and Overview

This project explores Netflix’s dataset using **Exploratory Data Analysis (EDA)** techniques to uncover trends, audience preferences, and content strategies. As part of Netflix’s ongoing mission to lead in streaming entertainment, understanding what kind of content drives engagement is essential for growth.

The analysis is performed using **Python** and its data analysis stack — **Pandas, NumPy, Matplotlib, and Seaborn** — with the objective to **identify which types of shows or movies Netflix should invest in** and how to **expand its global footprint**.

---

## 2. Data Structure Overview

The dataset used consists of Netflix's content catalog, publicly available via Kaggle. It includes over 8,800 entries with details such as:

| Column         | Description                               |
| -------------- | ----------------------------------------- |
| `show_id`      | Unique identifier for each show/movie     |
| `type`         | Whether the content is a Movie or TV Show |
| `title`        | Title of the show or movie                |
| `director`     | Director name (can be null)               |
| `cast`         | Actors involved                           |
| `country`      | Country of origin                         |
| `date_added`   | When the content was added to Netflix     |
| `release_year` | Original release year                     |
| `rating`       | Age group rating (TV-MA, PG, etc.)        |
| `duration`     | Runtime (in minutes or seasons)           |
| `genres`       | Primary genre(s)                          |
| `description`  | Brief summary                             |

### The data was cleaned, nulls handled, and types transformed for effective analysis.


## 3. Executive Summary

Through this EDA, key trends about Netflix’s content strategy and audience preferences were uncovered:

* **TV Shows** now make up a growing share of the catalog.
* **Content addition peaked in 2019**, with a slight decline post-2020.
* **United States, India, UK, and Canada** dominate as production hubs.
* The most common **rating category** is **TV-MA**, suggesting a focus on mature audiences.
* **Drama, Comedy, and Documentaries** are the leading genres.

These insights help guide Netflix's decisions around **content types, regions, and user engagement patterns**.

---

## 4. Insights Deep Dive

### Content Mix

* **Movies (70%)** dominate over TV Shows (30%) but the share of **TV Shows has grown steadily**, indicating shifting consumer demand toward episodic content.

### Temporal Trends

* **2019 had the highest content additions**, reflecting aggressive platform expansion.
* Post-2020, the pandemic appears to have impacted production, with a visible dip in new content uploads.

###  Country-Wise Distribution

* **USA** leads in content production, followed by **India**, **UK**, and **Canada**.
* **Regional diversification** is evident, but Netflix still heavily depends on English-speaking countries.

###  Age Ratings

* Most content is rated **TV-MA**, targeting **mature audiences (18+)**.
* Very few titles cater to children (TV-Y, TV-G), suggesting a growth opportunity in family content.

###  Duration Patterns

* **Movies average around 90–100 minutes**.
* **TV Shows mostly span 1-2 seasons**, ideal for binge-watching, but Netflix may explore longer story arcs for better viewer retention.

### Genre Analysis

* Top genres: **Drama**, **Comedy**, **Documentary**, **Action & Adventure**.
* **Drama** is the single most recurring genre, reflecting high emotional engagement and rewatchability.

---

##  5. Strategic Recommendations

Based on the insights derived

### 1. **Invest in High-Performing Genres**

* **Drama, Comedy, and Documentaries** have consistently high representation and engagement. Focus on producing innovative content in these genres.

### 2. **Expand Regional Content**

* Increase production in **non-English-speaking markets**, especially in **Asia, Latin America, and Africa** to drive new subscriber growth and localization.

### 3. **Explore More Family-Friendly Content**

* With a small portion of content targeted at **children and families**, Netflix has room to grow by developing content in the **TV-G, TV-Y** rating categories.

### 4. **Leverage Data for Sequel and Spin-Off Opportunities**

* Use watch-time and completion data (beyond scope of current dataset) to identify titles with sequel/spinoff potential, particularly in genres like **Action, Sci-fi, and Fantasy**.

### 5. **Optimize TV Show Lengths**

* Encourage **mid-length series** with **3–4 seasons** and high-quality storytelling to increase **subscriber retention**.

### 6. **Maintain Post-2020 Content Volume**

* Restore or exceed **pre-pandemic content upload rates** to remain competitive against new streaming entrants.


---



### **Author:**
 Shaik Mayeenuddin
 Business Analyst | Data Analytics | AI & ML Student
🔗 https://www.linkedin.com/in/shaikmayeenuddin

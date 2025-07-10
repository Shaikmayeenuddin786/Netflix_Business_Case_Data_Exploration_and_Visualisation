# Netflix Data Exploration and Strategic Insights using Python (EDA Project)



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
![image](https://github.com/user-attachments/assets/c4ffa7f5-238e-4c68-97d3-ba8e9a3c11f6)


### Movie release over last 30 years
* Steady Growth from 2000 to 2010 → The graph shows a gradual increase in movie releases starting around 2000,
  must be due to release of netflix and other streaming services
* Sharp Decline After 2020 → Might be related to the COVID-19 pandemic affecting production and releases.
* Minimal Releases before 1990s → The number of movies released before the 1990s is noticibily low
* Before 2010, the rise looked steady, but it exploded in the 2010s , again due to streaming services
![image](https://github.com/user-attachments/assets/2943f802-2f76-4392-b47e-9948c48c0518)



### Temporal Trends

* **2019 had the highest content additions**, reflecting aggressive platform expansion.
* Post-2020, the pandemic appears to have impacted production, with a visible dip in new content uploads.
* By focusing on TV shows, global partnerships, Netflix can sustain its leadership in streaming while aligning with evolving viewer demands.
![image](https://github.com/user-attachments/assets/e97bd050-0dcf-4e4e-8a29-194728cc099e)


###  Country-Wise Distribution

* **USA** leads in content production, followed by **India**, **UK**, and **Canada**.
* **Regional diversification** is evident, but Netflix still heavily depends on English-speaking countries.

###  Age Ratings

* Most content is rated **TV-MA**, targeting **mature audiences (18+)**.
* Very few titles cater to children (TV-Y, TV-G), suggesting a growth opportunity in family content.
![image](https://github.com/user-attachments/assets/21f39aad-cf57-475d-828b-d77f13b3ded6)

###  Duration Patterns

* **Movies average around 90–100 minutes**.
* **TV Shows mostly span 1-2 seasons**, ideal for binge-watching, but Netflix may explore longer story arcs for better viewer retention.
* ![image](https://github.com/user-attachments/assets/530253f6-1a18-4244-b53d-393cb61fcb12)

### Type Anlysis

* Dominance of Mature Content , indicates strong preference for adult-oriented shows.
* Limited Demand for Restricted Content:NC-17" and "UR" indicating minimal demand for extreme adult-rated content.
* The most common content type is TV Shows, making up ~60% of total titles in recent years.

### Genre Analysis

* Top genres: **Drama**, **Comedy**, **Documentary**, **Action & Adventure**.
* **Drama** is the single most recurring genre, reflecting high emotional engagement and rewatchability.
* **Top 5 Popular Genres** in netflix watched most
* ![image](https://github.com/user-attachments/assets/fd2b8aa4-cef6-4b0d-99d7-4a52810e5d3e)


##  Business Growth , the Median (Line Inside the Box) : Movie Duration Analysis (Box Plot Interpretation)
-  The Box (Interquartile Range - IQR) Represents the middle 50% of all Netflix movie durations.
-  A narrow box indicates most movies have similar lengths (consistency).
-  A wider box suggests Netflix offers a diverse range of movie lengths.
-  The Median (Line Inside the Box) Shows the midpoint of all movie durations.Helps understand if movies are typically longer or shorter than average.
![image](https://github.com/user-attachments/assets/1350e278-2361-47a9-888f-018953cc1255)

## Outliers
- These are unusually short or long movies.Likely represent experimental content, such as short films or extended cinematic releases.

---

## 5. Strategic Recommendations


Based on deep exploratory analysis of Netflix’s dataset — including genre trends, geography, audience rating, content duration, cast frequency, and content volume — 

---

###  1. **Leverage Star Power (Top Cast Strategy)**

* Frequent appearances by actors like **Anupam Kher, Radhika Apte, and Shah Rukh Khan** indicate that known personalities drive platform visibility.
* Netflix should **prioritize partnerships with top recurring cast members**, especially in **regional markets** like India, to maximize local engagement and subscriber pull.
* Consider **exclusive contracts** or **branded original series** featuring high-performing cast.

---

### 2. **Grow Through Regional Language and Local Content**

* **USA, India, and the UK** dominate production volume, but there is **underutilized potential** in **Latin America, Southeast Asia, and Africa**.
* Invest in **local storytelling and language dubbing/subtitling** to appeal to culturally diverse audiences.
* Launch **geo-targeted content strategies** (e.g., Nollywood for Africa, K-Dramas for Southeast Asia) to unlock new subscription growth.

---

### 3. **Expand Family and Kids Content**

* Content aimed at younger audiences (e.g., **TV-Y, TV-G**) is underrepresented.
* Netflix can **tap into the family streaming segment** by expanding animated series, educational shows, and kid-friendly movies.
* Partner with educational and edutainment brands for co-branded family content.
* Expand Mature Content Offerings. Strengthen Family-Friendly invest more TV-PG" and "TV-G" rated content,

---

### 4. **Restore and Maintain High Content Upload Volume**

* Content addition peaked in **2019**, followed by a **drop post-COVID**.
* Aim to **return to 2019-level publishing** (especially in TV Shows), which coincided with strong user growth.
* Explore **content diversification** (mini-series, documentaries, short films) to maintain a healthy content cadence.
* Very long movies can be branded as "Netflix Specials" — perfect for deep storytelling or cinematic experiences.
* If longer movies show high engagement, Netflix should invest in big-budget, story-rich films or limited series.
* Short films and mini-movies appeal to busy viewers — ideal for mobile users or casual watch behavior. Netflix can expand its "Quick Watch" category for daily engagement.



---

### 5. **Invest in Limited-Series TV Shows**

* Prioritize TV Shows for Long-Term Engagement TV shows have seen consistent growth, while movie production peaked and declined after 2018.
* Expand Global Content Production The dominance of International Movies & Dramas highlights a strong demand for culturally diverse stories. Netflix should collaborate with local filmmakers
* Invest Heavily in Stand-Up Comedy & Documentaries , Comedy specials and documentaries are among the top-performing genres,
* Encourage **high-quality limited series** with well-defined arcs that promote binge-watching while minimizing production risk.
* Use viewer retention metrics to decide when to extend successful shows to multiple seasons.

---

### 6. **Double Down on Winning Genres**

* **Drama, Comedy, and Documentary** content continues to dominate and show high viewer affinity.
* Prioritize **original content production** in these genres with fresh storylines and diverse representation.
* Introduce **genre blending** (e.g., Comedy-Dramas, Docu-Thrillers) to attract broader audiences.

---

### 7. **Strategic Content Budgeting**

* Invest heavily in content that combines **popular genres with top cast and culturally resonant themes**.
* Use historical data to identify combinations (e.g., “Drama + Radhika Apte + India”) that correlate with repeat viewing.

---



### **Author:**
 Shaik Mayeenuddin
 | Business Analyst | Data Analytics | AI & ML Student
🔗 https://www.linkedin.com/in/shaikmayeenuddin

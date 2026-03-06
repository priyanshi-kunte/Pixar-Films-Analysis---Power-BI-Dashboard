#  Pixar Films Analysis – Power BI Dashboard

##  Project Overview
This project presents an **interactive Power BI dashboard** that analyzes the performance of **Pixar Animation Studios films**.  
It visualizes insights related to **box office revenue, ratings, genres, awards, and crew involvement** to understand trends and success factors across Pixar's filmography.

---

##  Objectives
- Analyze **box office performance** of Pixar films.
- Explore **audience and critic ratings** (IMDb, Metacritic, Rotten Tomatoes).
- Identify **top grossing movies** and ROI.
- Examine **genres, awards, and crew contributions**.
- Build an **interactive dashboard for data exploration**.

---

##  Dataset Tables
The dashboard uses the following datasets:

- **pixar_films** – film details (title, release date, runtime, rating)
- **box_office** – budget and worldwide revenue
- **public_response** – IMDb, Metacritic, Rotten Tomatoes scores
- **academy** – awards and nominations
- **genres** – genre and subgenre information
- **pixar_people** – directors, writers, musicians
- **people_link** – images and role mapping

---

##  Data Model
The project follows a **snowflake schema** with **pixar_films** as the central table connected to other datasets through relationships using the **film** column.

---

##  DAX Measures
DAX measures were used to calculate key metrics such as:

- **Total Revenue**
- **Total Budget**
- **Return on Investment (ROI)**
- **Average IMDb Rating**
- **Top 5 Grossing Films**
- **Awards Count**

These measures power **dynamic visuals and KPIs** in the dashboard.

---

##  Dashboard Pages

### 1. Overview Page
Provides a summary of Pixar films including:

- KPI cards (Revenue, ROI, IMDb Score, Budget)
- Top 5 Grossing Films
- Revenue distribution by region
- Film rating breakdown (G vs PG)
- Public ratings table

### 2. Film Details Page
Displays detailed insights for each film including:

- Film poster and description
- Crew members involved
- Awards and nominations
- Ratings and performance metrics

---

##  Tools Used
- **Microsoft Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**

---

 If you find this project useful, feel free to **star the repository!**

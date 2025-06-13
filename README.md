# 🎥 Netflix Data Analysis SQL Project

## 📜 Overview
This project showcases my SQL expertise through an analytical deep dive into Netflix’s dataset. Using advanced SQL techniques, I solved real-world streaming service challenges, extracted key insights, and provided data-driven solutions aligned with business and customer needs.

---

## 🗂 Project Structure

### 1. Database Setup
- Created the `netflix_db` database.
- Designed and structured the `netflix` table to reflect Netflix’s core data operations.

### 2. Data Import
- Imported sample data to replicate Netflix's content library and user behavior.

### 3. Data Cleaning
- Addressed inconsistencies and null values.
- Ensured data reliability and integrity for accurate analysis.

### 4. Business Problems Solved
- Solved 10+ real-world streaming platform problems using advanced SQL queries.

---

## 📊 Key Topics and Skills Covered

- **Database Creation and Table Design:** Structured data for Netflix’s streaming operations.
- **Aggregate and Grouping Functions:** Analyzed content trends, genre popularity, and top-performing regions.
- **Joins:** Connected datasets to explore user preferences and content distribution.
- **Window Functions:** Ranked top-rated content and tracked subscription trends.
- **Date and Time Functions:** Studied content release trends by year, month, and day.
- **Data Segmentation:** Grouped content into genres, countries, and ratings.
- **Subqueries:** Used for breaking down complex queries and driving focused insights.

---

## 🧩 Database Tables

### `netflix` Table

| Column Name | Data Type     | Description                                  |
|-------------|---------------|----------------------------------------------|
| show_id     | VARCHAR(5)    | Unique ID for the show or movie              |
| type        | VARCHAR(10)   | Type of content (e.g., Movie, TV Show)       |
| title       | VARCHAR(250)  | Title of the content                         |
| director    | VARCHAR(550)  | Director(s) of the content                   |
| casts       | VARCHAR(1050) | Cast members featured in the content         |
| country     | VARCHAR(550)  | Country of origin                            |
| date_added  | VARCHAR(55)   | Date when content was added to Netflix       |
| release_year| INT           | Year of release                              |
| rating      | VARCHAR(15)   | Content rating (e.g., PG, R, TV-MA)          |
| duration    | VARCHAR(15)   | Duration (e.g., minutes or number of seasons)|
| listed_in   | VARCHAR(250)  | Genres associated with the content           |
| description | VARCHAR(550)  | Synopsis of the content                      |

> 💡 Note: Currently the dataset includes a single comprehensive table (`netflix`). Future enhancements may include relationships with users, subscriptions, and viewing behavior data.

---

## 🚀 Highlights of the Analysis

- Identified the most popular content types (Movies vs. TV Shows)
- Analyzed content distribution by rating and release year
- Segmented content by genre and country for localized insights
- Determined top-performing directors and most-featured cast members

---

## 📚 Learning Outcomes

- Crafted efficient and insightful SQL queries to analyze Netflix’s library
- Discovered patterns in content addition frequency, genre distribution, and viewer ratings
- Mastered advanced SQL techniques like window functions, CTEs, and subqueries for solving real business challenges

---




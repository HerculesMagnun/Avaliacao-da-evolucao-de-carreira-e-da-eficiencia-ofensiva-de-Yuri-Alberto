# Yuri Alberto — Career Performance Analysis ⚽📊

## Project Overview
This project focuses on the analysis of **Yuri Alberto’s professional football career**, using data analytics to simulate a real-world **player scouting and recruitment evaluation**.

The main goal is to understand how the player’s performance evolved over time, especially in terms of **offensive efficiency**, and to assess whether his statistical profile suggests continuous improvement or performance stabilization.

This project reflects the type of analysis commonly used by **sports analytics and scouting departments**.

---

## Objectives
The analysis aims to answer the following key questions:

- Has the player’s offensive efficiency improved over the years as experience increased?
- How many shots, on average, does the player need to score a goal, and how has this metric evolved?
- Based on historical performance data, does the player present an attractive profile for recruitment decisions?

These questions were defined **before data collection**, ensuring a hypothesis-driven analysis rather than random data exploration.

---

## Data Source
The dataset used in this project was manually built using data collected from **SofaScore**, a reliable public platform for football performance statistics.

All career data was structured season by season, covering the player’s trajectory from early professional appearances to recent seasons.  
When specific statistics were unavailable, values were intentionally left as `NULL` to preserve data integrity and avoid assumptions.

---

## Dataset Structure
The main dataset is stored in CSV format and includes the following fields:

- `season`
- `club`
- `matches`
- `minutes_played`
- `goals`
- `assists`
- `average_rating`
- `competition_won`
- `shots`
- `shots_on_target`
- `big_chances_missed`

The dataset is designed to support longitudinal analysis and efficiency metrics.

---

## Tools & Technologies
The analysis is conducted using:

- **SQL** for data querying, aggregation, and metric creation
- **Google Sheets** for initial data organization
- **CSV** as the standardized data format
- (Future) Data visualization tools for performance trends

---

## Methodology
The analytical process follows these steps:

1. Data collection from SofaScore
2. Data structuring and cleaning
3. Importing the dataset into a SQL database
4. Exploratory analysis and metric calculation
5. Performance evaluation using normalized metrics (e.g., goals per 90 minutes)

---

## Scope & Limitations
This project focuses exclusively on **individual offensive performance**.

It does **not** aim to:
- Evaluate collective tactical impact
- Analyze team titles or overall team performance
- Deeply explore injuries or disciplinary records (future extension)

---

## Next Steps
- Complete SQL data import and validation
- Develop advanced efficiency metrics
- Create visualizations to illustrate performance evolution
- Extend the analysis to compare the player with peers

---

## Disclaimer
This project is for **educational and portfolio purposes only** and does not represent official scouting or recruitment decisions.

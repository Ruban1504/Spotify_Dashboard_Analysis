Spotify Analysis Challenge - Maven Analytics
======
![Chat Preview](https://imgur.com/iPMNOwj.png)
![Chat Preview](https://imgur.com/5Il1wnM.png)



---


## Overview
This repository contains a project focused on analyzing **Spotify listening history** using Data Analytics techniques. The Spotify Dashboard Challenge by Maven Analytics is a comprehensive data analysis project designed to uncover insights into music consumption patterns. Using Power BI, the project explores over **149,860 records** to identify trends in listening behavior, top songs, skipped tracks, and playback habits, helping to visualize and interpret personal music preferences **effectively**.

---

## Problem Statement
The challenge in this project is to discover:

1. **Listening Trends**
    – Analyzing yearly, monthly, and hourly trends in total minutes played.

2. **Top & Least Played Music**
      – Identifying the most played songs, artists, albums, and skipped tracks.
3. **Playback Behavior**
     – Understanding reasons for starting or stopping tracks and platform preferences.
4. **Music Engagement Patterns**
     – Analyzing shuffle usage, weekend/night plays, and long-term trends.
---
## Dataset
The **Spotify Listening History** dataset contains:  
- **149,860 records** tracking user listening behavior.  
- Information about track names, artists, albums, play duration, playback platform, shuffle mode, and reasons for starting or ending a track.  

---
## Project Workflow

1. **Problem Identification**:
   - Identified key insights to extract from the Spotify listening history.
   - Listed out KPI measures and relevant charts for trend analysis.

2. **Data Preprocessing**:
   - Loaded the dataset in Power BI and cleaned the raw data.
   - Standardized column names and checked for missing or inconsistent values.
   - Gained a rough understanding of the dataset structure.
   
3. **Power BI Analysis**:
   - Created measures for total tracks, total artists, total minutes played, and skipped tracks.
   -  Designed interactive charts to analyze listening behavior across different time frames.
   - Developed a well-structured dashboard to visualize trends and insights.

4. **Cross Validation**:
   - Ensured accuracy by cross-checking results and verifying calculations.
   - Validated trends in listening habits using aggregated data analysis.
   
5. **Documentation**:
   - Documented all key insights, findings, and dashboard designs.
   - Uploaded the project details and findings on GitHub for reference.


Description
Below is the detailed field of dataset.
## Spotify Listening History  
| Data field         | Description                                      | Unit/Format   |
|--------------------|--------------------------------------------------|--------------|
| spotify_track_uri | Unique identifier for each track                  | String       |
| ts               | Timestamp of when the track was played             | DateTime     |
| platform         | Device/platform used to play the track             | Categorical  |
| ms_played       | Duration the track was played                       | Milliseconds |
| track_name      | Name of the track                                   | String       |
| artist_name     | Name of the artist                                  | String       |
| album_name      | Name of the album                                   | String       |
| reason_start    | How the track started (e.g., autoplay, user action) | Categorical  |
| reason_end      | How the track ended (e.g., track finished, skipped) | Categorical  |
| shuffle         | Indicates if shuffle mode was on (True/False)       | Boolean      |
| skipped         | Indicates if the track was skipped (True/False)     | Boolean      |


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ruban1504/Spotify_Dashboard_Analysis.git

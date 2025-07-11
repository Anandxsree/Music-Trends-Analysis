# 🎧 Music Trends Analysis: Last.fm Top Tracks (May 2025)

Welcome to the **Music Trends Analysis** project! This repository contains a Power BI dashboard and supporting assets to explore music popularity using **Last.fm’s top tracks from May 2025**.

---

## 🔍 Project Overview

This project analyzes **99 top tracks** from Last.fm to uncover:

* 📈 Trends among the most played and most listened tracks
* 🎤 Popular artists such as Arctic Monkeys, Radiohead, and The Killers
* 🧠 Factors contributing to a track's popularity using a machine learning model

We used a **Random Forest model (90% accurate)** to predict track popularity, with **listeners** being the most important feature (**86.34% importance**).

---

## ✨ Features

* Treemap of the top 15 artists by playcount
* Bubble chart comparing playcounts vs. listeners (green = more popular)
* Word cloud showing top 20 tracks by listeners
* Bar chart of top 10 tracks colored by artist
* KPI cards for model accuracy and feature importance
* Interactive filter to explore artist-specific data (e.g., Charli XCX, Sabrina Carpenter)

---

## 📁 Repository Structure

```
Music-Trends-Lastfm/
├── Music_Trends_Dashboard_Final.pbix         # Power BI dashboard file
├── lastfm_dashboard_data.csv                 # Dataset of top 99 tracks
├── music_trends_analysis.py                  # Python script for modeling (optional)
├── lastfm_popularity_model.pkl               # Trained Random Forest model
├── Music Trends Analysis.ipynb               # Jupyter notebook for data analysis
├── artist_playcount.png                      # Visualization: top artists by playcount
├── playcount_vs_listeners.png                # Visualization: playcount vs. listeners
└── README.md                                 # Project documentation
```

---

## 📸 Dashboard Preview

![Artist Playcount](artist_playcount.png)
![Playcount vs Listeners](playcount_vs_listeners.png)

---

## 🚀 How to Use

1. **Install Power BI Desktop**
   Download from [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

2. **Open the Dashboard**
   Launch `Music_Trends_Dashboard_Final.pbix` in Power BI Desktop

3. **Explore the Insights**

   * Use the artist filter to focus on specific artists like **Sabrina Carpenter**
   * Hover on visuals to see details (playcount, listeners)
   * Review model cards for accuracy and feature importance

> 💡 If the `.pbix` file is not included, you can still view the main visuals in the `.png` images.

---

## 🔑 Key Findings

* **Top Artists**: Arctic Monkeys, The Killers, Radiohead each have over **40M plays**
* **Top Tracks**: “Mr. Brightside” (3.38M listeners), “Creep” (3.29M)
* **Model Insight**: Listener count is the biggest factor in predicting track popularity
* **Actionable Insights**:

  * Promote tracks with **>1M listeners** (e.g., “Poker Face”)
  * Highlight artists with multiple hits like **Charli XCX** or **Sabrina Carpenter**

---

## ⚠️ Limitations

* Track duration data is often missing or recorded as 0.0 seconds
* No genre data available — genre trends were not analyzed

---

## 💡 Future Enhancements

* Use the Last.fm API to collect accurate track duration
* Add genre classification to explore trends across music types

---

## 👤 About Me

Hi, I’m **Anand** – a data analyst with a passion for insights and storytelling.

This project highlights my skills in **Power BI**, **data visualization**, and **machine learning**.

Other projects: [BlinkIT Grocery Power BI Dashboard](https://github.com/Anandxsree/Power-bi)

---

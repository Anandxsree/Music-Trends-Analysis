# 🎧 Music Trends Analysis: Last.fm Top Tracks (May 2025)

This project is a **Power BI dashboard** that analyzes music trends using **Last.fm data** from **May 2025**. It includes a **machine learning model (90% accurate)** to predict track popularity based on features like artist, playcount, and listener count.

---

## 📊 What This Project Does

Using data from **99 top tracks**, this project explores:

- 🔥 **Top Artists**: For example, **Arctic Monkeys** with ~42.9M plays.
- 🎶 **Most Listened Tracks**: Like **“Mr. Brightside”** with **3.38M listeners**.
- 🧠 **Relationship between playcounts and listeners** (via a bubble chart).
- 🤖 **Popularity Prediction Model**: A **Random Forest** model (90% accurate), where **listeners** contribute **86.34%** to track popularity.

---

## 📈 Dashboard Visuals

The Power BI dashboard includes:

- 🟩 **Treemap**: Top 15 artists by playcount.
- 🟢 **Bubble Chart**: Playcount vs. Listeners (green bubbles = more popular).
- ☁️ **Word Cloud**: Top 20 tracks by listeners.
- 📊 **Bar Chart**: Top 10 tracks, color-coded by artist.
- 📌 **KPI Cards**:
  - Model Accuracy: **90%**
  - Most Important Feature: **Listeners (86.34%)**
- 🔍 **Interactive Filter**: Select an artist (e.g., **Charli XCX**, **Sabrina Carpenter**) to explore individual tracks.

---

## 🗂️ Files in This Project

| File                            | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| `Music_Trends_Dashboard_Final.pbix` | Power BI dashboard (might be missing if not uploaded).                   |
| `lastfm_dashboard_data.csv`     | Dataset with 99 tracks: track name, artist, playcount, listeners.         |
| `music_trends_analysis.py`      | Python script to collect data & train model (optional).                   |
| `lastfm_popularity_model.pkl`   | Trained **Random Forest** model (90% accuracy).                           |
| `artist_playcount.png`          | Image of top artists by playcount.                                        |
| `playcount_vs_listeners.png`    | Image of bubble chart (playcount vs. listeners).                          |
| `Music Trends Analysis.ipynb`   | Jupyter notebook with full data analysis.                                 |

---

## ▶️ How to Use It

1. **Download** `Music_Trends_Dashboard_Final.pbix`.
2. **Open** it in **Power BI Desktop** ([Download Power BI](https://powerbi.microsoft.com/)).
3. **Explore the dashboard**:
   - Use the **filter** to focus on artists (e.g., *Sabrina Carpenter*).
   - Hover over visuals for playcount & listener info.
   - View model accuracy and importance in the **KPI cards**.

> 🔍 *If the `.pbix` file is missing, refer to the visuals in the `.png` images.*

---

## 🔑 Key Findings

- **Top Artists**: Arctic Monkeys, The Killers, Radiohead — each with **40M+** plays.
- **Top Tracks**: “Mr. Brightside” (3.38M listeners), “Creep” (3.29M).
- **Model Insight**: Listener count is the biggest predictor of popularity (**86.34% importance**).
- **Suggestions**:
  - Promote tracks with **>1M listeners** (e.g., “Poker Face”).
  - Feature artists with **multiple hits** (e.g., Charli XCX, Sabrina Carpenter).

---

## ⚠️ Limitations

- 🎵 Missing or invalid **track duration data** (many values = 0.0 sec).
- 🎼 No **genre information**, so genre-based analysis wasn't possible.

---

## 💡 Future Improvements

- Pull better **duration data** from the **Last.fm API**.
- Add **genre classification** to analyze music trends by type.

---

## 👤 About Me

Hi, I’m **Anand** – a passionate data analyst.  
This project showcases my skills in **Power BI**, **data visualization**, and **predictive modeling**.  
Other projects I’ve worked on include the **Blinkit Grocery Data Analysis (May 2025)**.

---


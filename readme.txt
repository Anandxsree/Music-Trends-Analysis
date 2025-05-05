Music Trends Analysis: Last.fm Top Tracks (May 2025)
This project is a Power BI dashboard that looks at music trends using data from Last.fm, as of May 2025. It uses a model that’s 90% accurate to predict which tracks are popular, focusing on artists, tracks, and listener patterns.
What This Project Does
I analyzed 99 top tracks from Last.fm to find trends:

Which artists are the most popular (like Arctic Monkeys with ~42.9M plays).
Which tracks have the most listeners (like “Mr. Brightside” with 3.38M listeners).
How playcounts and listeners are related (using a bubble chart).
A model (90% accurate) shows listeners are the biggest factor (86.34% importance) in predicting popularity.

The dashboard has visuals like:

A treemap showing the top 15 artists by playcount.
A bubble chart comparing playcounts and listeners (green means popular).
A word cloud of the top 20 tracks by listeners.
A bar chart of the top 10 tracks, colored by artist.
Cards showing the model’s accuracy (90%) and top factor (listeners).
A filter to look at specific artists (like Charli XCX’s 6 tracks).

Files in This Project

Music_Trends_Dashboard_Final.pbix: The Power BI dashboard file (might be missing if not uploaded yet).
lastfm_dashboard_data.csv: The dataset with 99 tracks (has columns like track name, artist, playcount, listeners).
music_trends_analysis.py: The Python script that collects data and builds the model (might be missing if not uploaded yet).
lastfm_popularity_model.pkl: The trained model file (Random Forest, 90% accurate).
artist_playcount.png: A picture of the top artists by playcount.
playcount_vs_listeners.png: A picture of the playcount vs. listeners chart.
Music Trends Analysis.ipynb: A Jupyter notebook with my analysis.

How to Use It

Download the Music_Trends_Dashboard_Final.pbix file (if it’s in the repository).
Open it in Power BI Desktop (you can download Power BI from Microsoft).
Explore the dashboard:
Use the filter to pick an artist (like Sabrina Carpenter to see “Espresso”).
Hover over visuals to see more details (like playcounts and listeners).
Look at the cards to see the model’s accuracy.



If the .pbix file isn’t here, you can still see the visuals in artist_playcount.png and playcount_vs_listeners.png.
Key Findings

Top Artists: Arctic Monkeys, The Killers, and Radiohead have over 40M plays each.
Popular Tracks: “Mr. Brightside” (3.38M listeners) and “Creep” (3.29M listeners) are the most listened to.
Model Insight: The number of listeners is the biggest reason a track is popular (86.34% importance in the model).
Suggestions: Streaming platforms should promote tracks with over 1M listeners (like “Poker Face”) and feature artists with many hits (like Charli XCX or Sabrina Carpenter).

Limitations

The dataset doesn’t have good duration data for tracks (many are 0.0 seconds).
There’s no genre information, so I couldn’t look at trends by music type.

Future Ideas

Get better track duration data from the Last.fm API.
Add genre data to see which music types are most popular.


About Me: I’m Anand, and this is part of my work in data analysis. I’ve also done projects like the Blinkit Grocery Data Analysis (May 2025). This project shows my skills in Power BI, data visualization, and building models to find insights.

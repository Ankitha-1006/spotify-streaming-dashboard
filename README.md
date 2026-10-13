1. Project Title
Spotify Streaming Analytics Dashboard (2020–2025)
This project is an interactive data analytics dashboard developed using Microsoft Power BI to analyze Spotify streaming data, understand music popularity, compare artists and genres, and explore trends in streaming activity from 2020 to 2025.
The main objective is to transform raw Spotify dataset information from Kaggle into meaningful visual insights that can help users understand listening trends, music characteristics, and content popularity.

2. Dashboard Description
The Spotify Streaming Analytics Dashboard provides a visual overview of streaming performance using key performance indicators (KPIs), charts, and interactive filters. It analyzes streaming counts, artist performance, popular albums, genres, release timing, and audio characteristics such as danceability, energy, and loudness.
Spotify Streaming Analytics: Presents an overview of streaming performance, top artists, top genres, album popularity, yearly trends, audio characteristics, and explicit-content distribution.
Spotify Streaming Analytics: Presents an overview of streaming performance, top artists, top genres, album popularity, yearly trends, audio characteristics, and explicit-content distribution.
Users can interact with the dashboard using genre and country slicers to explore different segments of the data. This makes it easier to move from a general overview to more specific comparisons.

3.Technology	Purpose in the project
Power BI Desktop	Created the interactive dashboard, KPIs, charts, slicers, and report pages.
DAX (Data Analysis Expressions)	Created measures and calculations for aggregated metrics, including average audio characteristics and streaming performance.
Power Query	Used for importing, cleaning, transforming, and preparing raw data for analysis.
Data Modeling	Organizes the dataset fields and measures so they can be analyzed together in Power BI.

4.Data Source 
A CSV file is downloaded from kaggle.com

5.Features and Highlights

1. Key Performance Indicators (KPIs)
The dashboard displays summary cards for:
- Total streams
- Total artists
- Total tracks
- Average loudness
- Average energy percentage
- Average danceability percentage
These indicators provide a quick overview of the dataset and its music characteristics.
2. Top 10 Streamed Artists
A clustered bar chart compares artists by their total streaming counts. It helps identify high-performing artists and compare their streaming performance.
3. Top 10 Streamed Genres
A bar chart compares genres based on total streams. It helps identify popular music categories and provides a basis for genre-level comparisons.
4. Yearly Streaming and Popularity Trends
A combination chart compares yearly streaming counts with average popularity from 2020 to 2025. It helps examine how streaming activity and popularity change over time.
5. Popular Albums Analysis
A column chart compares album names using popularity scores. It supports album-level comparisons and helps highlight albums with stronger popularity scores.
6. Danceability vs. Energy by Genre
A scatter chart compares danceability and energy, with genres represented in the visual and streaming count used for bubble size. It helps explore relationships between musical characteristics and streaming activity.
7. Weekend Release Percentage
A donut chart compares weekend-release categories. It provides a quick view of how the dataset's releases are distributed between weekend and non-weekend releases.
8. Explicit Content Analysis
A donut chart compares streaming counts for explicit and non-explicit content. It helps examine how streaming activity is distributed between these content categories.
9. Interactive Filters
- Genre slicer: Filters the report by selected music genres.
- Country slicer: Enables country-based exploration where country data is available.
Interactive filtering allows users to investigate specific segments instead of relying only on overall totals.


6. Example Business Problems 
How the dashboard addresses the problem
Problem 1: Identifying successful artists
Dashboard solution: Use the Top 10 Streamed Artists chart to compare streaming counts and identify leading artists in the available data.
Problem 2: Understanding genre preferences
Dashboard solution: Compare genres by total streams and use the genre slicer to explore individual categories.
Problem 3: Tracking changes over time
Dashboard solution: Use the yearly combination chart to compare streaming counts and average popularity from 2020 to 2025.
Problem 4: Exploring music characteristics
Dashboard solution: Use the danceability-versus-energy scatter chart to explore differences across genres and investigate their relationship with streaming counts.
Problem 5: Comparing release patterns
Dashboard solution: Examine the weekend-release distribution and explicit-content streaming breakdown to identify patterns worth further investigation.

7.sample dashboard view 
https://github.com/Ankitha-1006/spotify-streaming-dashboard/blob/main/spotifydashboard.png

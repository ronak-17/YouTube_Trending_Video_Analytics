# YouTube Trending Video Analytics
Analyze and visualize trends in YouTube's most popular content from the US and India using Python, SQL, and Tableau.

🔍 Project Overview
This project uncovers patterns in YouTube trending videos using datasets from India and the US. It explores:

Most popular video categories

Viewer engagement metrics

Sentiment in titles and tags

Regional and temporal trends

🛠️ Tools & Technologies
Python: Data preprocessing, cleaning, and sentiment analysis

SQLite3: SQL-based querying in Jupyter

TextBlob: Sentiment analysis of video titles and tags

Jupyter Notebook: End-to-end data pipeline and SQL execution

Tableau: Interactive dashboard creation and visualization

📁 Dataset
YouTube Trending Video CSV files (India and US)

Category mapping via category_id.json

Date range: up to April 2024

🔄 Workflow Summary
1. Data Preparation
Cleaned and standardized datasets

Combined data from India and US

Mapped category IDs to names

2. SQL Integration
Loaded data into SQLite using sqlite3

Executed queries for:

Regional comparison

Top categories by views and engagement

Videos with longest trending duration

3. Sentiment Analysis
Used TextBlob to evaluate polarity of titles and tags

Classified as Positive, Neutral, or Negative

4. Visualization (Tableau)
Created:

Pie charts for category distribution

Line charts for monthly trending patterns

Bar charts for top performing videos

📈 Key Insights
India had a consistently higher number of trending videos.

Music & Entertainment led in views and engagement.

Positive sentiment in titles correlated with longer trending duration.

Cultural/seasonal events triggered spikes in trending content.

📜 Final Report
A detailed 2-page PDF report is included, summarizing:

Objective

Methodology

Tools

Insights

Visuals

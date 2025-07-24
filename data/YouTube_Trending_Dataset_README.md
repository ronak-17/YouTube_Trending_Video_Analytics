# 📁 Dataset Description - YouTube Trending Video Analytics

This project utilizes publicly available YouTube trending video datasets for the **United States** and **India**, including video metadata, engagement metrics, and category mappings.

## 📄 USvideos.csv
- **Region**: United States
- **Description**: Contains daily records of trending YouTube videos in the US.
- **Key Columns**:
  - `video_id`: Unique identifier for each video
  - `title`: Title of the video
  - `channel_title`: Name of the video’s publisher
  - `category_id`: Numerical ID for video category
  - `publish_time`: Timestamp of video publication
  - `views`, `likes`, `dislikes`, `comment_count`: Engagement metrics
  - `tags`: List of tags associated with the video
  - `trending_date`: Date the video was trending

## 📄 INvideos.csv
- **Region**: India
- **Description**: Contains daily records of trending YouTube videos in India.
- **Structure**: Same as `USvideos.csv`, enabling easy comparison across regions.

## 📄 US_category_id.json and IN_category_id.json
- **Description**: JSON files mapping `category_id` values to human-readable category names (e.g., Music, Gaming, News).
- **Usage**: Used to enrich CSV data by adding category labels during preprocessing.

## 🔄 Notes
- Data is updated till **April 2024**
- CSV files are large due to multiple days of trending data for the same videos
- Used **Python** (Pandas) for preprocessing, including merging category names and handling missing values

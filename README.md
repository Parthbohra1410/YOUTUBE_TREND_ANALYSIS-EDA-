# 📊 YouTube Trending Video Analysis

This project is an **Exploratory Data Analysis (EDA)** on YouTube Trending Videos data. It aims to uncover trends, patterns, and insights behind what makes a video trend on YouTube across different countries like the US, India, UK, etc.

---

## 🧠 Objective

The goal is to analyze the dataset to understand:

- What factors influence a video to trend?
- Which categories and channels trend the most?
- How engagement metrics (likes, dislikes, comments) affect popularity?
- What are the differences in trending patterns across countries?

---

## 📂 Dataset

- **Source:** [Kaggle - YouTube Trending Videos](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- **Files:** Includes CSV files for countries like `USvideos.csv`, `INvideos.csv`, etc.
- Each row represents a video that was trending on YouTube for a specific day.

---

## 📌 Features in the Dataset

| Column Name       | Description                                   |
|-------------------|-----------------------------------------------|
| `video_id`        | Unique video identifier                       |
| `title`           | Title of the video                            |
| `publishedAt`     | Date and time of publication                  |
| `channel_title`   | Channel name                                  |
| `category_id`     | ID of the video category                      |
| `tags`            | Tags used in the video                        |
| `views`           | Number of views                               |
| `likes`           | Number of likes                               |
| `dislikes`        | Number of dislikes                            |
| `comment_count`   | Number of comments                            |
| `thumbnail_link`  | URL of the thumbnail                          |
| `comments_disabled` | Whether comments are disabled                |
| `ratings_disabled`  | Whether ratings are disabled                 |
| `video_error_or_removed` | Whether video was removed               |
| `description`     | Description of the video                      |

---

## 🔍 Key Analyses Performed

- 📈 Trends over time (published vs trending date)
- 🔥 Top trending categories & channels
- 💬 Likes, dislikes, comment trends
- 🌍 Comparison across different countries
- 🧮 Title length, tag count, description length effects
- 📊 Correlation heatmaps and interactive visualizations

---

## 🛠 Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Plotly (optional for interactive visuals)
- Jupyter Notebook / Google Colab

---

## 📸 Example Visualizations

- Top 10 most frequent trending channels
- Categories with the highest views/likes
- Trend of views over time
- Heatmaps for correlation between features

---


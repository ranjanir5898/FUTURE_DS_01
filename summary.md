# 📊 Social Media Sentiment Analysis

## 📝 Overview
This project involves analyzing 732 social media posts collected from platforms such as **Facebook**, **Twitter**, and **Instagram**. The goal is to uncover insights into user sentiment trends, engagement (likes and retweets), hashtag usage, and platform-based behavior using **Python** for data analysis and **Power BI** for visual storytelling.

---

## 📁 Dataset Description

- **Total Records**: 732
- **Key Columns**:
  - `Text`: Content of the social media post
  - `Sentiment`: Emotion (e.g., Positive, Negative, Joy)
  - `Timestamp`, `Year`, `Month`, `Day`, `Hour`: Temporal details
  - `Platform`: Facebook, Twitter, Instagram
  - `User`: Username
  - `Hashtags`: Tags used in the post
  - `Likes`, `Retweets`: Engagement metrics
  - `Country`: Country of the user

---

## ⚙️ Tools & Libraries Used

- **Python** (Jupyter Notebook)
  - `pandas`, `numpy`: Data cleaning and transformation
  - `matplotlib`, `seaborn`: Visualizations
- **Power BI**: Interactive dashboards
- **GitHub**: Version control and documentation

---

## 🔄 Data Cleaning and Preparation

- Dropped redundant columns (`Unnamed: 0.1`)
- Renamed column `Unnamed: 0` to `Id`
- Converted `Timestamp` to datetime format
- Extracted `Year`, `Month`, `Day`, `Hour` from `Timestamp`
- Removed whitespace from categorical fields
- Verified data types and missing values (none found)

---

## 📈 Exploratory Data Analysis (EDA)

### 📌 Sentiment Distribution
- Most frequent sentiments: **Positive**, **Joy**, and **Gratitude**
- Sentiments plotted with `value_counts()` on bar chart

### 📌 Platform Analysis
- Instagram had the highest number of posts (258), followed by Twitter (243) and Facebook (231)
- Pie chart used to show platform distribution

### 📌 Hashtag & Country Trends
- Top 10 hashtags: Based on `value_counts()` and plotted as a bar chart
- Top countries: USA, UK, Canada, Australia, etc.

---

## 🔥 Engagement Insights

### ✅ Top 10 Hashtags by Retweets
- Highest engagement hashtags vary across platforms
- Facebook, Twitter, and Instagram show different sets of top-performing hashtags

### ✅ Likes and Retweets by Platform
- Instagram had the highest cumulative likes
- Twitter and Facebook show competitive retweet performance

---

## 📊 Platform-Specific Deep Dives

### 🔵 Facebook
- Top users by total likes
- Top 10 hashtags by retweets
- Cumulative likes and retweets trend over years (2010–2023)

### 🐦 Twitter
- Top users by total likes
- Top 10 retweeted hashtags
- Cumulative engagement trend (likes & retweets) over time

### 📸 Instagram
- Top 15 hashtags by retweets
- Top users by total likes
- Yearly cumulative likes and retweets plotted using `lineplot` with annotations

---

## 📉 Summary Statistics

| Metric      | Min   | Max   |
|-------------|-------|-------|
| Likes       | 10.0  | 80.0  |
| Retweets    | 5.0   | 40.0  |
| Year        | 2010  | 2023  |
| Month       | 1     | 12    |
| Day         | 1     | 31    |
| Hour        | 0     | 23    |

---

## 📌 Insights

- **Instagram** dominates in terms of total likes, especially in recent years.
- **Twitter** had the most diverse mix of sentiments, including surprise and annoyance.
- **Top countries** contributing to posts: USA, UK, Canada, and Australia.
- **Engagement trends** (likes and retweets) steadily increased from 2010 to 2023.

---

## 📎 Power BI Dashboards

Power BI visualizations were used to:
- Show top sentiments
- Compare platform usage
- Highlight hashtag and country-based trends
- Display time-based engagement patterns

📁 Find visuals in the `visuals/` folder.

---

## 🔮 Future Enhancements

- Integrate real-time streaming of tweets
- Apply advanced NLP models (e.g., BERT) for deeper sentiment tagging
- Use interactive dashboards with filters for user exploration

---

## 👩‍💻 Contributor

- **Ranjani Priyaa**

For feedback or collaboration, feel free to connect.


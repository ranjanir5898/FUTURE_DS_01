# FUTURE_DS_01
Social media sentimental analysis
## overview
# 📊 Social Media Sentiment Analysis

## 📝 Overview
This project focuses on analyzing user sentiments across major social media platforms — Facebook, Twitter, and Instagram — using a dataset containing 732 posts. The goal is to understand user emotion trends, popular hashtags, and platform engagement through both Python-based preprocessing and Power BI visualizations.

## 📁 Dataset Description
The dataset contains 732 records and includes the following columns:
- `Unnamed: 0`: Index
- `Text`: The content of the post
- `Sentiment`: Emotion or tone (e.g., Positive, Joy, Gratitude)
- `Timestamp`: Date and time of post
- `User`: Username or user ID
- `Platform`: Facebook / Twitter / Instagram
- `Hashtags`: Hashtags used in the post
- `Retweets`: Retweet count (if Twitter)
- `Likes`: Like count
- `Country`: Country of the user
- `Year`, `Month`, `Day`, `Hour`: Extracted from Timestamp

## 🔧 Tools & Technologies
- **Python**: Data cleaning, preprocessing, sentiment tagging
- **Power BI**: Visual analytics and dashboards
- **Pandas, Matplotlib, Seaborn**: Python libraries used
- **GitHub**: Version control and documentation

## 📊 Power BI Visualizations
Visuals include:
1. Sum of Likes by Platform
2. Top 10 Sentiments (e.g., Joy, Gratitude)
3. Count of Sentiment Types
4. Hashtags by Retweet Counts
5. Geographic Distribution of Posts
6. Likes/Retweets by Country
7. Platform Engagement Trends over Time

You can find these visuals in the `visuals/` folder.

## 📈 Key Findings
- **Instagram** received the most likes overall, followed by Twitter and Facebook.
- The most common sentiments were **Positive**, **Joy**, and **Excitement**.
- The hashtag **#Wonder #Star...** was most retweeted, especially on Facebook.
- **USA**, **UK**, and **Canada** had the highest social media activity in terms of likes and retweets.
- Engagement has seen a gradual rise year over year, especially on **Instagram**.

## 📎 File Structure
data/: Dataset used for analysis

notebooks/: Python notebook for data processing

visuals/: Power BI dashboard images

reports/: Detailed report in Markdown format

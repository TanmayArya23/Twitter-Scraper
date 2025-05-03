# 🐦 Tweepy Twitter Scraper

## 🔍 Overview

**Tweepy** is a powerful Python library that allows users to access and fetch real-time Twitter data via the Twitter API. This project utilizes Tweepy to build a **Twitter scraping system** for **market and trend analysis** based on hashtags.

Key Highlights:
- Extracted tweets based on user-defined hashtag queries
- Stored results in a CSV file
- Analyzed tweet data using Python libraries to identify patterns and sentiment
- Presented insights visually using tables and plots

---

## 💡 Motivation

Social media, particularly Twitter, has become a crucial platform for:
- Monitoring trends
- Analyzing customer feedback
- Tracking competition

However, **manual tracking is inefficient**. Tweepy offers an automated and scalable approach to collect and analyze tweet data — enabling businesses and analysts to make data-backed decisions.

> 🏢 *63% of the world's top brands operate multiple Twitter accounts*

---

## 📚 Literature Review

- Tweepy is widely adopted in academic and business communities for social media mining.
- It integrates seamlessly with Python’s data stack (Pandas, Matplotlib, etc.).
- Compared to small surveys or intuition, Twitter scraping offers a scalable and cost-effective way to capture real-time public sentiment and behavior.

---

## 🧩 Problem Statement

The project aims to:
- Build a system to **fetch tweets** based on hashtags using the Twitter API
- Store and **analyze the tweets** using Python libraries
- Use the insights for **market and trend analysis**

> 📊 Traditional methods like intuition or surveys yield limited and potentially biased results. Real-time tweet analysis can bridge this gap.

---

## 🧰 Tools & Technologies Used

| Tool        | Purpose                                       |
|-------------|-----------------------------------------------|
| **Python**  | Primary programming language                  |
| **Tweepy**  | To fetch tweets via Twitter API               |
| **SQLite**  | To store fetched tweets in a local database   |
| **SQLite3** | Python’s built-in module for SQLite integration |
| **Twitter Developer API** | To generate API keys for authentication |

---

## 🗂️ Dataset

- **Source:** Real-time tweets via Twitter API
- **Storage:** `tweetsDatabase.db` (SQLite format)
- **Fields Stored:**  
  - Hashtag used in query  
  - Full text of each tweet  

> 🌍 *450 million monthly active Twitter users globally*  
> 💬 *93% of users who follow a brand on Twitter intend to purchase from them*

---

## 🔁 Methodology

### 🧪 Steps:
1. Create a Twitter Developer account and generate API keys  
2. Install and configure the Tweepy library  
3. Define search query (hashtag-based)  
4. Fetch and store tweets into a `.csv` file  
5. Use Python libraries to clean, filter, and analyze the data  
6. Visualize trends and patterns  


---

## 📈 Results

- Fetched and analyzed tweets revealed patterns such as:
  - Popular hashtags
  - Tweet frequency by region
  - Engagement metrics (likes, retweets)
  - Commonly used terms and sentiments
- Insights presented via tables and visualizations (bar charts, pie charts, word clouds)

> 📣 *21 million+ users contributed to the analyzed data*

---


## 👨‍💻 Author

**Tanmay Arya**  
🎓 Duke University – MQM '26  
📊 Passionate about Data Analytics, Python, and Digital Trends



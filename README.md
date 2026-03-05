# Jobaaj_Learning_SQL_Instagram_User_Analytics
This README provides a comprehensive overview of the **Instagram User Analytics** project, which uses SQL to derive business insights for marketing and investor relations teams.

---

# Instagram User Analytics

## 📌 Project Overview

This project involves a deep dive into an Instagram-clone database to track user engagement and interaction. By analyzing patterns in user signups, photo uploads, and likes, the project provides actionable insights that help marketing teams launch targeted campaigns and help investors understand the platform's long-term viability.

## 🗂️ Case Studies

### 1. Marketing Analysis

Focused on identifying user loyalty and optimizing the timing of promotional activities.

* **Loyal User Reward**: Identified the top 5 oldest users based on their registration date to reward long-term loyalty.
* **Inactive User Engagement**: Found users who have never posted a single photo, providing a target list for re-engagement campaigns.
* **Contest Winner**: Identified the user who uploaded the most-liked photo in a single contest.
* **Hashtag Research**: Ranked the top 5 most commonly used hashtags to help partners reach maximum audience visibility.
* **Ad Campaign Optimization**: Analyzed which days of the week have the highest registration rates to determine the best launch window for advertisements.

### 2. Investor Metrics

Focused on the health of the platform and the authenticity of its user base.

* **User Engagement**: Calculated the average number of posts per user (Total Photos / Total Users).
* **Bot & Fake Account Detection**: Developed queries to identify "super users" who have liked every single photo on the site—a behavior typical of bots and fake accounts.

## 🛠️ Tech Stack

* **Database**: MySQL Workbench 8.0
* **Concepts**: Joins, Subqueries, CTEs (Common Table Expressions), Aggregate Functions, Date/Time Functions.
* **Reporting**: Microsoft PowerPoint.

## 📊 Key Insights

* **Oldest Users**: Identified the "Founding" members of the platform for a loyalty reward program.
* **Platform Health**: Determined the ratio of photos to users to measure content creation frequency.
* **Ad Strategy**: Discovered the peak registration day, allowing the marketing team to schedule ad spend more efficiently.
* **Bot Mitigation**: Isolated accounts showing inorganic liking patterns to ensure platform integrity for advertisers.

## 📖 How to Use

1. **Database Creation**: Run the `Instagram User Analytics.sql` script in MySQL Workbench to initialize the `ig_clone` database and populate the tables (Users, Photos, Comments, Likes, Follows, Tags).
2. **Run Queries**: Each section of the SQL file is labeled with the specific business question it answers.
3. **Review Findings**: Open the `Instagram User Analytics.pptx` presentation for a visual summary of the data, including charts for hashtags and user activity levels.

---

*This project serves as a portfolio piece for social media analytics, demonstrating proficiency in relational database management and business intelligence.*

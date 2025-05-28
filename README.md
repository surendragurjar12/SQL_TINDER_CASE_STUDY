# Tinder Case Study – SQL Analysis Project

This project simulates a Tinder-like application using SQL. It includes user profiles, interests, swipe interactions, and match generation. The dataset is fully synthesized with fictional users (inspired by pop culture characters) to perform behavioral analysis.

## 🗃️ Schema Overview

- **users**: Basic profile info (name, age, gender, plan).
- **interests**: List of predefined interests.
- **user_interests**: Many-to-many mapping between users and interests.
- **swipes**: Records of swiping actions (like/dislike).
- **matches**: Mutual likes result in a match.

## 🧪 Key Features

- Inserted data for **25 users** with diverse interest sets.
- Simulated **swipe activity** with realistic interaction logic.
- Generated **mutual matches** using SQL joins.
- Designed to support behavioral, preference, and engagement analytics.

## 🛠️ Tools Used

- MySQL or compatible RDBMS
- SQL DDL and DML
- Joins, ENUMs, and timestamps

## 🚀 How to Run

1. Open a MySQL-compatible SQL client.
2. Run the full SQL script:
   ```sql
   SOURCE SQL_TINDER_CASE_STUDY.sql;


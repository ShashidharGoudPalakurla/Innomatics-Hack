# Innomatics-Hack
#Multi-source food delivery data merged into one analytics-ready dataset.
🍽️ Food Delivery Data Integration & Analytics Dataset
📌 Project Overview

This project demonstrates a real-world data engineering workflow by integrating multiple data sources—CSV, JSON, and SQL—into a single analytics-ready dataset. The final dataset acts as a single source of truth for exploratory data analysis, SQL querying, dashboards, and hackathon-style problem solving.

The project simulates how modern food delivery platforms manage orders, users, and restaurants across heterogeneous systems.

🗂️ Data Sources

The project combines three different data formats commonly found in production systems:

orders.csv – Transactional order-level data

users.json – User master data (demographics & membership)

restaurants.sql – Restaurant master data (cuisine, ratings, location)

Each dataset represents an independent system and is merged using relational keys.
🔗 Data Integration Logic

Joins are performed using LEFT JOINs to ensure no order data is lost.

Source	Key	Target
orders → users	user_id	user_id
orders → restaurants	restaurant_id	restaurant_id

This approach mirrors real-world ETL pipelines used in analytics and BI systems.
📁 Final Output

📄 final_food_delivery_dataset.csv

Dataset Features:

10,000+ order records

User membership segmentation (Gold vs Regular)

City-wise and cuisine-wise insights

Restaurant ratings and performance metrics

This dataset is ready for analysis using:

SQL

Pandas

Power BI / Tableau

Hackathons & case studies
📊 Key Analysis Possibilities

Students and analysts can explore:

📈 Order trends and seasonality

👥 User behavior and retention

🌍 City-wise & cuisine-wise performance

💎 Membership impact on revenue

💰 Revenue distribution across restaurants
🧠 Learning Outcomes

This project helps learners understand:

Multi-format data ingestion

SQL + Python integration

ETL concepts and joins

Building a single source of truth

Real-world analytics workflows
🚀 Use Cases

Data Engineering practice

Data Analytics hackathons

SQL & Python assignments

Portfolio / resume projects

Mini capstone project

🛠️ Tech Stack

Python

Pandas

SQLite

CSV / JSON / SQL
📜 License

This project is intended for educational and learning purposes.

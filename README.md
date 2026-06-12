Instagram Database Building 📸🗄️

This project focuses on designing and building a structured database system for an Instagram-like social media platform. It includes creating relational database schemas, defining entity relationships, and implementing core functionalities such as user profiles, posts, likes, comments, followers, and messaging.

📌 Project Objectives

Design an efficient relational database for a social media platform.
Create tables for users, posts, comments, likes, and followers.
Establish relationships between entities using foreign keys.
Implement normalization to reduce redundancy.
Simulate real-world Instagram database operations.
🛠️ Tech Stack
SQL
MySQL / PostgreSQL
Database Design (ER Diagrams)
Normalization Techniques

📂 Database Structure

The database consists of the following main tables:

Users – Stores user profile details.
Posts – Contains uploaded posts (images/videos, captions).
Comments – Stores user comments on posts.
Likes – Tracks likes on posts.
Followers – Manages follower-following relationships.
Stories – Stores temporary stories.
Messages – Handles direct messaging between users.
Hashtags – Stores hashtags used in posts.
🔗 Entity Relationships
One user can create multiple posts.
One post can have multiple likes and comments.
Users can follow multiple users (many-to-many).
Users can send and receive messages.

🚀 Workflow

Requirement analysis
Database schema design
ER diagram creation
Table creation with constraints
Insert sample data
Query execution and testing

📊 Sample SQL Queries

Includes:

Fetch user posts
Count total likes per post
Find top-followed users
Retrieve comments on a specific post
Show mutual followers

🎯 Conclusion

This project demonstrates the foundation of building a scalable social media database system by modeling real-world Instagram functionalities and optimizing data storage for efficient querying.

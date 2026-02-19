# Relational Database Design & Querying – Video Club Platform

This project demonstrates the design, implementation, and querying of a fully relational movie database system using SQL.

---

## Project Objective

To design and implement a normalized relational database for a video streaming platform and perform analytical queries to extract business insights.

---

## Database Design

The database includes the following entities:

- Actor
- Director
- Movies
- Category
- User
- MoviesRating
- Cast
- Direction
- History

Primary and foreign keys were implemented to ensure referential integrity.

An Entity-Relationship (ER) model was developed to define relationships between entities.

---

## Schema Implementation

- Table creation with constraints (PRIMARY KEY, FOREIGN KEY)
- Data insertion scripts
- Many-to-many relationships (Cast, Direction)
- Transaction history tracking

---

## Querying & Analysis

The project includes SQL queries demonstrating:

- Aggregation (COUNT, AVG, SUM)
- Filtering (WHERE conditions)
- GROUP BY and HAVING clauses
- INNER JOIN and LEFT JOIN
- Subqueries
- Detection of missing ratings
- User activity analysis
- Category-based movie filtering

Example analyses:

- Count actors born after 1990
- Retrieve actors participating in a specific movie
- Identify directors with multiple movies
- Compute average rating for a movie
- Detect users who watched movies but did not rate them
- Identify highly active vs minimally active users

---

## Tools Used

- SQL (SQLite)
- Relational modeling
- ER diagram design
- Constraint enforcement

---


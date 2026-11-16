# Mario Character Relational Database

A normalized PostgreSQL database modeling characters, detailed profiles, actions, and relationships from the Super Mario universe. Built as part of the **freeCodeCamp Relational Databases** curriculum.

## Database Schema & Key Concepts
* **Relational Normalization:** Structured across multiple related tables (`characters`, `more_info`, `sounds`, `actions`, and `character_actions`) to eliminate data redundancy.
* **Constraints & Keys:** Enforces data integrity using `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, and `NOT NULL` constraints, including one-to-one, one-to-many, and many-to-many junction relationships.

## How to Restore the Database
To recreate this database locally in PostgreSQL, run:
```bash
psql -U postgres < mario_database.sql
```

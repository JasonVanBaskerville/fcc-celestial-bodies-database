# Celestial Bodies Database

A PostgreSQL database project that models celestial bodies and their relationships in the universe.

## Database Structure

The database contains five main tables:

- `galaxy_type` — stores different types of galaxies.
- `galaxy` — stores galaxy information and its type.
- `star` — stores stars and the galaxies they belong to.
- `planet` — stores planets and the stars they orbit.
- `moon` — stores moons and the planets they orbit.

The relationships between the tables are connected using **primary keys** and **foreign keys**:

```text
galaxy_type → galaxy → star → planet → moon
```

## Main SQL Concepts

This project demonstrates:

- Creating databases and tables
- Defining primary keys and foreign keys
- Using `UNIQUE` constraints
- Using different data types such as `integer`, `boolean`, `text`, `varchar`, and `numeric`
- Creating sequences for automatically generated IDs
- Inserting data using `INSERT INTO`
- Establishing relationships between tables

The database is named `universe` and contains sample data representing galaxies, stars, planets, and moons.

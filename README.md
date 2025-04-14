# PostgreSQL Query Practice

This repository contains SQL query files and result logs from working with PostgreSQL databases as part of a learning project.

## Databases Included

### 📁 playstore
- `queries.sql`: Query script for analyzing app data
- `results.txt`: Output from executing the query file

### 📁 products
- `products_queries.sql`: Inserts, selects, updates, and deletes for product inventory
- `products_results.txt`: Query output after transformations

## How to Run

1. Connect to the appropriate database in `psql`
2. Run query file with:

```sql
\o /tmp/results.txt
\i /home/tmr/products_queries.sql
\o

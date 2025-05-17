# NYC Taxi Data Analysis

This project analyzes NYC Yellow Taxi trip data (January 2023) with Python and SQLite.  
It generates multiple insightful visualizations and saves them in a single PDF file.

## Features

- Loads a large dataset directly from an online Parquet file  
- Cleans and preprocesses data  
- Stores data in SQLite  
- Creates 5 different visualizations covering trip counts, fares, payment types, trip distances, and day-of-week trends  
- Saves all visualizations into one combined PDF file `NYC Taxi Data Analysis.pdf`  

## Requirements

- Python 3.x  
- pandas  
- matplotlib  
- pyarrow (for reading Parquet files)  
- sqlite3 (built-in with Python)  

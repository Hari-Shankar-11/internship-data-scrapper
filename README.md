# Internshala Data Analyst Internship Scraper

This is a beginner Python project that collects Data Analyst internship
listings from Internshala and stores them in a SQLite database.

The project demonstrates a simple ETL process using Python.

## Project Overview

This project performs three basic steps:

### Extract
- Scrapes internship data from Internshala using BeautifulSoup

### Transform
- Cleans the data
- Handles missing values
- Adds the date when the data was scraped

### Load
- Saves the cleaned data into a SQLite database

## Tools Used

- Python
- BeautifulSoup
- Pandas
- SQLite3


## Files in this Repository

- `etl_scraper_internshala.ipynb` – Jupyter notebook containing the scraping and data processing code
- `internshala_jobs.db` – SQLite database generated from the pipeline
- `requirements.txt` – Python dependencies needed to run the project

# How to run
1. Clone the repo: `git clone https://github.com/Hari-Shankar-11/etl-job-pipeline`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `etl_scraper_internshala.ipynb` in Jupyter and run all cells

# Dataset
- Source: Internshala (live scraped)
- Records: 40 Data Analyst internships
- Fields: Title, Company, Location, Duration, Stipend

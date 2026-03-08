# ETL Pipeline – Internshala Data Analyst Internships

An automated Extract → Transform → Load pipeline that scrapes
live Data Analyst internship postings from Internshala, cleans
the data, and stores it in a SQLite database.

## What it does
- **Extract**: Scrapes job title, location, duration and stipend from Internshala
- **Transform**: Cleans missing values, standardises formats, adds scrape date
- **Load**: Stores structured data in a SQLite database

## Tools Used
| Library | Purpose |
|---|---|
| `requests` | Fetch web pages |
| `beautifulsoup4` | Parse HTML and extract data |
| `pandas` | Clean and transform data |
| `sqlite3` | Load data into database |
| `csv` | Read/write CSV files |
| `datetime` | Add scrape timestamps |

## How to Run
1. Clone the repo: `git clone https://github.com/Hari-Shankar-11/etl-job-pipeline`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `etl_scraper_internshala.ipynb` in Jupyter and run all cells

## Dataset
- Source: Internshala (live scraped)
- Records: 40 Data Analyst internships
- Fields: Title, Company, Location, Duration, Stipend

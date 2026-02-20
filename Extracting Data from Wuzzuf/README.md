# Wuzzuf Job Scraper 
A Python-based web scraping tool designed to extract job listings from the Wuzzuf recruitment platform. This project automates the process of gathering job data, including titles, companies, locations, and specific requirements, saving them into a structured CSV format for further analysis.

# Project Overview
The scraper targets "Data Analyst" positions (or any specified search query) and navigates through the search results to extract key information. It handles multi-step extraction by visiting both the search result page and individual job detail pages to get the full requirements.

# Built With
- Python: The core programming language.
- Requests: To send HTTP requests and fetch page content.
- BeautifulSoup4: For parsing HTML and navigating the DOM tree.
- CSV & Itertools: For data structuring and exporting results.

# Features
- Full Data Extraction: Captures job titles, company names, locations, and post dates.
- Deep Scraping: Follows job links to extract detailed job requirements and salary information.
- Arabic Support: Uses utf-8-sig encoding to ensure Arabic text and symbols display correctly in Excel.
- Clean Data: Strips unnecessary whitespace and joins skill tags into a readable string.

# Extracted Columns
The output CSV (Data Analysts Jobs.csv) contains the following columns:
- Posted Date: When the job was listed.
- Job Title: The name of the position.
- Company Name: The hiring organization.
- Location: The office location or city.
- Skills: Key technical and soft skills required.
- Links: The direct URL to the job posting.
- Salaries: Compensation details (where available).
- Requirements: Full text of job qualifications and duties.

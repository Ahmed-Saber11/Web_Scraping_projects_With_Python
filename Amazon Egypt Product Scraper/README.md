# Amazon Egypt Product Scraper
A high-performance web scraping tool built with Python, Selenium, and BeautifulSoup. 
This project automates the process of searching for products on Amazon Egypt, navigating multiple pages, and extracting detailed product information into a structured CSV format.

---

# Overview
This scraper is designed to overcome common scraping challenges such as dynamic content loading (Lazy Loading) and anti-bot detection. By mimicking human browsing behavior through automated scrolling and custom headers, it successfully extracts data from up to 10 pages per search query.

---

# Key Features
- Automated Pagination: Navigates through result pages using the Next button until the target page or the end of results is reached.
- Smart Scrolling: Uses a JavaScript-based incremental scroll to trigger Amazon's Lazy Loading, ensuring prices and titles are fully rendered.
- Anti-Bot Bypass: Implements custom User-Agent strings and disables automation flags to avoid being blocked.
- Excel-Ready Export: Generates a CSV file using utf-8-sig encoding to ensure Arabic characters and currency symbols display correctly in Excel.

---

# Technical Stack
- Language: Python 3.12
- Automation: Selenium WebDriver
- Parsing: BeautifulSoup 4
- Data Management: Pandas
- Driver Management: WebDriver Manager

--

# Project Structure
- Extracting Products from Amazon.ipynb: The main Jupyter Notebook containing the logic.
- amazon_results.csv: The output file generated after running the script.
- README.md: Project documentation.

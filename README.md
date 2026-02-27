# Amazon Web Scraper Project

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A **Python-based web scraper** that extracts product details from Amazon and stores them in a CSV file. This project allows you to track product information over time and optionally receive email notifications when a product price drops below a specified threshold. Ideal for personal analytics, portfolio projects, and learning web scraping techniques.  

---

## Features

- Scrapes **product Title**, **Color**, and **Fit Type** for apparel items.  
- Records the **date of scraping** automatically.  
- Saves data into a **CSV file** (`AmazonWebScraperDataset.csv`) for easy tracking and analysis.  
- Optional **email notifications** when a product price drops below a set threshold.  
- Handles product variations such as color, size, and fit type.  
- Can be scheduled to run periodically to track changes over time.  

---

## Technologies Used

- **Python 3**  
- `requests` – for HTTP requests  
- `BeautifulSoup` – for parsing HTML content  
- `csv` – for storing scraped data  
- `datetime` – for timestamps  
- `smtplib` – for sending email alerts  

---

## Installation

1. Clone this repository:

git clone https://github.com/YourUsername/Amazon-Web-Scraper.git

2.Install the required packages:

pip install requests beautifulsoup4

3.Data will be saved/appended to AmazonWebScraperDataset.csv.

CSV Output

The CSV file contains the following columns:

Column	Description
Title	Name of the product
Color	Selected color of the product
Fit Type	Selected fit type (e.g., Men/Women)
Date	Date of scraping
Notes

This project is intended for educational purposes and personal use.

Amazon may dynamically load some data via JavaScript. For fully dynamic pages, Selenium may be required.

Always comply with Amazon’s Terms of Service when scraping data.

Future Improvements

Track multiple products simultaneously.

Record additional attributes such as price, ratings, and availability.

Integrate scheduling with cron or Windows Task Scheduler.

Use Selenium for handling JavaScript-rendered content and dynamic price tracking.

Implement robust error handling for blocked requests or network failures.

License

This project is licensed under the MIT License. See the LICENSE
 file for details.

Author

Kareeb Sadab

Email: kareebsadab@gmail.com

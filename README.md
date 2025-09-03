🏠 Real Estate Web Scraper

This project is a Python-based web scraping tool built using Selenium and BeautifulSoup to extract property listing data (such as name, location, price, area, and BHK) from real estate websites like 99acres or Magicbricks. The scraper navigates through multiple pages, extracts structured property data, and stores it in a DataFrame or CSV format for further analysis.


📦 Features

✅ Automatically scrolls and navigates through paginated listings

✅ Extracts key property details:

Property Name

Location

Price

Area (sqft)

BHK (Bedrooms)

✅ Handles edge cases where some details may be missing or displayed in alternative HTML classes

✅ Includes fallback logic for extracting area/BHK from multiple class selectors

✅ Saves all data into a structured format (list of dicts or CSV)


🛠️ Tech Stack

Python 3.x

Selenium

BeautifulSoup

NumPy

Pandas

Chrome WebDriver

follow the requirements.txt file for the rest of the stack

⚠️ Legal Notice

This project is intended for educational purposes only. Please ensure you respect a website’s robots.txt and terms of service before scraping.

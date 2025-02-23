# Web Scraping Project

## Description
This project is designed to scrape company websites to extract contact information such as email addresses and phone numbers. It utilizes Python along with web scraping libraries to automate data extraction and processing.

## Features
- Scrapes company websites for email addresses and phone numbers
- Uses BeautifulSoup and requests for parsing web pages
- Can handle multiple websites efficiently
- Saves extracted data into a structured format

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.8 or later
- Required Python libraries (see Installation section)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/bora-arda/web-scraper.git
   cd web-scraper
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

## Usage
1. Add the target companies to an Excel file and fill the neccessary spaces in the code that are specified for Excel files.
2. Run the script:
   ```bash
   python main.py
   ```
3. Extracted data will be saved in the Excel file you specified.

## Configuration
- Modify `main.py` to adjust scraping parameters such as user agents, request delays, and HTML parsing rules.
- Use a proxy or headers to avoid getting blocked by websites.

## Legal Notice
Ensure that you comply with each website's terms of service before scraping. Unauthorized data extraction may violate legal policies.

## License
This project is licensed under the MIT License.


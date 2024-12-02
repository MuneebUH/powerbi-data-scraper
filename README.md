# Power BI Data Scraper

This repository contains a Python script that uses Selenium to scrape data from a Power BI report and save it into a CSV file. The script interacts with the Power BI web page, navigates through the report, clicks dropdowns, and extracts specific data.

## Requirements

- Python 3.x
- Selenium
- WebDriver Manager
- Pandas
- Microsoft Edge WebDriver

## Setup

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/yourusername/powerbi-data-scraper.git

```

### 2. Navigate to the Project Directory
Change to the project directory:
```
cd powerbi-data-scraper
```
### 3. Install Dependencies
Make sure you have all the required libraries installed. Run the following command to install them using pip:
```
pip install selenium webdriver_manager pandas
```
4. Run the Script
Now, you can run the scraper script but before that modify it accordingly. This will open the Power BI report in the Edge browser, navigate through the report, and scrape the relevant data:
```
python powerbi_scraper.py
```

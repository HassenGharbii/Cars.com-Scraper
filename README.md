# Cars.com-Scraper
The Cars.com Scraper is a Python script designed to extract car information, ratings, breakdowns, and user reviews from the cars.com website. It automates the process of collecting data about different car makes, models, and years, along with their associated reviews.
## How It Works
1.The script uses the Selenium library to automate web browsing. It launches a web browser, navigates to the provided cars.com URL, and extracts data using various XPATHs and class names.</br>
2.The script iterates through available car makes, models, and years to gather information for each combination.</br>
2.It stores the extracted data, including ratings, recommended percentages, breakdowns, and reviews, in a JSON file.</br>
## Features
Scrapes car information, ratings, breakdowns, and user reviews from cars.com.</br>
Stores scraped data in JSON format for later analysis.</br>
Supports skipping already scraped cars based on a saved file.</br>

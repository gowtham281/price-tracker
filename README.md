# Flipkart Scraper and Price Comparison Script

## Overview
This Python script performs the following tasks:
1. Utilizes the requests and BeautifulSoup libraries to scrape product information from Flipkart.
2. Connects to a MySQL database to store and compare product prices.

## Functionality
1. Search Flipkart: Takes a product name input, searches Flipkart, and retrieves the title and price of the first result.

2. Scrape Product Info: Extracts product details such as title and price from a given Flipkart product page.

3. Price Comparison: Compares the scraped price with the stored price in the MySQL database, calculating and displaying the price difference.

4. Database Interaction: Checks if the product is already in the database, updates it if present, or inserts a new entry.

5. Output and Logging: Displays relevant information and writes the price difference to a 'price_difference.txt' file.

## Database Configuration
- Host: localhost
- User: root
- Password: 1234
- Database: engine => (If you want change  )

## Execution
1. Run the script and enter a product name when prompted.
2. Retrieves and displays Flipkart product information.
3. Compares prices with the stored value in the MySQL database.
4. Outputs results and writes price difference to 'price_difference.txt'.

## Dependencies
- requests
- BeautifulSoup
- mysql.connector

## Note
Ensure the MySQL database is set up with the specified configuration before running the script.

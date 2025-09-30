# Web-Scraping

## Introduction
This project features a Python script that utilizes BeautifulSoup for web scraping product data from Amazon's PS5 product page. The script extracts various details, including the product title, price, rating, availability, and customer reviews. It handles missing data gracefully, ensuring robustness during the scraping process.

## Features
Product Title: Grabs the title of the PS5.
Price Extraction: Retrieves the current price of the product.
User Ratings: Extracts the product rating from customer reviews.
Availability Status: Indicates whether the item is in stock.
Customer Reviews: Gathers user feedback, ratings, and comments.

## HTML Element Extraction
The script precisely locates and parses specific HTML elements to extract relevant information using CSS selectors.

## Error Handling and Defaults
To ensure smooth execution, the script includes error handling to manage missing data scenarios while scraping.

## Product Information Extraction
Key data points are retrieved as follows:
Title: Extracted using a unique CSS selector.
Price: Captured despite potential changes in the product page structure.
Rating: Retrieved and formatted appropriately.
Availability: Clearly indicates stock status.




# Ecommerce Web Scraping Project

This project consists of two web scraping tasks aimed at extracting product and review data from Amazon. Each task is performed in separate Jupyter notebooks, and the data is saved to CSV files for further analysis.

## Notebooks Overview

### 1. Web Scraping Products
This notebook scrapes details for products from Amazon and stores the data in a CSV file.

#### Key Features:
- Extracts product information such as name, price, and ratings.
- Stores the scraped data in a structured CSV format.
- Includes error handling for unavailable or restricted data.

### 2. Web Scraping Product Reviews
This notebook scrapes reviews for a specified product from Amazon and stores the data in a CSV file.

#### Key Features:
- Extracts review details including the reviewer's name, rating, and review text.
- Collects multiple pages of reviews if available.
- Saves the scraped reviews into a CSV file for easy analysis.

## Requirements

- Python 3.x
- Required Libraries:
  - `requests`
  - `BeautifulSoup`
  - `pandas`
  - `csv`
  - `time`

To install the required libraries, run the following or install from "requirements.txt" file:

```bash
pip install requests beautifulsoup4 pandas
```

## Usage

### 1. Run the Notebooks

Download and open the notebooks `amz_prod.ipynb` and `amz_rev.ipynb` in Jupyter.

### 2. Modify Product URLs or Review Targets

- For product scraping, input the Amazon search page URL in the designated cell.
- For review scraping, specify the product page for which reviews should be scraped.

### 3. Output

- The product scraping notebook generates a CSV file with product details.
- The review scraping notebook generates a CSV file with user reviews.

## Disclaimer
This project is intended for educational purposes. Please adhere to website's terms of service and scraping guidelines.

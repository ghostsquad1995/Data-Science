## Project Description:
This project involves scraping product data from Flipkart and Lazada websites, saving the information in CSV files, and then combining the top 5 products from both CSV files into a final CSV file.

### Problem Statement:
1. Scrape product data from Flipkart and Lazada.
2. Save the product info in CSV files.
3. Sort the data in descending order based on price.
4. Concatenate the data showing the top 5 products from both CSV files into a final CSV file.

### Data Columns:
- `productName`
- `productPrice`
- `productDesc`
- `productImg`
- `productBuyLink`


### Files Description:
1. **flipkart_scraper.py**: Contains the code for scraping product data from Flipkart.
2. **lazada_scraper.py**: Contains the code for scraping product data from Lazada.
3. **final_combined.csv**: The final combined CSV file containing the top 5 products from both Flipkart and Lazada.
4. **FlipKart_Product_Data.csv**: Contains the scraped product data from Flipkart.
5. **Lazada_Product_Data.csv**: Contains the scraped product data from Lazada.
6. **README.md**: This file.

## Prerequisites:
- Python 3.x
- pandas
- numpy
- selenium
- BeautifulSoup4
- Requests

---

This README provides a comprehensive guide to understanding and using the product scraper for Flipkart and Lazada.

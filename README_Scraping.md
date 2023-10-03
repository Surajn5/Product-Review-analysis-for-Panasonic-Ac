## Introduction

This Python script is designed to scrape reviews and feature data for the product "Panasonic AC 1.5 ton 3 star rated" from the Flipkart website. It extracts information such as product ratings, review summaries, reviews, review locations, review dates, review upvotes, and review downvotes.

## Requirements

To run this script, you need to have the following libraries installed:

- `requests`
- `pandas`
- `BeautifulSoup` (from the `bs4` package)

You can install these libraries using pip:
pip install requests pandas beautifulsoup4
## Usage

1. Set the URL variable to the Flipkart product page you want to scrape. Make sure it points to the product's review section.

2.Run the script, and it will start scraping reviews and feature data from multiple pages. The script is currently set to scrape reviews from pages 2 to 221 (inclusive).

3.The scraped data will be stored in a Pandas DataFrame.

4.The scraped data is organized in a Pandas DataFrame named df_reviews. You can use this DataFrame to analyze and work with the scraped data further.

##Note
Make sure to abide by Flipkart's terms of service and respect their scraping policy while using this script.
You may need to adjust the code if the HTML structure of the Flipkart website changes in the future.


Author
Suraj N







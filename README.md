# web_scrape_challenge

This project consists of two technical products:

1. Scrape titles and preview text from Mars news articles.
2. Scrape and analyze Mars weather data, which exists in a table.

Part 1: Scrape Titles and Preview Text from Mars News
* Use automated browsing to visit the Mars news site.
* Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to extract text elements from the website.
* Extract the titles and preview text of the news articles.
* Store each title-and-preview pair in a Python dictionary.
* Store all the dictionaries in a Python list.

Part 2: Scrape and Analyze Mars Weather Data
* Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
* Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to scrape the data in the HTML table.
* Assemble the scraped data into a Pandas DataFrame.
* Cast (or convert) the data to the appropriate datetime, int, or float data types.
* Analyze your dataset by using Pandas functions to answer the following questions:
  1. How many months exist on Mars?
  2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  4. Which months have the lowest and the highest atmospheric pressure on Mars?
  5. About how many terrestrial (Earth) days exist in a Martian year?
* Export the DataFrame to a CSV file.

**References**<br>
The Mars News website is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.

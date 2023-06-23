# Mars Data Scraping and Analysis

This project aims to scrape and analyze Mars data using web scraping techniques and data analysis with Python. The project consists of two parts:

- Part 1: Scrape and analyze the latest news articles about Mars from a news website.
- Part 2: Scrape and analyze Mars weather data.

## Part 1: Scrape and Analyze Mars News Articles

### Instructions

1. Use automated browsing to visit the Mars News website.
2. Inspect the page to identify the HTML elements that contain the news article titles and summaries.
3. Create a Beautiful Soup object and use it to extract the news article titles and summaries.
4. Optionally, store the scraped data in a file (e.g., JSON).

### Completed Code

You can find the completed code for Part 1 in the file [part_1_mars_news.ipynb](part_1_mars_news.ipynb). The code includes the following steps:

1. Import the necessary libraries: `requests` for making HTTP requests, `BeautifulSoup` for parsing HTML, and `json` for working with JSON data.
2. Send an HTTP GET request to the Mars News website and retrieve the HTML content.
3. Create a Beautiful Soup object and use it to extract the news article titles and summaries.
4. Optionally, store the scraped data in a JSON file.

## Part 2: Scrape and Analyze Mars Weather Data

### Instructions

1. Use automated browsing to visit the Mars Temperature Data website.
2. Inspect the page to identify the HTML elements that contain the temperature data.
3. Create a Beautiful Soup object and use it to scrape the temperature data in the HTML table.
4. Assemble the scraped data into a Pandas DataFrame.
5. Analyze the dataset using Pandas functions to answer specific questions.
6. Optionally, plot the results using Matplotlib.
7. Export the DataFrame to a CSV file.

### Completed Code

You can find the completed code for Part 2 in the file [part_2_mars_weather.ipynb](part_2_mars_weather.ipynb). The code includes the following steps:

1. Import the necessary libraries: `splinter` for automated browsing, `BeautifulSoup` for parsing HTML, `matplotlib.pyplot` for data visualization, and `pandas` for data analysis.
2. Use automated browsing to visit the Mars Temperature Data website.
3. Create a Beautiful Soup object and use it to scrape the temperature data from the HTML table.
4. Assemble the scraped data into a Pandas DataFrame.
5. Analyze the dataset using Pandas functions to answer specific questions, such as the number of months on Mars, the number of Martian days' worth of data, the coldest and hottest months on Mars, the months with the lowest and highest atmospheric pressure, and the number of terrestrial days in a Martian year.
6. Plot the results using Matplotlib.
7. Export the DataFrame to a CSV file.

## Conclusion

This project demonstrates how to scrape and analyze Mars data using Python. By following the instructions and running the provided code, you can extract the latest news articles about Mars and retrieve and analyze Mars weather data. The code can be further extended and customized to gather additional information or perform more in-depth analysis.

Feel free to explore and modify the code to suit your specific needs and interests. Happy exploring Mars data!

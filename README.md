# Mars Web Scraping and Data Analysis Project

## Overview

This project involves web scraping data related to Mars from various sources, performing data analysis on the scraped data, and visualizing the findings. It consists of two main deliverables:

1. **Scrape Titles and Preview Text from Mars News**
   - Use automated browsing with Splinter to visit a Mars news website.
   - Utilize Beautiful Soup for HTML parsing and data extraction.
   - Store titles and preview text of news articles in Python data structures.
   - Export the scraped data to a JSON file (optional).

2. **Scrape and Analyze Mars Weather Data**
   - Automate browsing to visit a Mars temperature data site.
   - Extract data from an HTML table using Beautiful Soup.
   - Assemble the scraped data into a Pandas DataFrame.
   - Analyze the dataset to answer questions about Martian weather.
   - Visualize the data using matplotlib.

## Project Structure

The project consists of two Jupyter Notebooks:

1. `part_1_mars_news.ipynb`: This notebook focuses on scraping titles and preview text from Mars news articles.

2. `part_2_mars_weather.ipynb`: This notebook involves scraping and analyzing Mars weather data.

## Dependencies

This project relies on the following Python libraries and tools:

- Splinter: For automated web browsing.
- Beautiful Soup: For HTML parsing and data extraction.
- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization.
- Jupyter Notebook: For creating and running Python notebooks.

Make sure to install these dependencies using pip or your preferred package manager before running the notebooks.

## Instructions

To replicate and explore this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies.
3. Open and run the Jupyter Notebooks in the following order:
   - `part_1_mars_news.ipynb`
   - `part_2_mars_weather.ipynb`
4. Follow the code and instructions within each notebook to scrape and analyze the Mars data.
5. Visualize the results and observe the findings.

## Final Analysis

The analysis of the scraped Mars data has yielded several key findings:

- **Mars News Articles:** The project successfully scraped titles and preview text from Mars news articles, providing insights into recent developments on Mars.

- **Mars Weather Analysis:** The analysis of Mars weather data revealed average temperatures by month, allowing us to identify the coldest and hottest months at the Curiosity rover's location. Additionally, we analyzed atmospheric pressure trends by month.

- **Martian Year:** A visual representation showed that there are approximately 687 Earth days in a Martian year.

These findings enhance our understanding of Mars and its weather patterns, which can be valuable for future missions and research.

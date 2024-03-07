# data-collection-challenge
Module 11 Challenge - Data Collection

### Files in this repository include:
1. part_1_mars_weather.ipynb - provided as starter code to cover "Part 1: Scrape Titles and Preview Text from Mars"
2. part_2_mars_weather.ipynb - provided as starter code to complete "Part 2: Scrape and Analyze Mars Weather Data"
3. "mars_weather.csv" is the saved data from Part 2.

### Part 1: Scrape Titles and Preview Text from Mars News
1. Scrape the text from the "Mars Facts" site.
2. Extracted the titles and preview text then stored into dictionary.
3. Stored a list of the dictionaries created into a list. (made sure to close the browser before exiting)

### Part 2: Scrape and Analyze Mars Weather Data
1. Visit the Mars Facts website and scrape the table for Mars Weather Data using BeautifulSoup.
2. Store the data in a Pandas DataFrame.
3. Prepare the data by changing the data types for terrestrial_date, min_temp, and pressure columns.
4. Answer the following questions from the starter code:
    * How many months exist on Mars?
    * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    * What are the coldest and the warmest months on Mars (at the location of Curiosity)? And plot a bar chart.
    * Which months have the lowest and the highest atmospheric pressure on Mars? And plot a bar chart.
    * About how many terrestrial (Earth) days exist in a Martian year? And plot in a line chart.
5. Save the data to csv file. Data saved to 'mars_weather.csv'.
6. Make sure to close the browser.
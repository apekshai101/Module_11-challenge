# Module_11-challenge
web scraping challenge
This challenge use web scrapting techniques to
 1) Scrape titles and preview text from Mars news articles 
 2) Scrape and analyze Mars weather data, which exists in a table.



## Data Source
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC.
The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.


## Instructions:
Part 1: Scrape Titles and Preview Text from Mars News using part_1_mars_news.ipynb:
Visited  the Mars news siteLinks to an external site. And inspected the page to identify which elements to scrape using chrome dev tools.
1.    Beautiful Soup object was created and used to extract text elements from the website.
2.    Extracted the titles and preview text of the news articles and  stored the scraping results in Python data structures as follows:
•    Each title-and-preview pair in a Python dictionary and, each dictionary has two keys: title and preview. 
•    Dictionaries stored in a Python list.
•    The list is printed in notebook.

Part 2: Scrape and Analyze Mars Weather Data using part_2_mars_weather.ipynb

Visited the Mars Temperature Data SiteLinks to an external site.. and inspected the page to identify which elements to scrape  using chrome dev tools. The URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
A Beautiful Soup object was created and used to scrape the data in the HTML table.

The scraped data was assembled into a Pandas DataFrame. The columns had the same headings as the table on the website. The headings are as follows:
•    id: the identification number of a single transmission from the Curiosity rover
•    terrestrial_date: the date on Earth
•    sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
•    ls: the solar longitude
•    month: the Martian month
•    min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
•    pressure: The atmospheric pressure at Curiosity's location

The data was examined for data types that are currently associated with each column. 

Dataset  was analyzed  by using Pandas functions to answer the following questions:
•    How many months exist on Mars?
•    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
•    What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
•    Find the average minimum daily temperature for all of the months.
•    Plot the results as a bar chart.
•    Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
•    Find the average daily atmospheric pressure of all the months.
•    Plot the results as a bar chart.
•    About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
•    Consider how many days elapse on Earth in the time that Mars circles the Sun once.
•    Visually estimate the result by plotting the daily minimum temperature.


### Prerequisites
•    Tools need to have installed before project:
•    Jupyter notebook
•    Matplotlib
•    Pandas
•    Beautiful Soup
•    Splinter
•    GitHub
•    Local git repository Module_11-challenge was created, cloned and changes were pushed to main branch.

## Analysis
A short analysis summary is added at the end of part_2_mars_weather.ipynb jupyter notebook.
The df dataframe is exported to mars_weather_data.csv file.

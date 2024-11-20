Mars News and Weather Data Analysis

This project focuses on web scraping and data analysis using Python. By leveraging tools like Splinter for automated browsing and Beautiful Soup for HTML parsing, you’ll scrape data from web pages, organize it, and analyze it. The tasks include extracting Mars-related news and weather data to refine your skills in data collection, organization, and visualization.

This project requires the development of two deliverables:
	1.	Scrape Mars News: Extract and organize titles and preview texts from Mars news articles.
	2.	Scrape and Analyze Mars Weather Data: Scrape weather data from an HTML table, analyze it, and visualize key insights.

Part 1: Scrape Titles and Preview Text from Mars News

	1.	Open the Jupyter Notebook file part_1_mars_news.ipynb in the starter folder.
	2.	Use automated browsing with Splinter to navigate to the Mars News website and extract the page’s HTML code.
	3.	Use Beautiful Soup to scrape:
	•	News Titles
	•	Preview Texts
	4.	Save the extracted data into a Python list of dictionaries with the following structure:

 {'title': "Title of the news article",
 'preview': "Preview text of the news article"}

 	5.	Optionally, save the data into a JSON file for easier sharing.

Part 2: Scrape and Analyze Mars Weather Data

	1.	Open the Jupyter Notebook file part_2_mars_weather.ipynb in the starter folder.
	2.	Use Splinter and Beautiful Soup to scrape weather data from the Mars Temperature Data page at Mars Temperature Data.
	3.	Scrape the data into a Pandas DataFrame with columns corresponding to the HTML table’s headings:
	•	id: Identification number of the transmission
	•	terrestrial_date: Date on Earth
	•	sol: Martian days since landing
	•	ls: Solar longitude
	•	month: Martian month
	•	min_temp: Minimum daily temperature in Celsius
	•	pressure: Atmospheric pressure
	4.	Analyze the dataset using Pandas to answer the following questions:
	•	How many months exist on Mars?
	•	How many Martian days of data exist in the dataset?
	•	Which months have the highest and lowest:
	•	Average temperatures
	•	Atmospheric pressures
	5.	Create bar charts to visually represent:
	•	Temperature trends across months
	•	Pressure trends across months
	6.	Estimate the number of terrestrial days in a Martian year using a visual plot of daily temperatures.
	7.	Export the final DataFrame to a CSV file.

Requirements

Part 1: Mars News Scraping (40 points)
	1.	Use Splinter to visit the Mars news site and extract HTML with Beautiful Soup (10 points).
	2.	Scrape and extract the titles and preview texts of the news articles (20 points).
	3.	Save the results in a Python list of dictionaries (10 points).

Part 2: Mars Weather Data Scraping and Analysis (60 points)
	1.	Extract the weather table into a Pandas DataFrame with correct headings and data types (15 points).
	2.	Answer these questions using data analysis:
	•	How many months are there on Mars? (5 points)
	•	How many Martian days’ worth of data exists? (5 points)
	3.	Analyze the data with visualizations:
	•	Average temperature by month (10 points).
	•	Average atmospheric pressure by month (10 points).
	•	Terrestrial days in a Martian year, estimated within 25% accuracy (10 points).
	4.	Export the DataFrame to a CSV file (5 points).

Tools and Techniques

	•	Libraries: Splinter, Beautiful Soup, Pandas, Matplotlib
	•	Skills: Web scraping, data parsing, data analysis, data visualization
	•	File Handling: Exporting JSON and CSV files for data sharing and storage

This project strengthens core skills in web scraping, data organization, and Python programming while enhancing your ability to visually communicate insights through data analysis.

# mars_challenge
# Project 
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

# Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site Links to an external site.. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
An example is the following:
Store all the dictionaries in a Python list.
Print the list in your notebook.

# Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:
1) How many months exist on Mars?
2) How many Martian (and not Earth) days worth of data exist in the scraped dataset?

3) What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
![Cold_and_Hot](https://user-images.githubusercontent.com/115199874/210693335-fa743348-dcfc-4ad2-a46a-8837e4f65c50.png)
 Month 3 was the coldest month, and month 8 was the warmest month on mars. 

4) Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
![Average_pressure](https://user-images.githubusercontent.com/115199874/210692811-6db8590b-1ef5-4345-a80c-030955dd672a.png)
Month 6 has the lowest atmospheric pressure and month 9 has the highest atmospheric pressure. 
5) About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
![Earth_days](https://user-images.githubusercontent.com/115199874/210693432-ed339c78-9393-4044-bd49-86741fd81423.png)
On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms.
Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

# Ressources
## Images
1. Average_pressure.png
2. Average_temperature.png
3. Cold_and_Hot.png
4. Earth_days.png
## Data
Data_csv


# html-challenge
Module 11 Challenge

## Deliverable 1: Scrape Titles and Preview Text from Mars News
Import Splinter and BeautifulSoup.
Execute path to browser.
Visit the Mars news site.
Create a Beautiful Soup object.
Extract all the text elements.
Create an empty list to store the dictionaries.
Loop through the text elements.
Extract the title and preview text from the elements.
Store each title and preview pair in a dictionary.
Add the dictionary to the list.
Print the list to confirm success.
Quit the browser.

## Deliverable 2: Scrape and Analyze Mars Weather Data
Import relevant libraries.
Execute path to browser.
Visit the website.
Create a Beautiful Soup Object.
Extract all rows of data.
Create an empty list.
Loop through the scraped data to create a list of rows.
Create a Pandas DataFrame by using the list of rows and a list of the column names.
Confirm DataFrame was created successfully.
Examine data type of each column.
Change data types for data analysis.
Confirm type changes were successful by examining data types again.

Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average the minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

Write the data to a CSV.
Quit the browser.

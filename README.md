# Mission-to-Mars
UT Bootcamp Module 10 

## Project Overview
This is a module learning the web scraping process to extract data using the Mars Plant Science Exploration program website (https://redplanetscience.com/).


## Resources
Software utilized for this study included:
- Web Drive Manager
- Beautiful Soup
- MongoDB
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4
- Personal GitHub account

## Analysis and Workflow
Deliverable 1:
1. View images at the Mars Hemispeheres website.
2. Creat a list to hold the .jpg image URL string and title for each hemisphere image.
3. Write code to retrieve the full-resolution image URL and title for each hemisphere image.
4. Loop the full-resultion image URL and get the href from the Sample anchor tag.
5. Save the full-resolution image URL string as the value for the img_url key.
6. Save the hemisphere image title as the value for the title key.
7. Add the dictionary with the image URL string and the hemisphere image title to the list you created.
8. Print the list of dictionary items.
9. Quit the browser.

<code screen capture>

<image showing dictionaries>
  
Deliverable 2:
1. In the def scrape_all() function in your scraping.py file, create a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image.
2. 

## Results

Deliverable 1 - June Weather Statistics

![alt text](https://github.com/austin020269/surfs_up/blob/main/June_statistics.PNG)

- Total 1700 stations 
- Average temperature was approximately 75 degrees 
- High and low temperatures were 85 and 46 degrees Farenheit, respectively.

Deliverable 2 - December Weather Statistics

![alt text](https://github.com/austin020269/surfs_up/blob/main/December_statistics.PNG)

- Total of 1517 stations 
- Average temperature was approximately 71 degrees 
- High and low temperatures were 83 and 56 degrees Farenheit, respectively.

## Summary
Based on June and December temperature data, Oahu looks like a great place to open a surf and ice cream shop showing that it has a warm to moderate climate year round.  Other queries I would use in this analysis would be precipitation and number cloudy days vs sunny days.  People tend to be outdoors surfing and eating ice cream when the sun is out.

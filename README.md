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

 
Deliverable 2:
1. In the def scrape_all() function in your scraping.py file, create a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image.
2. Below the def mars_facts() function in the scraping.pyfile, create a function that will scrape the hemisphere data and return the scraped data as a list of dictionaries with the URL string and title of each hemisphere image.
3. Run the app.py file, then check your Mongo database to make sure that you are retrieving all of the data.
4. Modify the index.html file to access your database, and retrieve the img_url and title as you loop through the dictionary in the database using {% for hemisphere in mars.hemispheres %}.
5. Run the app.py file, open the index.html file, and click the "Scrape New Data" button.
6. Confirm that your webpage has the full-resolution images and the titles of the four hemisphere images.
7. Save all files.

<code screen capture>
  
Deliverable 3:
1. 

<code screen capture>

## Results

<show web page>

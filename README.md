# Mission-to-Mars
UT Bootcamp Module 10 

## Project Overview
This is a module learning the web scraping process to extract data using the Mars Plant Science Exploration program website (https://redplanetscience.com/).  I used Splinter and Beautiful Soup to scrape the appropriate data, transformaed the data into a Mongo database, used flask to upload to my webpage  and finally utilized Bootstrap to clean the webage content to get the final product.


## Resources
Software utilized for this study included:
- Web Drive Manager
- Beautiful Soup
- MongoDB
- Bootstrap
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

![alt text](https://github.com/austin020269/Mission-to-Mars/blob/main/Del1_image_1.PNG)

![alt text](https://github.com/austin020269/Mission-to-Mars/blob/main/Del1_image_2.PNG)



 
Deliverable 2:
1. In the def scrape_all() function in your scraping.py file, create a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image.
2. Below the def mars_facts() function in the scraping.pyfile, create a function that will scrape the hemisphere data and return the scraped data as a list of dictionaries with the URL string and title of each hemisphere image.
3. Run the app.py file (https://github.com/austin020269/Mission-to-Mars/blob/main/app.py), then check your Mongo database to make sure that you are retrieving all of the data.
4. Modify the index.html file (https://github.com/austin020269/Mission-to-Mars/blob/main/index_final.html) to access your database, and retrieve the img_url and title as you loop through the dictionary in the database using {% for hemisphere in mars.hemispheres %}.
5. Run the app.py file, open the index.html file, and click the "Scrape New Data" button.
6. Confirm that your webpage has the full-resolution images and the titles of the four hemisphere images.
7. Save all files.

![alt text](https://github.com/austin020269/Mission-to-Mars/blob/main/Del2_image_1.PNG)

  
Deliverable 3:
1. Make sure the page is clean.
2. Use the Bootstrap 3 grid system examples to update the index.html file so it is mobile-responsive.
3. Use DevTools to test the responsiveness of the website.
4. Add two Bootstrap 3 components from the list provided.

## Results - Final Webpage
Unforunately my app.py file ran but did not give the intended result that I did not have time to resolve:

http://127.0.0.1:5000/scrape

![alt text](https://github.com/austin020269/Mission-to-Mars/blob/main/Del2_image_2.PNG)





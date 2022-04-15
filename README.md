# Mission-to-Mars
## Project Overview
The project overview consist in four deliverables 
* Scrape Full-Resolution Mars Hemisphere Images and Titles
* Update the Web App with Mars Hemisphere Images and Titles
* Add Bootstrap 3 Components
* Readme

Delivering this challenge 10 we used to automate the website Splinter ,to parse and data extraction BeautifulSoup, to hold the data MongoDB to hold the data, also we used   Python, Jupyter notebook , flask, Jupyter Notebook, VS Code  and  GitHub; and the files used were, Firstly, the starter code, named  Mission_to_Mars_starter_code.ipynb downloaded from the challenge 10 in Canvas and renamed  Mission_to_Mars-Challenge.ipynb, also we dowloaded the index as a text and it was saved as html, Secondly it was created a folder named templates containing the last file mentioned; and using Python and HTML, it was added to the code created in the first delivery to the scraping.py file and update the Mongo database to modify index,html, consequently, the webpage contains all the information  collected, the full-resolution image and title for each hemisphere image, it was very challenging bacuse request to export for first time a file jupyter notebook as Python file and save it as a Mission_to_Mars_Challenge.py, used thue function defscrape_all() in the scraping.py file, create a new dictionary to hold the list of the URL string and title of each hemisphere image. after that was added the def mars_facts() function in the scraping.py file to scrape the hemisphere data using the code from Mission_to_Mars_Challenge.py filr, to return the scrapped  data as a list of dictionaries with the uRL string and title of each hemisphere image.Adittionally we ran the app.py file and ensured Mongo database was retriving all the data, finally it was mofified the index.html to access the database and retrive the img.url and title, for that was used % for hemisphere in mars.hemispheres %, ran the app.py file, open the Srape Data button and confirm thet the web page has the full resoltuion images and tiltitles for the four hemispheres as shown in the figure below.

![this is an image](https://github.com/JJF1962/Mission-to-Mars/blob/main/Mars%20Hemipheres(Deliverable%202).jpg)


## Results
* Added the hemisphere images.
* Styled the "Scrape New Data" 


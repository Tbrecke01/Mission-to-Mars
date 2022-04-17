# Mission-to-Mars

### Overview
The purpose of this project was to create a webpage that gathered information about Mars, the Mars Mission, and several pictures of the Martian surface into one location. To do this, a python script was written to scrape the desired data from several (scrape-friendly) NASA and JPL websites. A Flask web application was then created with a HTML template to display the data. The data was stored in a MongoDB database and Bootstrap componenets were used to design the webpage, make it mobile compatible, round the Mars images, and to create a button to automatically refresh the scrape and add any new data to the webpage. The downside is that if the scrapped websites update their HTML components the scrape will no longer occur correctly.

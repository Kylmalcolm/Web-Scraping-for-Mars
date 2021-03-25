<h1> Web Scraping for Mars </h1>

This is a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page.

<img width="570" alt="final_app_1" src="https://user-images.githubusercontent.com/70925750/112411361-c6c57f80-8cea-11eb-8759-8d72a6c674e8.PNG">

The latest article from https://mars.nasa.gov/news is scraped to provide the link, title, and introductory paragraph. This uses BeautifulSoup, pandas, and requests/splinter.

A featured image from https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars is scraped using splinter as well.

A set of Mars facts is scraped from https://space-facts.com/mars/ and converted into a HTML screen to load into the web application.

Finally, six different pictures of Mars are scraped from https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars and loaded into a MongoDB database to display in the application.

![image](https://user-images.githubusercontent.com/70925750/112412335-5d467080-8cec-11eb-8318-2fd8fd793378.png)

<img width="625" alt="final_app_2" src="https://user-images.githubusercontent.com/70925750/112411394-d80e8c00-8cea-11eb-8d5a-9d7ea970c4e4.PNG">

A html index page was created using bootstrap and the scraped data from the various sites loaded into it using Flask and MongoDB.

![image](https://user-images.githubusercontent.com/70925750/112412409-74855e00-8cec-11eb-9579-a40db37e6862.png)

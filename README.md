# Mission to Mars
For this module, we have been scraping data in Python using Splinter, Beautiful Soup, and Pandas. We then stored the data in MongoDB and displayed it in a web application built with Python Flask.

## Overview
For this module's challenge, we have been scraping Mars data from various websites. We would identify the HTML elements we wanted to scrape first. We'd then execute various scripts in Python to launch a browser, extract content, and click buttons on the web page to navigate.

The information of interest was stored in a MongoDB database running on our development machine.

A Python Flask application was built with two routes:
1. The default route would look up the scraped information from the database and display it on the index page.
2. We also provided a scrape route for the user to click the button and update the information by scraping for the same information again.

## Challenge Files
- The [mission to mars challenge](Mission_to_Mars_Challenge.ipynb) interactive Python notebook file contains the initial scraping code.
- We then converted the scraping code into functions in the [scraping](scraping.py) file.
- The [index](templates/index.html) HTML contains the updated template with several examples of Bootstrap usage.
- The [app](app.py) Python file is the program that starts the Flask application, defines the various routes, and database connection.

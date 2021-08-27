# Module-10-Mission-to-Mars

## Tools & Resources
* VS Code (.py, HTML, css)
* Jupyter Notebook
* Python & Librarys: Beautifulsoup, Pandas, splitter, datetime Bootstrap 3
* Flask
* MongoDB


## Objectives

* Scape high resolution images from Mars.Nasa using BeautifulSoup and splinter 
* Store our nonsql data in a MongoDB database we created called Mars_app
* Create a local web application and using flask to display the data we scaped from Mars.Nasa
* Used bootstrap to style our webapp
*


## Description

Our web scrapping script is written in the scraping.py. We created this script throught out module 10. Our challenge was to add an additional section into our web app. 1) The Mars Hemisphere headers  2) four high quality images from headers. Our output is pushed with flask and the apps routes being sorted in app.py script.

Our app.py script calls upon our scaping.py script and the scraping.py script does basically most of the work. Our scrapped Data is stored in a MongoDB database and retrieved to our browser app through running a local flask. Our page setup is formatted in the index.html file, we are using bootstrap 3 to clean up and display our high quality images. 

## Outcome & Challenges

I had an inital problem getting MongoDB to start up properly. I could not connect to any server on my local drive.
Drew helped me by identifying my problem. He helped me get Brew installed correctly on my computer and I was able to complete the module. 

I had an issue with the chromedriver not being file causing the python interpretor to fail. I searched for the chromedriver file and put it in the correct directory. This fixed the issue.

Below are two screenshots of the outcome. 


<img width="255" alt="Screen Shot 2021-08-27 at 1 44 45 PM" src="https://user-images.githubusercontent.com/83923903/131187288-1c39d4dc-a979-4f3c-bd3f-b9df0b72082d.png">

<img width="1368" alt="Screen Shot 2021-08-27 at 1 34 39 PM" src="https://user-images.githubusercontent.com/83923903/131187311-1d68ad27-d614-4b73-8025-8ff1120470f4.png">


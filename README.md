# Linkedin Search Query Tool 
- Overview: This Jupyter Notebook Script allows you to take a set of linkedin company urls + a handful of search terms and collect employees associated with those companies and titles. 

## Create Driver Folder and add chromedriver ( check chrome browser version on your device )

## add linkedin credentials to config.ini

## Open the terminal in vs code and run the following 

### Virtual Environment
- pip install virtualenv 
- virtualenv venv
- source venv/bin/activate

### Python-decouple ( for reading env )
- pip install python-decouple

### Selenium
- pip install selenium 

### Beautiful Soup
pip install beautifulsoup4

# Bug Fixes 
- Currently employee urls are collected but not always accurate - some include re-directs back to the original search query. 
- This issue likely stems from the fact that the requests are being made through a chromedriver and are therefore viewed as 'bot' activity. In order to avoid this categorization, headers with further details should be used in order to mimic the requests made by a regular browser (chrome, firefox, brave, etc). This requires changing the headers associated with the request. 







 
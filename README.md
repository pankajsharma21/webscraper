# webscraper
**if we want to scrape a website :**
1. Use the API  
2. HTML Web Scraping using some tool like bs4

**Required Modules.** 

**pip install requests**     _______fetched HTML using requests as an string using get() function in requests module <br/>

 **pip install html5lib**    _______html5lib is a pure-python library for parsing HTML <br/>

 **pip install bs4**         _______Beautiful Soup is a Python library for pulling data out of HTML and XML files <br/>


we can fetched HTML using requests as an string using get() function in requests module. 

now we need to parse it.

for parsing i used pythons BeautifulSoup module which will create a tree like structure for our DOM

once the HTML is fetched and parse the next step is to manipulate the tree using BeautifulSoup's function to get our job done.

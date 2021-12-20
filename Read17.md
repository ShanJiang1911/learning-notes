
### [Web Scrape with Python in 4 minutes](https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460)
  ```
  Steps:
import urllib.request
import time
from bs4 import BeautifulSoup

# Set the URL you want to webscrape from
url = 'http://web.mta.info/developers/turnstile.html'

# Connect to the URL
response = requests.get(url)

# Parse HTML and save to BeautifulSoup object¶
soup = BeautifulSoup(response.text, "html.parser")

# To download the whole data set, let's do a for loop through all a tags
line_count = 1 #variable to track what line you are on
for one_a_tag in soup.findAll('a'):  #'a' tags are for links
    if line_count >= 36: #code for text files starts at line 36
        link = one_a_tag['href']
        download_url = 'http://web.mta.info/developers/'+ link
        urllib.request.urlretrieve(download_url,'./'+link[link.find('/turnstile_')+1:]) 
        time.sleep(1) #pause the code for a sec
    #add 1 for next line
    line_count +=1
  ```

### [What is Web Scraping?](https://en.wikipedia.org/wiki/Web_scraping)
* Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites
* Techniques:
  * Human copy-and-paste
  * Text pattern matching
  * HTTP programming
  * HTML parsing
  * DOM parsing
  * Vertical aggregation
  * Semantic annotation recognizing
  * Computer vision web-page analysis
### [How to scrape websites without getting blocked](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)
* Web scraping should not have a detrimental effect on the sites being scraped
* How can website detect and block web scraping
  * Unusual traffic/high download rate
  * Repetitive tasks performed on the website in the same browsing pattern
  * Checking if you are real browser
  * Detection through honeypots 
### Videos
### [Track Amazon Prices](https://www.youtube.com/watch?v=Bg9r_yLk7VY)
### Bookmark/Skim
### [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)

[<--Back](README.md)
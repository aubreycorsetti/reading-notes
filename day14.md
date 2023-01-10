# Day 14 Notes

## Web Scraping

### Web Scrape with Python in 4 minutes

> Step Through

1. Inspect the website
  • We need to figure out where we can locate the links to the files we want to download inside the levels of HTML tags. There is a lot of code on a website page and we want to find the relevant pieces of code that contains our data. (use the console)

2. Python Code
  • Import libraries then set the url to the website and access the site with our requests library
  • Parse the html then use the method .findAll to locate off of the anchor tags
  • Extract the link
  • Use time.sleep(1) to pause our code so we aren't spamming the site with requests.

### What is Web Scraping

> Extracting data from websites. It's a form of copying in which specific data is gathered and copied from the web.

### How to scrape websites without getting blocked

• Do not overload the server, don't spam it with requests.

•Dont' follow the same "crawling" pattern

• Make your requests through a proxy

• If the site contains these lines, the site does not want to be scraped:

  1. user-agent: *
  2. disallow:/

> **Easy giveaways that you are a scraper**

• Scraping too fast and too many pages, faster than a human ever can

• Following the same pattern while crawling. For example – go through all pages of search results, and go to each result only after grabbing links to them. No human ever does that.

• Too many requests from the same IP address in a very short time

• Not identifying as a popular browser. You can do this by specifying a ‘User-Agent’.
using a user agent string of a very old browser

#### Things I want to know more about

> I want to know more about how/when to scrape sites.

#### Sources

[towardsdatascience.com](https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460)

[Wikipedia](https://en.wikipedia.org/wiki/Web_scraping)

[scrapehero.com](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

Click to return [Home!](../README.md)

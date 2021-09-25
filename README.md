# CZ4070 Cyber Theat Intelligence

## 1. Web Scraping
Websites that have been scraped: 
1) REvil (Link: http://dnpscnbaix6nkwvystl3yxglz7nteicqrou3t75tpcc5532cztc46qyd.onion)
2) ??
3) ?? 

__How it works:__ <br />
The web scaper scrapes the title of each post in the website, which contains the name of the victim company/organization. Each 
victim company/organization is placed inside a list that will later be passed to the Selenium script to find its industry. 

## 2. Web Automation using Selenium
__How it works:__ <br />
Selenium will loop through the list of vicim campanies/organizations, and do an automated Google search to find the victim's 
industry. The search has been narrowed down to Wikipedia searches. 

## 3. Collating the data
__How it works:__ <br />
Data from each of the scraped websites will be collated together into a Pandas DataFrame.

## Challenges faced:
1) __Unable to incorporate Selenium with Tor__
    1) Problem: Usage of proxy server and different sockets to access Tor causes Selenium to be unable to run
    2) Fix: Storing the old socket configurations, and configuring the socket to its previous socket configurations helped solve the issue
2) __Difficulty in cleaning data__
    1) Problem: There exists duplicate victim company/organization names within the DataFrame with slight variations
    2) Fix: ???
  

# Proxy Scraper

## General info:
A simple web scraper that retrieves proxies from a public website.
Developed to easily add proxies to requests in personal/hobby scraping projects.

The proxies are returned in a list so that they can easily be passed
into the request proxy argument. Additional functionality to retrieve proxies from a certain country, or exclusively HTTPS proxies.

## Technologies:
Created with Python. Packages used:
* Beautiful Soup
* Requests

## Setup:
* pip install requirements.txt
* run

## Development:
For the moment the script works as intended for the purpose it was created. Possible extensions include a filter on when a given proxy was last tested or a test to see if the proxy still works. Additionally, could add multiple source websites from which the proxies are retrieved.
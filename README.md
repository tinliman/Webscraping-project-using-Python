# Scraping Goodfirms.co's Software company details using Python

Check out the Jypeter Notebook here :https://jovian.com/tinliman21/web-scraping-project

What is web scraping?

Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites.[1] Web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.

Why GOODFIRMS?
GoodFirms is a treasury of the globe’s most prominent, efficient, and well-performing IT companies and software solutions.

With its groundbreaking and foolproof research process, GoodFirms has been researching and reviewing companies & software products that could be of help to prospects. With an extensive stacked up list of researched and reviewed companies & software solutions altogether at one place, service finders are witnessing a noticeable reduction in their tasks with them being able to easily identify and pick the most appropriate firm to meet their requirements on the go!

GoodFirms is offering a solid platform for companies and software vendors that want to sow seeds of reputation management just so to mark their hard-earned stature in the industry across the globe.

GoodFirms is a full-fledged research and review platform that helps software buyers and service seekers to opt for the best software or firm. At the same time, it helps IT companies and software vendors to boost user acquisition stats, market share and brand awareness. GoodFirms, just as the name suggests, is a dedicated community of “performing” IT companies as well as software solutions.

We are well aware of the scenarios at both ends, wherein service seekers are struggling to find the best companies to meet a specific need and how leading software firms are making efforts to stand out from a clusters of inferior competitors.

Hence, GoodFirms is at the forefront to help service buyers from around the world by providing a categorized directory, client reviews and company content & resources to help them choose the best firm/software product that meets their specific requirements. That said, GoodFirms also serves as an unequalled platform for performing IT companies and software to put their best foot forward. We follow an innovative research process that helps us to identify leading companies and software solutions that have been delivering groundbreaking results to their clients.

For this project, I used :

- import requests # To extract the HTML document from the website
- from bs4 BeautifulSoup # To parse through the HTML document
- import csv # To convert result into a csv file
- import pandas as pd # To put the data into a dataframe
- BeautifulSoup library for handling the text extraction from the web page’s source code (HTML and CSS)
- from bs4 import BeautifulSoup

doc= BeautifulSoup(requests.get(i).text)

Requests library for handling the interaction with the web page (Using HTTP requests)
import requests

Install Pandas DataFrame to create a Library
import pandas as pd

Create CVS file with the extracted information
company_df.to_csv('4software_company.csv', index=None)

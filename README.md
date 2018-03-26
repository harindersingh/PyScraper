# PyCrawler
Crawler using Python 3

ScrapLink is a crawler that starts with a url on the web (ex: http://python.org), fetches the web-page corresponding to that url, and parses all the links on that page into a repository of links. Next, it fetches the contents of any of the url from the repository just created, parses the links from this new content into the repository and continues this process for all links in the repository until stopped or after a given number of links are fetched.

"Structure of Code is Key"

./LICENSE - Lawyering Up \n
.setup.py - Package and distribution management. \n
./requirements.txt - Development dependencies. \n
./tests - Package integration and unit tests.

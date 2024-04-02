# webScrape0327_ichef
This is a python web scrape code for recording the restaurants showed on the ichef maps ("https://shop.ichefpos.com/explore").
The code follows these steps:
A. First:
  1. Set the coordinates rectangle by four corners' coordinates and the step which the function will search at each coordinates every step
  2. After setting the current coordinates, it will pass the coordinates to chrome, the selenium web driver will record the restaurants showed on the map to json.
  3. When the previous coordinate had been searched, the webdriver will jmpu to the next coordinate and so on untill all coordinates are covered.
B. Secnd:
  1. After all the shop links were scraped, use the links to scrape menu information

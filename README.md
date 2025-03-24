# CeneoScraper
# https:/www.ceneo.pl/84514582#tab=reviews_scroll
## Ceneo scraping algorithm
1. Analysis of the structure of the website
2. Sending http request to acces first page with options
3. CHecking the code of Http responce
4. Parse the http code of first page with opinions
5. Extract required data from parsed code
6. If there are more pages, move to the next page and repeat steps
7. Save extracted data


## Analysis ofteh structure of the webpage
|Component|Selector|Variable|
|---------|--------|--------|
|opinion ID|#opinion-ID | |
|author|.author||
|recommendation|.recommendation||
|number of stars|.star .rating||
|opinion’s content|.opinion-content||
|list of advantages|.advantages li||
|list of disadvantages|.disadvantages li||
|for how many helpful|.helpful-count||
|for how ,ane unhelpful|.unhelpful-count||
|publishing date|.publish-data||
|Purchase date|.purchase-data||

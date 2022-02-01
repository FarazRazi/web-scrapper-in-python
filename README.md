# web-scrapper-in-python
web-scrapper to collect data from any three university website and visualize the three websites' nouns and their connections in a graph.
## Implementation needed:
1. Use a web-scrapper to collect data from any three university website (include  5 webpages)of Pakistan and provide the following analysis.
2. Create visualization showing the comparison of the three website wrt adjectives, verbs and nouns.
3. Create a graph using  by considering all the Nouns and nodes and two nouns are considered adjacent when they occur in the same sentence. After the graph construction show the following metrics for the selected website
    - Number of Connected component
    - Top 10 Nouns with highest degree and their degree value
    - Print all nouns that are available on a distance <5 from the noun "quality" for each university, the selected pages must contain "quality".
## Libraries Used 
- ### For Graphing
  - networkx `https://networkx.org/`
  - matplot `https://matplotlib.org/`
- ### For Scraping and reading 
  - spacy `https://spacy.io/`
  - pandas `https://pandas.pydata.org/`
- ### For Website Fetching
  - requests `https://docs.python-requests.org/en/latest/`
  - urllib `https://docs.python.org/3/library/urllib.html`

## Disclaimer 
  This project was done for a non-programming course Discrete structure, to showcase how we can use concepts learnt like logics and graphs to implement it. So, the code is not optimized and have a very limited use.
  Hope someone finds it useful.


# Homework 5 - Explore Wikipedia's hyperlinks network
![graph](https://anthonybonato.files.wordpress.com/2017/03/jrnlcovercropped.jpg)

## Authors
* Michelangelo Saveriano
* Flavia Penta de Peppo
* Adrienn Timea Aszalos
* Nicola Calabrese

*for "Algorithmic Methods of Data Mining", "La Sapienza" University of Rome, MSc in Data Science, 2020-2021*.\
In this assignment we analyze the Wikipedia's articles network by applying graph algorithms.

## Data and setting

There are many options to collect and build the Wikipedia's underlying network, we rely on the dataset provided [here](https://snap.stanford.edu/data/wiki-topcats.html). For the purpose of our exploration, we do not consider the entire dataset. Instead, we focus on the articles belonging to a subset of categories.

We download the reduced version of the graph Wikicat hyperlink graph. Every row indicates an edge. In particular, the two elements are the source and the target, respectively.
<br/>
<br/>
From the linked page we download:
* [wiki-topcats-categories.txt.gz](https://snap.stanford.edu/data/wiki-topcats.html)
  > containing the list of pages per category
  
* [wiki-topcats-page-names.txt.gz](https://snap.stanford.edu/data/wiki-topcats-page-names.txt.gz)
  > containing the page names
<br/>
Note that in the reduced version of the network we remove the categories whose number of articles in less than 5000 and more than 30000.

## Repository files
* [__`main.ipynb`__](../main/main.ipynb):
  > This is the core of this repository. In fact it contains the results of our implementations and researches.

## Notes
We choose to implement the graph within a class **Graph**, from scratch with all the related methods, like BFS, Min-Cut and many others, in order to optimize computational time. 
We also decided to challenge ourselves and add an **Extra** part for the first three questions using the library networkx. 

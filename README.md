# ADM-HW5
![graph](https://anthonybonato.files.wordpress.com/2017/03/jrnlcovercropped.jpg)
#### Authors: Michelangelo Saveriano, Flavia Penta de Peppo, Adrienn Timea Aszalos, Nicola Calabrese
#### Course: Masters in Data Science

In this assignment we analyze the Wikipedia's articles network by applying graph algorithms.

## Data and setting

There are many options to collect and build the Wikipedia's underlying network, we rely on the dataset provided here. For the purpose of our exploration, we do not consider the entire dataset. Instead, we focus on the articles belonging to a subset of categories.

Download the reduced version of the graph Wikicat hyperlink graph. Every row indicates an edge. In particular, the two elements are the source and the target, respectively.
From this page download:
wiki-topcats-categories.txt.gz: list of pages per category
wiki-topcats-page-names.txt.gz: page names
Note that in the reduced version of the network we removed the categories whose number of articles in less than 5000 and more than 30000.

## Repository Files
#### 1. main.ipynb File
We decide to implement our class  **Graph** from scratch with all the methods we need for the several questions (BFS,Algorithm for the  min cut,...),optimizing 
all functions to be able to run them in a suitable computational time.

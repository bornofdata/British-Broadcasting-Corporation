# British-Broadcasting-Corporation

## Overview

The objective of this project is to employ Natural Language Processing (NLP) techniques to analyze a collection of articles from the BBC across five distinct categories. The project aims to uncover insights by addressing two primary questions:

1. Identifying Common Topics by Category:
For each of the five specified categories, the project seeks to determine the most prevalent topics among the articles. Utilizing NLP algorithms, the analysis will focus on extracting key themes, subjects, and trends within each category. This exploration aims to provide a comprehensive understanding of the predominant discussions within the different sections of the BBC.

2. Exploring G20 Country Mentions Across Categories:
The second aspect of the project involves examining how many articles across all categories specifically mention each of the G20 countries. By leveraging NLP algorithms, the analysis will identify and quantify the frequency of references to individual G20 nations within the entire dataset. This broader perspective aims to unveil patterns in the global coverage provided by the BBC, shedding light on the prominence of G20 countries in various news topics.

Overall, this NLP-driven project seeks to offer valuable insights into the content of BBC articles, providing a nuanced understanding of prevalent topics within specific categories and the coverage of G20 countries across diverse news segments. The application of NLP techniques enables a data-driven approach to uncover patterns, trends, and relationships within the extensive BBC article dataset.


## BBC Datasets
Two news article datasets, originating from [BBC News](http://mlg.ucd.ie/datasets/bbc.html), provided for use as benchmarks for machine learning research.
These datasets are made available for non-commercial and research purposes only. If you make use of these datasets please consider citing the publication:

D. Greene and P. Cunningham. "Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering", Proc. ICML 2006. [PDF](http://mlg.ucd.ie/files/publications/greene06icml.pdf) [BibTeX](http://mlg.ucd.ie/files/bib/greene06icml.bib).


### Dataset: BBC
All rights, including copyright, in the content of the original articles are owned by the BBC.

- Consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.
- Class Labels: 5 (business, entertainment, politics, sport, tech)


> [Download pre-processed dataset](http://mlg.ucd.ie/files/datasets/bbc.zip)

> [Download raw text files](http://mlg.ucd.ie/files/datasets/bbc-fulltext.zip)


### Dataset: BBCSport
All rights, including copyright, in the content of the original articles are owned by the BBC.

- Consists of 737 documents from the BBC Sport website corresponding to sports news articles in five topical areas from 2004-2005.
- Class Labels: 5 (athletics, cricket, football, rugby, tennis)
> [Download pre-processed dataset]('http://mlg.ucd.ie/files/datasets/bbcsport.zip')

> [Download raw text files]('http://mlg.ucd.ie/files/datasets/bbcsport-fulltext.zip')


### File formats
The datasets have been pre-processed as follows: stemming (Porter algorithm), stop-word removal ([stop word list](http://mlg.ucd.ie/files/datasets/stopwords.txt)) and low term frequency filtering (count < 3) have already been applied to the data. The files contained in the archives given above have the following formats:


- *.mtx: Original term frequencies stored in a sparse data matrix in [Matrix Market format](http://math.nist.gov/MatrixMarket/index.html).
- *.terms: List of content-bearing terms in the corpus, with each line corresponding to a row of the sparse data matrix.
- *.docs: List of document identifiers, with each line corresponding to a column of the sparse data matrix. 
-  *.classes: Assignment of documents to natural classes, with each line corresponding to a document. 
- *.urls: Links to original articles, where appropriate. 


### Questions:
1.	For each of the five categories: what are the most common topics among articles?
2.	Across all categories: how many articles talk about each of the G20 countries?


[Link to analysis on Kaggle](https://www.kaggle.com/code/fagbamigbekehinde/bbc-category)

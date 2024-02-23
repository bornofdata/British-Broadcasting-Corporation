# British-Broadcasting-Corporation

## Overview

This is a document classification project to help to sort 



### BBC Datasets
Two news article datasets, originating from [BBC News]('http://mlg.ucd.ie/datasets/bbc.html'), provided for use as benchmarks for machine learning research.
These datasets are made available for non-commercial and research purposes only. If you make use of these datasets please consider citing the publication:

D. Greene and P. Cunningham. "Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering", Proc. ICML 2006. [PDF]('http://mlg.ucd.ie/files/publications/greene06icml.pdf') [BibTeX]('http://mlg.ucd.ie/files/bib/greene06icml.bib').


#### Dataset: BBC
All rights, including copyright, in the content of the original articles are owned by the BBC.

<li>
<ul> Consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005. </ul>
<ul></ul> Class Labels: 5 (business, entertainment, politics, sport, tech)</ul>
</li>

> [Download pre-processed dataset]('http://mlg.ucd.ie/files/datasets/bbc.zip')

> [Download raw text files]('http://mlg.ucd.ie/files/datasets/bbc-fulltext.zip')


Dataset: BBCSport
All rights, including copyright, in the content of the original articles are owned by the BBC.

Consists of 737 documents from the BBC Sport website corresponding to sports news articles in five topical areas from 2004-2005.
Class Labels: 5 (athletics, cricket, football, rugby, tennis)
>> Download pre-processed dataset

>> Download raw text files


File formats
The datasets have been pre-processed as follows: stemming (Porter algorithm), stop-word removal ([stop word list]('http://mlg.ucd.ie/files/datasets/stopwords.txt')) and low term frequency filtering (count < 3) have already been applied to the data. The files contained in the archives given above have the following formats:

<li>
 <ul> *.mtx: Original term frequencies stored in a sparse data matrix in [Matrix Market format]('http://math.nist.gov/MatrixMarket/index.html'). </ul> 
 <ul> *.terms: List of content-bearing terms in the corpus, with each line corresponding to a row of the sparse data matrix. </ul>
 <ul> *.docs: List of document identifiers, with each line corresponding to a column of the sparse data matrix. </ul>
 <ul>  *.classes: Assignment of documents to natural classes, with each line corresponding to a document. </ul>
 <ul>  *.urls: Links to original articles, where appropriate. </ul>
</li>




## Dataset

Questions:
1.	For each of the five categories: what are the most common topics among articles?
2.	Across all categories: how many articles talk about each of the G20 countries?
a.	Note that we are interested in topics about the country, so a mention of the UK might be an article on British business even if it doesn’t mention the words “United Kingdom”.

3.	Describe the methodologies you used to solve questions 1 and 2.
4.	What tools did you use for this analysis?
5.	How much time did you devote to this exercise?
6.	If you had more time how would you strengthen your answer for question 2?


[Link to analysis on Kaggle]('https://www.kaggle.com/code/fagbamigbekehinde/bbc-category')

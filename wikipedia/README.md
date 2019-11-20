# Wikipedia data sets

The provided Wikipedia data sets are divided in two subcategories: network analysis and  . 

## Network analysis

The network data set allows to analyse the interconnectivity between Wikipedia articles. If person x is referred to by a large number of articles (persons or others), the power-score of person x might go up. The data set contains two different kind of files:

- wiki-topcats-page-names.txt: This file links the page id's with the article name. The articles are of any nature and not limited to persons. 

- wiki_topcats_x.csv: This file contains the hyperlinks from one article to another. Each instance has the following structure: [index, article ID A, article ID B]. E.g. [2, 34, 2934] means that Wikipedia article 34 contains a link to Wikipedia article 2934. The data set is split up into 15 files. 


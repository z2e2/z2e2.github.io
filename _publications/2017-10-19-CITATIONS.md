---
title: "Incremental Author Name Disambiguation for Scientific Citation Data"
collection: publications
permalink: /publications/2017-10-19-CITATIONS
excerpt: 'This paper is about an incremental learning based author name disambiguation framework.'
date: 2017-10-19
venue: 'IEEE International Conference on Data Science and Advanced Analytics'
paperurl: 'https://doi.org/10.1109/dsaa.2017.17'
citation: 'Z. Zhao, J. Rollins, L. Bai and G. Rosen, "Incremental Author Name Disambiguation for Scientific Citation Data," <i>2017 IEEE International Conference on Data Science and Advanced Analytics (DSAA)</i>, Tokyo, pp. 175-183 (2017).'
---
## Abstract
Name disambiguation is a perennial challenge for any large and growing dataset but is particularly significant for scientific publication data where documents and ideas are linked through citations and depend on highly accurate authorship. Differentiating personal names in scientific publications is a substantial problem as many names are not sufficiently distinct due to the large number of researchers active in most academic disciplines today. As more and more documents and citations are published every year, any system built on this data must be continually retrained and reclassified to remain relevant and helpful. Recently, some incremental learning solutions have been proposed, but most of these have been limited to small-scale simulations and do not exhibit the full heterogeneity of the millions of authors and papers in real world data. In our work, we propose a probabilistic model that simultaneously uses a rich set of metadata and reduces the amount of pairwise comparisons needed for new articles. We suggest an approach to disambiguation that classifies in an incremental fashion to alleviate the need for retraining the model and re-clustering all papers and uses fewer parameters than other algorithms. Using a published dataset, we obtained the highest K-measure which is a geometric mean of cluster and author-class purity. Moreover, on a difficult author block from the Clarivate Analytics Web of Science, we obtain higher precision than other algorithms.

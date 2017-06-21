---
layout: post_projects
author: Julia Stoyanovich
title: DB4Pref - Managing Preference Data
category: projects
---

## Summary

The goal of this project is to streamline the management and analysis of preference data.

Preferences are orders among a collection of items attributed to a population of judges. Preference data comes in a variety of forms, such as ranked lists and pairwise comparisons, and is ubiquitous in a plethora of applications across different domains. Over the past decade, there has been a sharp increase in the volume of preference data, in the diversity of applications that use it, and in the richness of preference data analysis methods. Examples of applications include rank aggregation in genomic data analysis, management of votes in elections and recommendation systems in e-commerce.

In our work we look at two complementary aspects of preference management. In the first (funded by NSF Grant No. [1464327]), we are enriching the relational database model with extensions that are specialized for handling preference data.

This involves developing (1) a special type of a relation that is designed for preference data, and (2) operations on preference relations that can be embedded in SQL statements, for convenient reuse across applications. Treating preferences, and preference analytics, as first-class citizen in a relational database, and making these available through (augmented) SQL queries, will brings two important advantages. The first is usability: since SQL queries are specified declaratively, users need not worry about data formats and implementation details of data manipulation methods. The second advantage is efficiency: the system is free to choose an appropriate query execution plan, and an efficient implementation of a specific analysis method, exploiting a trade-off between processing time and answer quality.

The second aspect of our work (funded by BSF Grant No. 2014391 and NSF Grant No. [1539856]) focuses on developing novel analytics that are geared towards incomplete preferences.

This work will establish principles, paradigms, and computing machinery for effective analysis of large datasets of incomplete preferences. To that aim, this project develops (1) novel approaches for mining frequent, or otherwise interesting, patterns in preference data; (2) novel clustering and preference aggregation methods; and (3) an extensive data acquisition and experimental evaluation to enhance the research and development of analysis methodologies.


## People
See our members:
- [Julia Stoyanovich] (Drexel, USA)
- [Benny Kimelfeld] (Technion, Israel)
- [Lovro Ilijasic] (Drexel, USA)
- [Batya Kenig] (Technion, Israel)
- [Haoyue Ping] (Drexel, USA)


## Publications
See our papers:
- "Querying probabilistic preferences in databases", Batya Kenig, Benny Kimelfeld, Haoyue Ping and Julia Stoyanovich. PODS 2017. [pdf-pods17]

- "A database framework for probabilistic preferences", Batya Kenig, Benny Kimelfeld, Haoyue Ping and Julia Stoyanovich. AMW 2017. forthcoming

- "Workload-Driven Learning of Mallows Mixtures with Pairwise Preference Data", Julia Stoyanovich, Lovro Ilijasic, Haoyue Ping. WebDB 2016. [pdf-webdb16]

- "Analyzing Crowd Rankings", Julia Stoyanovich, Marie Jacob, Xuemei Gong. WebDB 2015. [pdf-webdb15]

- "Dichotomies in the Complexity of Preferred Repairs", Ronald Fagin, Benny Kimelfeld, Phokion G. Kolaitis. PODS 2015. [pdf-pods15]

- "A System for Management and Analysis of Preference Data", Marie Jacob, Benny Kimelfeld, Julia Stoyanovich. PVLDB 7(12) 2014. [pdf-pvldb14]

- "Understanding Local Structure in Ranked Datasets", Julia Stoyanovich, Sihem Amer-Yahia, Susan Davidson, Marie Jacob, Tova Milo. CIDR 2013. [pdf-cidr13]


## Data and Code

Learning Mallows Mixtures, complete code and data on [project website].

The CrowdRank dataset on [GitHub].


## Funding

This work is generously supported by the US National Science Foundation (NSF) and by the US-Israel Binational Science Foundation (BSF).

NSF Grant No. [1464327] "Managing Preference Data", 5/1/2015 - 4/30/2017 (PI: Stoyanovich)

BSF Grant No. 2014391 "Aggregation Methods for Partial Preferences", 9/1/2015 - 8/31/2017 (US PI: Stoyanovich, Israel PI: Kimelfeld)

NSF Grant No. [1539856] "Aggregation Methods for Partial Preferences" (supplements BSF Grant No. 2014391), 9/1/2015 - 8/31/2017 (PI: Stoyanovich)




[1464327]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1464327&HistoricalAwards=false
[1539856]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1539856&HistoricalAwards=false
[Julia Stoyanovich]: https://www.cs.drexel.edu/~julia/
[Benny Kimelfeld]: http://benny.net.technion.ac.il/
[Lovro Ilijasic]: http://lovroforsale.com/
[Batya Kenig]: http://www.cs.technion.ac.il/people/batyak/
[Haoyue Ping]: http://cs.drexel.edu/~hp354/
[project website]: https://www.cs.drexel.edu/dbgroup/db4pref/webdb2016/
[GitHub]: https://github.com/stoyanovich/CrowdRank
[pdf-pods17]: http://dl.acm.org/citation.cfm?doid=3034786.3056111
[pdf-webdb16]: https://www.cs.drexel.edu/dbgroup/downloads/webdb2016/preference.webdb2016.pdf
[pdf-webdb15]: http://dl.acm.org/citation.cfm?doid=2767109.2767110
[pdf-pods15]: http://dl.acm.org/citation.cfm?doid=2745754.2745762
[pdf-pvldb14]: http://www.vldb.org/pvldb/vol7/p1255-jacob.pdf
[pdf-cidr13]: http://www.cidrdb.org/cidr2013/Papers/CIDR13_Paper51.pdf
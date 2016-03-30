
## Data files for the paper:

[Tag Recommendation for Large-Scale Ontology-Based Information Systems](http://iswc2012.semanticweb.org/sites/default/files/76500318.pdf)

[Accepted at ISWC 2012, Evaluations & Experiments track]

## Article and Bookmark data

Data used in tag recommendation experiments. The data here is represented by the set of CSV files:

* [Bookmarks collection](bookmarks.csv). Contains users' choices of concepts for each paper in the collection. Fields are defined in the first line of the file.
* [Articles collection](articles.csv). Contains concepts extracted by the system for each paper in the collection. Fields are defined in the first line of the file.
* [Concepts collection](concepts.csv). Contains concepts from the ontology. Fields are defined in the first line of the file.


## Disambiguation Data

Data used in the disambiguation experiments

* [Articles collection](disambiguations/articles.tar.gz). Tarball containing collection of arXiv.org papers in the form of text files containing IDs of extracted concepts.
* [LDA processed data](disambiguations/lda_data.tar.gz). Tarball containing the LDA post-processed data on the latter articles collection.

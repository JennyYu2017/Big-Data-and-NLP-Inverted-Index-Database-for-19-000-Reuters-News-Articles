# Big Data and NLP：Inverted Index Database for 19,000 Reuters News Articles

This project is about implementing an inverted index using Apache Spark（Pyspark）to build a relational database (SQLite) for 19,000 Reuters News Articles.Storing the index in a database offers the benefit of  using the B-Tree data structure offered by a relational database instead of building it from  the scratch.  

To convert the text file into inverted index, natrual lanaguage processing libraries, including nltk,re, bs4, collections,are applied. Two datasets are given; a real one from Reuters which contains more than 19,000  documents, and a small sample of 5 documents in order to help with testing the code. 

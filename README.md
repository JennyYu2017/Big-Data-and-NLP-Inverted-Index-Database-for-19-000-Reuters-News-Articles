# Big Data and NLP：Inverted Index Database for 19,000 Reuters News Articles

This project is about implementing an inverted index using Apache Spark（Pyspark）to build a relational database (SQLite) for 19,000 Reuters News Articles.Storing the index in a database offers the benefit of  using the B-Tree data structure offered by a relational database instead of building it from  the scratch.  

Natrual lanaguage processing is applied to clean the text and invert the text data into tf-idf index using Python libraries(nltk,re, bs4, collections). Two datasets are given; a real one from Reuters which contains more than 19,000  documents, and a small sample of 5 documents in order to help with testing the code. 

# Interface for keyword searching and ranking the most relevant results by TF-IDF
![Database Query Result](https://github.com/JennyYu2017/Big-Data-and-NLP-Inverted-Index-Database-for-19-000-Reuters-News-Articles/blob/master/Database%20query%20result.png)




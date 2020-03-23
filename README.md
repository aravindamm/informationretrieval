Project Name: Information Retrieval using NLP
Objective:  To retrieve the Top 5 question and Answers based on text search from the corpus with rankings (Probabilities)
Tools: Python, Python Flask, Github and Heroku
Techniques: NLP (Information Retrieval using Whoosh Package)
Analysis and Model building process:
JSON File is provided as a data source. Parsed the JSON file into data frame to do further exploratory data analysis. Used various statistical/mathematical techniques to bring out meaningful insights and performed EDA to develop meaningful insights from raw dataset. Identified various patterns in data and extracted the top topics of the corpus. Implemented BM25F algorithm to retrieve top scored 5 questions and answers based on tf-idf along with bunch of factors like length of document in words, average length of documents in the collection. Deployed the search engine using  flask and heroku

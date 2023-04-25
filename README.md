# Twitch-Features-Analysis-
The project is about visualizing and detecting if a Twitch account is mature or not.

**Database**
Neo4j is being used for the visualization of the data. Neo4j has its own flaws like, certain limit to create relations amongst the graph and could take around 2,00,000 nodes in one instance. Neo4j allows users to create a graph from scratch or build a graph using files of different format. The interface of Neo4j is user-friendly. Different nodes are represented by different colors. One can even write queries to retrieve information from a graph. Neo4j uses Cypher query language which is easy and powerful to use. Neo4j supports drivers for .Net, Java, JavaScript, Go and Python.

**Dataset**
The dataset is about the features of Twitch (streaming platform). The dataset was in the form of a csv file and had 1,68,114 rows and 9 columns. Some features on which we worked were the ‘life time’ of any account, if the account is a ‘dead’ or active account, when was the account ‘created’ and ‘updated’ at, if the account is a ‘mature’ account or not. These are some of the major features used by twitch in order to keep track of the user. Since the database used here in Neo4j and it supports Python, therefore it gives an advantage to use a csv file to work with. The relationships were built from scratch using the information given in csv file. The quality of the dataset is reliable. As the number of observations is much greater than the number of features in the dataset, thus the dataset is high dimensional.

**SVM**
The use of SVM was to find put whether an account is mature or not. Twitch has a feature names "mature". An account is said to be mature if it holds explict content and has strong language. SVM returned an accuracy of 60%. 

A screenshot attached of how the visualization of the dataset takes place on Neo4j. 
![bloom-visualisation_twitch](https://user-images.githubusercontent.com/76148792/234259838-98e51d90-2513-41fd-a26f-abde0ff82f64.png)


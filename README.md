# Neo4j_GraphDatabase
This project populates a Neo4j Graph Database using a collection of records on companies and executes various search queries against the database to extract meaningful insights. 

### Preperation
- A new Jupyter Notebook is created.
- Neo4j is setup and the necessary Python package is installed.
- Jupyter Notebook is used to import data and establish node relationships.

### Visualization:
Cypher commands are used for direct data manipulation and to visualize the following:
- Which companies are located in the state of California (via 2nd degree relation)?
- Which companies were founded in the last quarter of the 20th century [1975-2000]?
- What is the average annual revenue for all companies in the USA?
- Which companies are headquartered in Japan (via 3rd degree relation)?
- What is the total number of employees for all companies in the USA and Germany (via 3rd degree relation)?

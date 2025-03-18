# rdfs-in-neo4j

Project developed for the course of "Data Management" during the MSc in Artificial Intelligence and Robotics at Sapienza University of Rome, A.Y. 2023-2024.


## Summary

Implementation of 2 class structures representing RDFS-based Knowledge Graphs. The first version uses a Neo4J Session to perform updates, syntax check and deduction directly on the graph through queries in Cypher. The second version performs these operations in Python and is able to interact with a Neo4J Session for importing/exporting Knowledge Graphs.


## Requirements

The program requires the Neo4j Driver library for Python to interact with a Neo4j database. You can install it using pip: ```pip install neo4j```

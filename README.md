# Knowledge Graph for Napoleon History Using Neo4j

This project is divided into two main parts:

1. **Designing the Knowledge Graph and Ingesting Data**
2. **Retrieving Data from the Knowledge Graph**
To clone this repository, run:
```
git clone https://github.com/homayounsr/Knowledge-Graph-for-RAG-using-Neo4j
```

Install Poetry if you haven't already:
```
pip install poetry
```

Then, install the project dependencies:
```
poetry install
```
Use main.py to run the application

### Using Your Own Data
If you want to use your personal data, follow these steps:

1. Place your raw data into the Data folder.
2. Clean the data using the preprocessing script.
3. Convert the cleaned text data to JSON using the text2json script.
4. Design your custom knowledge graph by modifying the Nodes_and_Relationships.ipynb notebook in the knowledge_graph folder.
5. Use the generated JSON file as input for your knowledge graph.
6. Modify Chunking.py to chunk your file and extract properties from it
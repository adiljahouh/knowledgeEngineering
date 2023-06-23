## How to get setup
- Git clone the repository
- In the terminal of the repository create an environment (conda or venv) using python 3.11 (conda create --name knowledgeEngineering python=3.11)
- Activate the environemnt (conda activate knowledgeEngineering)
- Run ```pip install -r requirements.txt```
- navigate to new-recipe-code
- run the cells within rdf.ipynb


## Further info
The Preprocessing.ipynb preprocesses the recipes by using AH data, a translator, a simplifier dataset etc.
This file returns the /dataset/final.csv file which is used in rdf.ipynb for the knowledge graph.

# The extraction of protein complexes from PPI networks using metaheuristics.
In this project we propose several metaheuristic approaches: the genetic algorithm (GA), tabu search (TS), cuckoo search (CS), and a hybrid method combining GA and TS (GA\_TS).


## Introduction
The main problem is extracting subgraphs which are highly connected (maximize inter-connections) and minimize the intra-connections from protein-protein interaction networks.  

## Requirements
- Python 3.9.x
- Required libraries: [NumPy](http://www.numpy.org), [pandas](https://pandas.pydata.org) and
[xml.etree.ElementTree](https://github.com/python/cpython/blob/3.12/Lib/xml/etree/ElementTree.py) 

### Research Paper
The objective function and the first representation of the solution implemented in this project are based on the following research paper:

**Title**: [PPI-GA: A Novel Clustering Algorithm to Identify Protein Complexes within Protein-Protein Interaction Networks Using Genetic Algorithm]  
**Authors**: [Shirmohammady, Naeem and Izadkhah, Habib and Isazadeh, Ayaz]  
**Publication**: [Complexity]  
**Year**: [Published 25 March 2021]  
**Link**: [[URL to the Research Paper](https://www.researchgate.net/publication/350392631_PPI-GA_A_Novel_Clustering_Algorithm_to_Identify_Protein_Complexes_within_Protein-Protein_Interaction_Networks_Using_Genetic_Algorithm)]

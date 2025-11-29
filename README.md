

# Computational Tools for Data Science – Project Overview

Authors
<table> <tr> <td align="center"><strong>Andreas Rosenquist</strong><br>s214604@dtu.dk</td> <td align="center"><strong>Liv Cæcilie Dreyer</strong><br>s214613@dtu.dk</td> <td align="center"><strong>Karoline Klan Hansen</strong><br>s214638@dtu.dk</td> <td align="center"><strong>Renato Silva</strong><br>s250675@dtu.dk</td> </tr> </table>

## **00 Contents**


The goal of this project is to investigate communication patterns, user connectivity, and language dynamics within online incel communities using a combination of network analysis and text mining.  
The project consists of **seven main notebooks**, please read them in the following order:

### **[01_DataPreparation.ipynb](01_DataPreparation.ipynb)**  
- Prepares and cleans the dataset, extracts relevant fields, and ensures the data is ready for further analysis.

### **[02_GraphCreation.ipynb](02_GraphCreation.ipynb)**  
- Builds the user–user interaction graph, assigns metadata, and stores subreddit origins.

### **[03_NetworkAnalysis.ipynb](03_NetworkAnalysis.ipynb)**  
- Performs structural network analysis: degree distribution, cantrality measures, and Louvain community detection.

### **[04_CommunityWordclouds.ipynb](04_CommunityWordclouds.ipynb)**  
- Uses TF-IDF and word clouds to explore the dominant vocabulary within each Louvain community.

### **[05_SemanticClustering.ipynb](05_SemanticClustering.ipynb)**  
- Clusters posts based on semantic similarity using sentence embeddings and HDBSCAN.

### **[06_FrequentItemsLouvain.ipynb](06_FrequentItemsLouvain.ipynb)**  
- Applies frequent itemset mining to uncover co-occurring terms within each Louvain community.

### **[07_FrequentItemsDBScan.ipynb](07_FrequentItemsDBScan.ipynb)**  
- Performs the same frequent itemset analysis on the semantic clusters derived from HDBSCAN.

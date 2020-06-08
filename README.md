# Inductive Graph Representation Learning for Fraud Detection
This repository contains the code used in the experimental setup of the paper 'Inductive Graph Representation Learning for Fraud Detection. 

# Abstract
Graphs can be seen as a universal language to describe and model a diverse set of complex systems and data structures. However, efficiently extracting topological information from dynamic graphs is not a straightforward task. Previous works have explored a variety of inductive graph representation learning frameworks, but despite the surge in development, little research deployed these techniques for real-life applications. Most earlier studies are restricted to a set of benchmark experiments, rendering their practical generalisability questionable. Our paper evaluates the proclaimed predictive performance of state-of-the-art inductive graph representation learning algorithms on highly imbalanced credit card transaction networks. More specifically, we assess the inductive capability of GraphSAGE and Fast Inductive Graph Representation Learning in a fraud detection setting. Credit card transaction fraud networks pose two crucial challenges for graph representation learners: First, these networks are highly dynamic, continuously encountering new transactions. Second, they are heavily imbalanced, with only a small fraction of transactions labeled as fraudulent. Our paper contributes to the literature by (i) proving how inductive graph representation learning techniques can be leveraged to enhance predictive performance for fraud detection and (ii) demonstrating the benefit of graph-level undersampling for representation learning in imbalanced networks.

# Experimental Pipeline
<img src="https://github.com/Charlesvandamme/Inductive-Graph-Representation-Learning-for-Fraud-Detection/tree/master/Figures/experimental_pipeline.JPG?raw=true"/>

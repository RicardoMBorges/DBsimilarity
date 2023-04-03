# DBsimilarity

DBsimilarity is a method proposed in a scientific paper to help natural product researchers analyze chemical data obtained from databases. This method involves organizing structural databases into similarity networks to represent the chemical space of a given organism or biological system. The method includes various steps such as converting .sdf files into .csv files, adding chemoinformatics data, constructing a custom database for rapid dereplication of MS data on MZMine, constructing a candidate list of compounds for rapid dereplication of 2D NMR data on NMRfilter, calculating similarities between compounds, and convert this square matrix into a network type of file. Cytoscape is suggested as an ideal platform for visualizing similarity networks, and Jupyter Notebooks are recommended for their readability to assist users in developing valuable programming skills. The ultimate goal of this method is to help researchers better understand the rich information available from a list of compounds found in a specimen. 


## Tutorial
1. Install Jupyter Notebook following their installation guide at https://docs.anaconda.com/anaconda/install/index.html

2. Install RDKit following their installation guide at https://www.rdkit.org/docs/Install.html
  a. users will be suggested to create an environment for RDKit
  b. users must install all the dependencies inside the newly created RDKit environment

3. Then, from the Anaconda Prompt, type: 
  * cd [_environment name_]/bin
  * source activate
  
4. Open Jupyter Notebook 
  * Users might want to open Jupyter Notebook directly on the directory they want to work on
  a. to open Jupyter Notebook on a specific directory, users can type: jupyter notebook [e.g. D:\Github || _desired path_]

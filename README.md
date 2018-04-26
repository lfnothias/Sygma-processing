# Sygma-processing

## About
This jupyter notebook uses RDKit and SyGMA library to predict the potential metabolites of a given parent structure."
Note that several filters are used for input library (no stereochemistry, smaller and larger compounds removed, only organic compounds)

SyGMA paper "SyGMa: combining expert knowledge and empirical scoring in the prediction of metabolites."
Ridder, L. and Wagener, M. (2008), SyGMa: Combining Expert Knowledge and Empirical Scoring in the Prediction of Metabolites. ChemMedChem, 3: 821-832. doi:10.1002/cmdc.200700312

SyGMA python library
https://github.com/3D-e-Chem/sygma

## Installation
- Upload the notebook on the labshare server. Select either SMILES [recommended] or InChI input notebooks.
- In the notebook, select the kernel "rdkit_sygma"
- Upload your database input file(s)

## Running the notebook
### Prepare your input database
The headers for the SMILES and InChI have to be named "SMILES" and "InChI".
### Modify the notebook following the comments
Change the filename of the database imported
Change the number of database imported
Change the output file
### Define SyGMA scenario
The number of reaction at each SyGMA can be set. It is 1 for Phase I and Phase II by default.
### Set the output filename
Run the workflow. Note that it can take several hours for large database

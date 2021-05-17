# MLADDBA
Module 2 -- Machine learning with protein data


Context
This module in MLADDBA workshop is intended to provide an introduction to machine learning and its applications with proteinbiology (proteiomics) and computational biologists. This session targets biologists or life scientists who want to understand machine learning, what it can do and how it can be used for a variety of bioinformatic specifically in terms of accessing and predicting protein structure. Attendees will gain experience in the following 
    Module 2: Introduction to machine learning (Lecture cum Hands-on session)<br>
● Protein data handeling using Jupyter(Python)<br>
● Examples of machine learning in protein bioinformatics<br>
● Brief introduction to machine learning methods including<br>
● decision trees and random forests<br>
● support vector machine

This is a protein data set retrieved from Research Collaboratory for Structural Bioinformatics (RCSB) Protein Data Bank (PDB) and Kaggle.

The constantly-growing PDB is a reflection of the research that is happening in laboratories across the world. This can make it both exciting and challenging to use the database in research and education. Structures are available for many of the proteins and nucleic acids involved in the central processes of life, so you can go to the PDB archive to find structures for ribosomes, oncogenes, drug targets, and even whole viruses. However, it can be a challenge to find the information that you need, since the PDB archives so many different structures. You will often find multiple structures for a given molecule, or partial structures, or structures that have been modified or inactivated from their native form.

Prerequisites installation:
All of the work here is done using Jupyter, which can be installed easily using the following:
https://test-jupyter.readthedocs.io/en/latest/install.html

BioPandas requires the following software and packages:
Python 2.7, 3.5, or 3.6
NumPy >= 1.11.2
SciPy >= 0.18.1
Pandas >= 0.19.1

Versions of biopandas are now also available via conda-forge; you can install it via
conda install biopandas -c conda-forge
or simply,
conda install biopandas

Content
There are two data files. Both are arranged on "structureId" of the protein:
pdbdatano_dups.csv contains protein meta data which includes details on protein classification, extraction methods, etc.
data_seq.csv contains >400,000 protein structure sequences.

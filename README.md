DeltaVina
======

A scoring function for rescoring protein-ligand binding affinity.

Project Organization
------------
    ├── LICENSE
    ├── README.md          <- README file.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── bin                <- Master script to run deltavina
    │   └── dvrf20.py
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   ├── pharma.py  
    │   │   ├── featureSASA.py 
    │   │   ├── featureVina.py 
    │   │   └── tests
    │   │
    │   └── models         <- Trained model rffit.rda and scripts to run model
    │       ├── rffit.rda
    │       ├── modelDV.py
    │       └── tests
    │
    └── examples           <- Examples


How to use
-------
Please see the DeltaVinaTutorial.pdf or visit http://www.nyu.edu/projects/yzhang/DeltaVina



Reference
---------
Cheng Wang, and Yingkai Zhang, J. Comput. Chem. 2017, 38, 169-177.

[Improving Scoring-Docking-Screening Powers of Protein–Ligand Scoring Functions using Random Forest](http://onlinelibrary.wiley.com/doi/10.1002/jcc.24667/abstract)
    

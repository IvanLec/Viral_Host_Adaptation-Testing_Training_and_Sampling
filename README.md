# Viral_Host_Adaptation-Testing_Training_and_Sampling
This repository contains a Notebook with trained models to decode the hosts of viral sequences to test new genomes, to train different models with new generic datasets and to sample artificial sequences from them.

The models trained (with full or partial genomes) are restricted to Orthomyxovirade, Coronaviridae, Picornaviridae and Flaviviridae families with human, swine, and avian hosts and could be used to test readers own sequences belonging to these virus/host combinations.

As a generalization for readers, an example of how to train models and test for any generic viruses and hosts datasets is shown, as well as sampling from them artificial sequences. 


### File specifications 
The zip file ViralHostAdaptation.zip contains the notebook file NotebookVHA.ipynb from which everything can be run without any additional operation. 
A Notebook_Functions.jl file contains the functions written for the notebook scopes. A folder Trained Models contains .bin files with all the models already trained (more specification in the notebook). 
The Datasets folder consists on random sequences used as trail genomes for test or train.
An additional folder is present and discussed here below.

### Attribution
This repository includes a folder called MENB, with files needed to train models, taken from MaxEntNucleotideBiases.jl (https://github.com/adigioacchino/MaxEntNucleotideBiases.jl), created by Andrea Di Gioacchino. The original work is licensed under Mozilla Public License 2.0.

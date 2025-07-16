# Viral_Host_Adaptation-Testing_Training_and_Sampling
This repository contains a Notebook with trained models to decode the hosts of viral sequences to test new genomes, to train different models with new generic datasets and to sample artificial sequences from them.

The models trained (with full or partial genomes) are restricted to Orthomyxovirade, Coronaviridae, Picornaviridae and Flaviviridae families with human, swine, and avian hosts and could be used to test readers own sequences belonging to these virus/host combinations.

As a generalization for readers, an example of how to train models and test for any generic viruses and hosts datasets is shown, as well as sampling from them artificial sequences. 


### File specifications 
1 The zip file "ViralHostAdaptation.zip" contains all the files needed to run the scripts. Inside it, the files have been organized as follows: 

1.1 A notebook file "NotebookVHA.ipynb" from which everything can be run once all packages have been installed. 

1.2 A Notebook_Functions.jl file contains the functions written for the notebook scopes. 

1.3 A folder "Trained Models" contains bin-files with all the models already trained (more specification in the notebook). 

1.3 The "Datasets" folder consistsing on random sequences used as trail genomes for test or train in the notebook.

1.4 A "DatasetsSpecifications" folder has been added to show the specification (and acces codes) of the datasets shown in Suppl. Figs. 1,2. of the paper presented in the below section "Citation".

1.5 An additional folder is present and discussed here below.

### Attribution
This repository includes a folder called MENB, with files needed to train models, taken from MaxEntNucleotideBiases.jl (https://github.com/adigioacchino/MaxEntNucleotideBiases.jl), created by Andrea Di Gioacchino. The original work is licensed under Mozilla Public License 2.0.

### Citation 
In case of use, please cite: "Andrea Di Gioacchino, Ivan Lecce, Benjamin D Greenbaum, Rémi Monasson, Simona Cocco, Deciphering the Code of Viral-Host Adaptation Through Maximum-Entropy Nucleotide Bias Models, Molecular Biology and Evolution, Volume 42, Issue 6, June 2025, msaf127, https://doi.org/10.1093/molbev/msaf127"

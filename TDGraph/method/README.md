### Intro

-----------

This is the code that is used as reference material, which contains the dataset, body model, validation metrics and other materials that you can find in the corresponding folders.  

The corresponding code runtime dependencies are given in the requirements.txt file as a reference.  

It is recommended to use the commonly used SMILES/FASTA data and Graph Transform processing methods for the corresponding type of datasets, and you can use MSE loss for model training.

### Drug–target affinity prediction method based on multi-scale information interaction and graph optimization

-----------

Drug–target affinity (DTA) prediction as an emerging and effective method is widely applied to explore the strength of drug–target interactions in drug development research. By predicting these interactions, researchers can assess the potential efficacy and safety of candidate drugs at an early stage, narrowing down the search space for therapeutic targets and accelerating the discovery and development of new drugs. However, existing DTA prediction models mainly use graphical representations of drug molecules, which lack information on interactions between individual substructures, thus affecting prediction accuracy and model interpretability. Therefore, transformer and diffusion on drug graphs in DTA prediction (TDGraphDTA) are introduced to predict drug–target interactions using multi-scale information interaction and graph optimization. 

#### DataSets

----------

The dataset used in this paper is KIBA，Davis, Metz and full_toxcast. The way to obtain the above datasets is given in the data file.

#### Requirement

-------------------

This article is implemented by Pytorch.

1. PyTorch 1.7.1
2. Some other libraries are listed in the requirements file.

#### Cite

----------------------------------------------

@article{ZHU2023107621,
title = {Drug–target affinity prediction method based on multi-scale information interaction and graph optimization},
journal = {Computers in Biology and Medicine},
volume = {167},
pages = {107621},
year = {2023},
issn = {0010-4825},
doi = {https://doi.org/10.1016/j.compbiomed.2023.107621},
url = {https://www.sciencedirect.com/science/article/pii/S0010482523010867},
}

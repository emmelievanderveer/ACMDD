# Workflow for the Identification of Novel Inhibitors for ABL1
**Authors**: Emmelie van der Veer, Lichelle Yeung, Ruben van Delden, Richard Salomons, Maximilian Falkner
![Picture3](https://github.com/user-attachments/assets/57c13da9-b41b-4f96-ba17-989d2f68ecb0)

This project describes the workflow for identifying chemically diverse and novel tyrosine kinase inhibitors targetting ABL1 for treating chronic myeloid leukaemia. Our work here includes QSAR modelling, virtual screening, clustering and docking based on the methods described in TeachOpenCADD (Sydow, D. et al. TeachOpenCADD 2022: open source and FAIR Python pipelines to assist in structural bioinformatics and cheminformatics research. Nucleic Acids Res 50, (2022).)

In the folder "Notebooks" one can find two Jupyter Notebooks providing the code used in this project.

In the notebook "QSAR modelling" one can find code to train and optimize a regression model for predictions of bioactivities for ABL1. Moreover, the model can be used to screen an imported dataset, in this example from the ZINC15 database, and select a final set of candidates based on chemical diversity, novelty and drug-likeness. 

The notebook "Docking" fits the top-ranked compounds into the ATP-binding site of the '1OPJ' crystal structure, providing insights into important protein-ligand interactions. 
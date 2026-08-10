# Systematic screen of PKR reveals genetic variants that evade diverse viral pseudosubstrate inhibitors

Characterization of human PKR missense variants in the context of viral pseudosubstrate antagonists.

Authors: Michael Chambers, Tristan Grieve, Sophia Scobell, and Meru Sadhu.

This project builds from our [previous work](https://elifesciences.org/articles/99575) characterizing single-residue missense variants of PKR in the context of vaccinia virus K3. Here, we extend this work to screen our PKR variant library against several diverse K3 orthologs: vaccinia virus K3, variola virus C3, tanapox virus K3, myxoma virus M156R, and the independently derived ranavirus vIF2α antagonist. We identified PKR variants that are broadly protective against all five viral antagonists, as well as variants with trade-offs.  This repo provides the code and results used for the analysis and figures included in the manuscript.  

Briefly, our analysis can be divided into three portions: (1) design of primers to generate PKR variants, (2) linking PKR variants to genetic barcodes, and (3) analysis of the PKR library screen against vaccinia K3.  Most figures were generated from the data file `data/barseq/combined_grouped-barcodes_241120.csv`, Jupyter notebooks and the conda environment for analysis are available in the `notebooks` directory.  

```
dms_human-pkr_k3-orthologs
├── data - contains primary input files for data analysis and figures
├── figures - .ai files used for manuscript figures
├── notebooks - Jupyter notebooks used for data analysis and figures
├── plasmids - .gb plasmid maps used in this project
├── predicted_structures - AlphaFold2-Multimer structure predictions
└── README.md
```

Conda environment: ```conda env create -n bio_env -f notebooks/bio_env.yaml``` 

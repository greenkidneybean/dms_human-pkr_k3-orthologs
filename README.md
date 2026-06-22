# Systematic screen of PKR reveals genetic variants that evade diverse viral pseudosubstrate inhibitors

Characterization of human PKR missense variants in the context of viral pseudosubstrate antagonists. 

Authors: Michael Chambers, Tristan Grieve, Sophia Scobell, and Meru Sadhu.

This project builds from our previous work characterizing single-residue missense variants of PKR in the context of vaccinia virus K3. Here, we extend this work to screen our PKR variant library against several diverse K3 orthologs: vaccinia virus K3, variola virus C3, tanapox virus K3, myxoma virus M156R, and the independently derived ranavirus vIF2α antagonist. We identified PKR variants that are broadly protective against all five viral antagonists, as well as variants with trade-offs.  This repo provides the code and results used for the analysis and figures included in the manuscript.  

Briefly, our analysis can be divided into three portions: (1) design of primers to generate PKR variants, (2) linking PKR variants to genetic barcodes, and (3) analysis of the PKR library screen against vaccinia K3.  Most all figures were generated from the file `results/barseq/pkr-variant-reads_240228.csv` and Jupyter notebooks for analysis are in the `workflow` directory.  

```
dms_human_pkr
├── data
├── figures - files used to generate figures for the manuscript
├── plasmids
├── results
├── structure_predictions
├── extended_data - supplemental files for manuscript
└── workflow - code and environment files used for data analysis and figures
```

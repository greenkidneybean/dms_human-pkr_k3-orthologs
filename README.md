# Systematic screen of PKR reveals genetic variants that broadly evade divergent viral pseudosubstrate inhibitors

Authors: Michael Chambers, Tristan Grieve, Sophia Scobell, and Meru Sadhu.

This project builds from our [previous work](https://elifesciences.org/articles/99575) to characterize missense variants of PKR in the context of 5 viral pseudosubstrate antagonists: vaccinia virus K3, variola virus C3, tanapox virus K3, myxoma virus M156R, and the independently derived ranavirus vIF2α antagonist. We identified PKR variants that are broadly protective against all five viral antagonists (Fig. 5), as well as variants with divergent effects (Fig. 6).  This repo provides the figures, results, and code used for the manuscript.

The primary results file is `data/barseq/combined_grouped-barcodes_241120.csv`, with Jupyter notebooks and the conda environment for analysis are available in the `notebooks` directory.  

```
dms_human-pkr_k3-orthologs
├── data - contains primary input files for data analysis and figures
├── figures - .ai files used for manuscript figures
├── notebooks - Jupyter notebooks used for data analysis and figures
├── plasmids - .gb plasmid maps used in this project
├── predicted_structures - AlphaFold2-Multimer structure predictions
├── manuscript_submission_260807
└── README.md
```

Conda environment: ```conda env create -n bio_env -f notebooks/bio_env.yaml```

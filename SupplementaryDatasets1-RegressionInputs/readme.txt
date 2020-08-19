This folder contains all the processed datasets from the meta-analysis described in Palmer et al. 2020.

The file "Database.HumanMouseRatOrthologsEntrezGenes" contains the mappings of the mouse and rat genes to there human homologs, as used in the paper.

All other files are expression matrices, where the first row gives the sample IDs, the second row gives the age (years for human, months for mouse or rat) and the first column gives the genes (Entrez IDs).

The expression data type depends on the study, please refer to the study accession in the ncbi database for the data type. RNAseq data are given as either log2 RPKM or log2 FPKM depending on the study.


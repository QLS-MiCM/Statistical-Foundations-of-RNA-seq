## Coding Notebook

Here you can find the R notebook (.Rmd file) that demonstrates the concepts from the workshop as well as a diffrential gene expression analysis example using edgeR package.

The folder contains two subfolders: Data and Scripts. The Scripts folder contains two R notebooks, and the Data folder contains the two data files: one is the actual count matrix, the other is the correspondence between geneID and gene names. After downloading them, please make sure the two data files are placed in the same folder as the R notebook when running the R code.

For the two R notebooks in the Scripts folder, there is GLMforRNAseq_1.Rmd that is meant to be opened and went through first. I made an intentional mistake for pedagogical purpose (at the normalization step), which gets commented on and fixed in GLMforRNAseq_2.Rmd. Additionally, GLMforRNAseq_2.Rmd also includes the PCA plot using log count, as well as volcano plot.

Data source: https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE53697

Scheckel C, Drapeau E, Frias MA, Park CY et al. Regulatory consequences of neuronal ELAV-like protein binding to coding and non-coding RNAs in human brain. Elife 2016 Feb 19;5. PMID: 26894958

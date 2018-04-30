# Additional-File-6
Additional File 6 


Additional File 6
Introduction
This github repository includes R software codes used for a study on the evaluation of 25 differential gene expression pipelines for RNA-sequencing data (particularly for mRNA and lncRNA). Fourteen popular DGE tools are considered in our study. All considered tools are popular (in terms of number of citation) and available on R software packages. All of them start from gene or transcript level read counts. Most methods were applied using their default settings, except for DESeq2 and PoissonSeq which required certain settings to be changed to avoid filtering out too many low abundant genes (such as lncRNA). In particular, in DESeq2 the independent filtering was disabled in the results() function, and in PoissonSeq the filter cutoffs for the sum and average counts of genes across samples were set to 1 and 0.01, respectively. All DE tools were applied at the nominal 5% FDR level, unless mentioned otherwise. All computations were performed in R version 3.3.2. baySeq was not included in the simulation study due to its slow computation time.


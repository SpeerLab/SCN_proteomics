# SCN_proteomics
## author: Theresa Alexander
## reesyxan@umd.edu

This repository contains code used to complete bioinformatic analyses for SCN Proteomics 
(conducted by the Nemes and Speer labs at UMD)

"Microanalytical Mass Spectrometry With Super-resolution Microscopy
Reveals a Proteome Transition During Development of the Brain’s
Circadian Pacemaker"


This repository contains the R markdown document which contains the code used to 
obtain results as well as an html document which contains the knitted results of
the R markdown to visualize output.


We first use the "MetaboAnalystR" package using their standard pipeline to read 
data in, normalize and filter, calculate PCA projections and visualize sample 
and gene loadings, and compute differential expression (DE) analysis.

We also compute heatmaps across the genes with the largest fold changes from the 
DE analysis, a correlation dot plot across all samples, and perform gene set 
enrichment analysis using the "gProfileR" package. 


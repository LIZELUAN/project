# project
This code is about scRNA analysis of prostate cancer for my research project.
The data used is the gene expression matrix of scRNA data of prostate cancer tumours.
The analysis includes tSNE view and cell communication analysis.

Cell communication analysis starts from the preparation of meta.txt and count.txt.
count_network.txt comes from the cellphonedb command output on linux server.
I refer to some of the related code available on web and want to show my thanks!

The order:
1. Data preprocess & cell clusters.Rmd
2. Data preparation for aEC network.Rmd
3. Command for cellphonedb
4. cell network.Rmd

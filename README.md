# RNA-sequencing - Technology Report
In this repository I am storing the data and the code used to produce the RNA-seq analysis I did to fulfill the requirements of the "Advanced Technology Report in Bioscience". 

In the code folder, the rmd file "How to perform RNA-sequencing" goes through each required step to analyze RNA-seq data. The script assumes the user already generated the gene counts. A limma-based approach combined with Voom transformation is used to perform differencial gene expression (DGE) analysis. Finally the output of the DGE is used to perform a gene set analysis (GSA) with the PIANO package. 

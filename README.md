# pigeon_ampulla_scRNA-seq
This repository contains Raw single cell RNA seq data, Seurat objects and R code for analysis and figure generation for the pigeon magnetic circuit single-cell RNA-sequencing project.

FastQ : Paired end reads from the 2 sublibraries of cDNA from 10k and 5k pigeon ampullary cells

Parse_Matrix

RDS_files
This repository contains analysed single cell RNA seq data using Seurat V‘4.1.3’.
E1APM :  QC, log normalised and clustered data object created from all transcripts aligned to the cliv1.0 reference genome using splitpipe v1.0.6
haircells_merged_object: Haircell subset from all transcripts 
E1APM.markers.rds: Top 100 DEGs of cell clusters

E1APM3 : QC, log normalised and clustered data object created from only 3' transcripts aligned to the cliv1.0 reference genome using splitpipe v1.0.6 
haircells_before_clustering_3p: Haircell subset of only 3' transcripts (used to compare gene expression of voltage gated ion channels in hair cells)

R scripts: R code for analysis and figure generation

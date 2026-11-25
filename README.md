# RNA_Pipeline

__Dataset:__

(https://www.10xgenomics.com/welcome?closeUrl=%2Fdatasets&lastTouchOfferName=3k%20PBMCs%20from%20a%20Healthy%20Donor&lastTouchOfferType=Dataset&product=atera&redirectUrl=%2Fdatasets%2F3-k-pbm-cs-from-a-healthy-donor-1-standard-1-1-0)

This dataset was collected from single-cell RNA sequencing (scRNA-seq) of peripheral blood mononuclear cells (PBMCs) from healthy donor blood samples. 

__Project Overview:__

ScRNA-seq enables the identification of individual cell populations within a sample instead of measuring average gene expression across all cells, as done with bulk RNA sequencing. This project focuses on utilizing the Seurat package in R to perform quality-control filtering, normalization of gene expression data, and Principal Component Analysis (PCA). Feature plots, PCA visualizations, and UMAP projections are used to identify major immune cell populations based on known marker genes.

Questions This Project Seeks to Answer:
- What genes are most variably expressed across cells?
- What are the main cell populations present in the sample?


__Methods:__

Data Cleaning:
- Removed cells that were high outliers for percentage of mitochondrial DNA.
- Normalized gene expression data 

Analysis:
- PCA
- Clustering
- Feature Plot
- UMAP

__Demonstrated Experience:__
- Seurat
- R

__Key Findings:__
- The top 10 most variable genes across cells were (1)PPBP (2)LYZ (3)S100A9 (4)IGLL5 (5)GNLY (6)FTL (7)PF4 (8)FTH1 (9)S100A8 (10)FCER1A
- This sample contains T cells, B cells, NK cells, and monocytes

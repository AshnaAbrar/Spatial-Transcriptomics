** Project Summary

This repository presents a complete and reproducible pipeline for analyzing spatial transcriptomics data, enabling the study of gene expression within the physical structure of tissues.
Unlike traditional RNA-seq, spatial transcriptomics preserves spatial location information, allowing deeper insights into:

* Tissue organization
* Cell–cell interactions
* Disease microenvironments

** Pipeline Overview
Raw Spatial Data
        ↓
Quality Control (QC)
        ↓
Normalization
        ↓
Dimensionality Reduction (PCA, UMAP)
        ↓
Clustering
        ↓
Spatial Analysis (Moran’s I, Neighborhood)
        ↓
Visualization & Interpretation

** Tech Stack
* Python
* Scanpy
* Squidpy
* NumPy / Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

** Key Analyses:

** Quality Control:
* Filtering low-quality spots
* Removing low-expression genes

** Preprocessing:
* Normalization
* Log transformation

** Dimensionality Reduction:
* PCA
* UMAP visualization

** Clustering:
* Identification of spatial domains
* Tissue region segmentation

** Spatial Analysis:
* Spatial autocorrelation (Moran’s I)
* Spatially variable gene detection
* Neighborhood enrichment

** Visualization:
* Spatial gene expression maps
* Cluster overlays
* Embedding plots

** Outputs:
* Spatial clustering maps
* UMAP plots
* Gene expression overlays
* Spatial statistics plots

** Applications:
* Cancer microenvironment analysis
* Tissue architecture studies
* Biomarker discovery
* Spatial omics research

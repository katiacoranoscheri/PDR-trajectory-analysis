# PDR-trajectory-analysis_stromal cluster
Single-cell transcriptomics analysis of proliferative diabetic retinopathy fibrovascular membranes reveals AEBP1 as fibrogenesis modulator

A trajectory analysis on the stromal cluster was performed using Monocle3 workflow. The Seurat object was imported into Monocle data set using the Monocle3 conversion tool function. After calculating size factors and estimating dispersions, differentially expressed genes among clusters along the trajectory were identified
via the “differentialGeneTest.” Monocle tools were used to learn the graph and to order the cells. A UMAP was then generated illustrating the trajectory
across the clusters. 

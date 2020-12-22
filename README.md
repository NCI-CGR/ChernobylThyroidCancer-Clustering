# Chernobyl Thyroid Cancer - Clustering and PCA
## I. Description
Here are the Rmarkdown files for the analyses of clustering and PCA in the Chernobyl Thyroid Cancer study.
## II. Contents
1) totalRNA_tumor_normal_all_cluster.Rmd: Hierarchical clusting of all tumor normal samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
2) totalRNA_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
3) miRNA_tumor_normal_all_cluster.Rmd: Hierarchical clusting of all tumor normal samples using the vst expression data of top 100 most variable microRNAs with the tool the Consensus Cluster Plus
4) miRNA_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the vst expression data of top 100 most variable microRNAs with the tool the Consensus Cluster Plus
5) meth_tumor_normal_all_cluster.Rmd: Hierarchical clusting of all tumor normal samples using the normalized beta value of most variably methylated 3000 cpg islands with the tool the Consensus Cluster Plus
6) meth_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the normalized beta value of most variably methylated 3000 cpg islands with the tool the Consensus Cluster Plus
7) pca_plot_tumors.Rmd: PCA plots of tumor samples excluding samples with unknown drivers. In RNA-seq data, the vst expression of all available genes was used for PCA. In miRNA-seq data, the vst expression of all available miRNAs was used for PCA. In methylation data, the normalized beta value of all available cpg islands was used for PCA. 
## III. Required R packages
1) DESeq2
2) ConsensusClusterPlus
3) ggplot2
4) pheatmap
5) vsn
6) ggthemes
7) scales
8) data.table
9) matrixStats
10) ggfortify

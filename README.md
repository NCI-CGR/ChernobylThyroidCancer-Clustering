# Chernobyl Thyroid Cancer - Clustering and PCA
## I. Description
Here are the Rmarkdown files for the analyses of clustering and PCA in the Chernobyl Thyroid Cancer study.
## II. Contents
1) totalRNA_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
2) miRNA_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the vst expression data of top 100 most variable microRNAs with the tool the Consensus Cluster Plus
3) methylation_tumor_cluster.Rmd: Hierarchical clusting of tumor samples using the normalized beta value of most variably methylated 3000 cpg islands with the tool the Consensus Cluster Plus
4) pca_plot_tumors.Rmd: PCA plots of tumor samples excluding samples with unknown drivers. In RNA-seq data, the vst expression of all available genes was used for PCA. In miRNA-seq data, the vst expression of all available miRNAs was used for PCA. In methylation data, the normalized beta value of all available cpg islands was used for PCA. 
5) totalRNA_tumor_normal_all_cluster.Rmd: Hierarchical clusting of all tumor and normal samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
6) pca_plot_paired_samples_totalRNA.Rmd: PCA plot of tumor-normal paired samples using the vst expression of all available genes
## III. Required R packages
1) [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html)
2) [ConsensusClusterPlus](https://bioconductor.org/packages/release/bioc/html/ConsensusClusterPlus.html)
3) [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)
4) [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html)
5) [vsn](https://www.bioconductor.org/packages/release/bioc/html/vsn.html)
6) [ggthemes](https://cran.r-project.org/web/packages/ggthemes/index.html)
7) [scales](https://cran.r-project.org/web/packages/scales/index.html)
8) [data.table](https://cran.r-project.org/web/packages/data.table/index.html)
9) [matrixStats](https://cran.rstudio.com/web/packages/matrixStats/index.html)
10) [ggfortify](https://cran.r-project.org/web/packages/ggfortify/index.html)
11) [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/index.html)

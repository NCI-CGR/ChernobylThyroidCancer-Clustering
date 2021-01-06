# Chernobyl Thyroid Cancer - Clustering and PCA
## I. Description
Here are the Rmarkdown files for the analyses of clustering and PCA in the Chernobyl Thyroid Cancer study.
## II. Contents
1) [totalRNA_tumor_cluster.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/totalRNA_tumor_cluster.Rmd): Hierarchical clusting of tumor samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
2) [miRNA_tumor_cluster.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/miRNA_tumor_cluster.Rmd): Hierarchical clusting of tumor samples using the vst expression data of top 100 most variable microRNAs with the tool the Consensus Cluster Plus
3) [methylation_tumor_cluster.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/methylation_tumor_cluster.Rmd): Hierarchical clusting of tumor samples using the normalized beta value of top 3000 most variably methylated cpg islands with the tool the Consensus Cluster Plus
4) [pca_plot_tumors.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/pca_plot_tumors.Rmd): PCA plots of tumor samples excluding samples with unknown drivers. In RNA-seq data, the vst expression of all available genes was used for PCA. In miRNA-seq data, the vst expression of all available miRNAs was used for PCA. In methylation data, the normalized beta value of all available cpg islands was used for PCA. 
5) [totalRNA_tumor_normal_all_cluster.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/totalRNA_tumor_normal_all_cluster.Rmd): Hierarchical clusting of all tumor and normal samples using the vst expression data of top 1000 most variable genes with the tool the Consensus Cluster Plus
6) [pca_plot_paired_samples_totalRNA.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Clustering/blob/main/pca_plot_paired_samples_totalRNA.Rmd): PCA plot of tumor-normal paired samples using the vst expression of all available genes
## III. Required R packages
* [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html)
* [ConsensusClusterPlus](https://bioconductor.org/packages/release/bioc/html/ConsensusClusterPlus.html)
* [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)
* [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html)
* [vsn](https://www.bioconductor.org/packages/release/bioc/html/vsn.html)
* [ggthemes](https://cran.r-project.org/web/packages/ggthemes/index.html)
* [scales](https://cran.r-project.org/web/packages/scales/index.html)
* [data.table](https://cran.r-project.org/web/packages/data.table/index.html)
* [matrixStats](https://cran.rstudio.com/web/packages/matrixStats/index.html)
* [ggfortify](https://cran.r-project.org/web/packages/ggfortify/index.html)
* [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/index.html)

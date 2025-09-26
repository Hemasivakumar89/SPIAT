runtime.txt
install.R
install.packages(c("Seurat", "SeuratData", "dplyr", "patchwork", "ggplot2"))
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("SPIAT")

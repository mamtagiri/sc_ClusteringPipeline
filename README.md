# sc_ClusteringPipeline

This is an automated pipeline adapting Seurat algorithms to cluster your set of files by just naming the folder
with the raw matrix files outputted by Cell Ranger.

The output you get is an rds file with your integrated (combining all samples within your folder) Seurat object retaining the sample names.

# sc_ClusteringPipeline

This is an automated pipeline adapting Seurat3.0 algorithms to cluster your set of files by just naming the folder
with the raw matrix files outputted by Cell Ranger.

The output you get is an rds file with your integrated (combining all samples within your folder) Seurat object retaining the sample names.

You can load the .rds file to further plot and visaulize/downstream analysis with the combined model.

You can create multiple plts by uncommenting the functions for plotting

More features for the pipline will be added soon.


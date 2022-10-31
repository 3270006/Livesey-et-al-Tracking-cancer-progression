# Livesey-et-al-Tracking-cancer-progression
The project used a normalization method to track cancer progression with RNA-Seq gene expression in the multi-stage early to advanced-stage cancer development, normalizing advanced-stage expression samples with early-stage.

The project focused on investigating cancer progression through RNA-Seq expression profiles across the multi-stage process of cancer development. A computational normalization method were employed that normalized advanced-stage with early-stage RNA-Seq data. 

The normalization method corrects for genes that display less expression variability in advanced-stage cancer samples but display a high variability in early-stage cancer samples. As a result, more meaningful information is available to differentiate between cancer types based on the differences in gene expression profiles, or cancer progression, from early-stage to advanced-stage cancer. Additionally, many RNA-Seq research projects do not generate normal sequenced samples, therefore, we propose the use of early-stage cancer samples.

To start a project create two gene-by-sample matrices (early-stage and advanced-stage). Where, the rows and columns are composed with the gene expression profiles and samples, respectively. Two binary primary site classification matrices are also created for each gene expression matrix. Where, the rows and columns represents the number of primary sites and the advanced-stage or early-stage cancer samples, respectively. The matrices are used as an input to the normalization method.

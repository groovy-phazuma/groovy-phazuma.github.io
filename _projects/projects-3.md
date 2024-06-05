---
title: "[Research] LiverDeconv: Liver-Specific Deconvolution Model"
excerpt: "We developed a deconvolution method that can accurately predict the proportions of immune cells from bulk RNA-Seq of liver tissues by modeling the cell types specific to the liver tissue. <br/><br/> <img src='/images/LiverDeconv_abstract_3.png' width=500><br/>"
collection: projects
---

We prepared seven mouse liver injury models using small-molecule compounds with known hepatotoxicity and established a dataset with corresponding liver bulk RNA-Seq and immune cell proportions, covering various immune responses. RNA-Seq expression for nine leukocyte subsets and four liver-associated cell types were obtained from the Gene Expression Omnibus (GEO) to provide a reference covering liver component cells. 

Here, we found that the combination of reference cell sets affects the estimation results of reference-based deconvolution methods. We established a liver tissue-specific deconvolution by optimizing the reference cell set for each cell to be estimated. We applied this model to independent datasets and showed that liver-specific modeling focusing on reference cell sets is highly extrapolatable.

The proposed module detection method is available at [https://github.com/mizuno-group/LiverDeconv](https://github.com/mizuno-group/LiverDeconv).
RNA-seq data (fastq files) are available in GEO dataset. The accession number is [GSE237801](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE237801).
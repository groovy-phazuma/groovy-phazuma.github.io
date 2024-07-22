---
title: "[Research] GLDADec: Guided LDA Deconvolution"
excerpt: "We proposed a Guided LDA Deconvolution method, called GLDADec, to estimate cell type proportions by using marker gene names as partial prior information. <br/><br/> <img src='/images/GLDADec_abstract.png' width=500><br/>"
collection: projects
---

Inferring cell type proportions from bulk transcriptome data is crucial in immunology and oncology. Here, we introduce GLDADec (Guided LDA Deconvolution), a bulk deconvolution method that guides topics using cell type-specific marker gene names to estimate topic distributions for each sample. Through benchmarking using blood-derived datasets, we demonstrate its high estimation performance and robustness. Moreover, we apply GLDADec to heterogeneous tissue bulk data and perform comprehensive cell type analysis in a data-driven manner. We show that GLDADec outperforms existing methods in estimation performance and evaluate its biological interpretability by examining enrichment of biological processes for topics. Finally, we apply GLDADec to TCGA tumor samples, enabling subtype stratification and survival analysis based on estimated cell type proportions, thus proving its practical utility in clinical settings. This approach, utilizing marker gene names as partial prior information, can be applied to various scenarios for bulk data deconvolution. 


The source code is available at [https://github.com/mizuno-group/GLDADec](https://github.com/mizuno-group/GLDADec).

Press release is [here](https://www.u-tokyo.ac.jp/focus/ja/press/z0111_00059.html).
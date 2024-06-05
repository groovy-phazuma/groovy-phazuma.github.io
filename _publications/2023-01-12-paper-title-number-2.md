---
title: "NRBdMF: A Recommendation Algorithm for Predicting Drug Effects Considering Directionality"
collection: publications
permalink: /publication/2023-01-12-paper-title-number-2
excerpt: ''
date: 2023-01-12
venue: 'Journal of Chemical Information and Modeling'
paperdoi: 'doi/10.1021/acs.jcim.2c01210'
paperurl: 'https://pubs.acs.org/doi/10.1021/acs.jcim.2c01210'
citation: 'Azuma, Iori, Tadahaya Mizuno, and Hiroyuki Kusuhara. "NRBdMF: A recommendation algorithm for predicting drug effects considering directionality." Journal of Chemical Information and Modeling 63.2 (2023): 474-483.'
---
Predicting the novel effects of drugs based on information about approved drugs can be regarded as a recommendation system. Matrix factorization is one of the most used recommendation systems, and various algorithms have been devised for it. A literature survey and summary of existing algorithms for predicting drug effects demonstrated that most such methods, including neighborhood regularized logistic matrix factorization, which was the best performer in benchmark tests, used a binary matrix that considers only the presence or absence of interactions. However, drug effects are known to have two opposite aspects, such as side effects and therapeutic effects. In the present study, we proposed using neighborhood regularized bidirectional matrix factorization (NRBdMF) to predict drug effects by incorporating bidirectionality, which is a characteristic property of drug effects. We used this proposed method for predicting side effects using a matrix that considered the bidirectionality of drug effects, in which known side effects were assigned a positive (+1) label and known treatment effects were assigned a negative (−1) label. The NRBdMF model, which utilizes drug bidirectional information, achieved enrichment of side effects at the top and indications at the bottom of the prediction list. This first attempt to consider the bidirectional nature of drug effects using NRBdMF showed that it reduced false positives and produced a highly interpretable output.

[Download paper here](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01210)

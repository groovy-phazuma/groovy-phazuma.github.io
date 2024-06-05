---
title: "[Research] NRBdMF: Neighborhood Regularized Bidirectional Matrix Factorization"
excerpt: "We developed a matrix factorization recommendation algorithm that considers the bidirectional nature of drug effects (side effects - indications) and can provide highly interpretable prediction results.<br/><br/> <img src='/images/NRBdMF_abstract_2.png' width=500>"
collection: projects
---

We surveyed studies using matrix factorization to predict drug effects and compared the performance of seven representative methods. Inspired by NRLMF, which showed excellent performance, we proposed NRBdMF and applied it to predict side effects by considering the side effects and indications as positive and negative directions of drug effects. This first attempt using the NRBdMF method showed that it reduced false positives and produced a highly interpretable output.

The proposed module detection method is available at [https://github.com/mizuno-group/NRBdMF](https://github.com/mizuno-group/NRBdMF).

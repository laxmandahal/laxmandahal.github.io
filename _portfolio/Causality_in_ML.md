---
title: "Causal Inference in Machine Learning"
excerpt: "An introduction to advanced methods in Causal Inference using Machine Learning"
collection: portfolio
---

This project was developed as a part of a graduate-level class on Causal Inference at UCLA. Our team looked into various advanced adjustment methods in causal inference to estimate average treatment effect (ATE). We published a detailed report in the form of a Jupyter Book where we start off with fundamentals in computing ATE, the limitations of the standard methods, and highlight the need for advanced methods. Following is a brief breakdown of each chapters:

In the introduction chapter, we clarify the idea or rather theory of "doubly robust" approach in quantifying causality. While highlighting in-built assumptions, we provide a simple mathematical demonstration to show the importance of doubly-robust methods. This chapter is contributed by Nathan.

The second chapter titled "Doubly Robust Method" looks into Augmented Inverse Propensity Weighting (AIPW) and Targeted Maximum Likelihood Estimation (TMLE) as two data-drive approaches to attain doubly-robust estimate of ATE. This chapter is contributed by Sunay. 

The third chapter takes a deeper look into double machine learning (DML) to perform inference. Frisch-Waugh-Lovell (FWL) theorem (or equivalently orthogonalization) is the backbone of DML which makes DML principled enabling it to generate unbiased estimate. It discusses in detail the limitations of AIPW, TMLE, and other similar methods in addition to discussing the advantage and appeal of DML. This chapter is contributed by none other than myself.

The final chapter provides summary of current advancement in research and future directions. This chapter is contributed by Ayush.

Here's a link to the [Jupyter Book](https://laxmandahal.github.io/double_machine_learning/intro.html) which contains example implementation of doubly robust methods. 

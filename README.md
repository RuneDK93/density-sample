# density-sample
This is an implementation of density sampling from the paper "Sampling To Improve Predictions For Underrepresented Observations In Imbalanced Data". 
The approach aims to mitigate the negative impact on predictive performance fro, models on underrepresented observations in imbalanced data.
The goal is to obtain a sample which covers the input space equally. This gives a small reduction in the overall predictive performance of models trained on the sample, but yields a systematically better performance on underrepresented observations and may improve robustness of trained models towards distributional shifts. 

For more information see the papers:

"Sampling To Improve Predictions For Underrepresented Observations In Imbalanced Data"

Link: https://arxiv.org/abs/2111.09065

"Data Representativity for Machine Learning and AI Systems"

Link https://arxiv.org/abs/2203.04706

## Machine Learning-Assisted Identification of Potential Metabolite Biomarkers for Glaucoma Diagnosis through Serum Metabolomic Analysis

This repository contains data & code for the recently accepted ARVOS paper. 
Glaucoma is a prevalent optic neuropathy condition and the leading cause of permanent blindness, significantly impacting the lives of individuals worldwide. In this situation, there is an urgent need for biomarkers associated with glaucoma, which would significantly improve early diagnosis and monitoring of disease progression. Herein, we utilized machine learning algorithms to develop and validate potential metabolite biomarkers for diagnosing glaucoma from metabolomic data.

Metabolite features were detected using Amide-positive, Amide-negative, T3-positive, and T3-negative analytical modes. The compounds were identified with higher confidence subject to biological interpretation. The Random Forest model achieved an accuracy of 0.87, Gradient Boosting achieved an accuracy of 0.83 and Extreme Gradient Boosting achieved an accuracy of 0.70. The Random Forest model exhibited the highest performance, with a permutation test yielding a p-value of 0.019. Then, we identify the most contributed metabolites to glau disease with the Shapley Additive exPlanations (SHAP) analysis for diagnosis purpose.


![Picture 3](https://github.com/jamesleocodes/glauSerum/assets/48637026/50a49d80-80af-4822-8449-1e794425cdd6)

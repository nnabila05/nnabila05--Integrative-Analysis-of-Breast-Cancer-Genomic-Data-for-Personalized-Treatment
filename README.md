# Integrative-Analysis-of-Breast-Cancer-Genomic-Data-for-Personalized-Treatment
The dataset used for this project is called Breast Cancer Gene Expression Profiles (METABRIC), collected from Kaggle. The dataset includes observations from 1904 patients with breast cancer and has 695 attributes, including 31 clinical attributes, a m-RNA level z-score for 331 genes, and mutation information for 175 genes.
Link to the dataset: https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric

## Objective
The primary objectives of this study are to predict patient survival using clinical, and genetic data and to predict the suitability of chemotherapy as a treatment option. Survival Analysis was also done to determine the relationship between clinical characteristics and post-treatment survival.

## Method
The models used for both predictions are  Support Vector Machines, Random Forest and Gradient Boosting methods.

As the dependent varible chemotherapy has a imbalanced distribution, SMOTE and ROSE algorithms are used for resampling and the accuracy after using the two algorithms are compred.

The genetic data is clusterd using k-means and hierarchial clustering algorithms and ARI was calculated to see any association with the labels.

For survavial analysis Kaplan - Meier Survival Curve an Cox's propotional hazard model is used to understand the effects of clinical attributes on survival.

## results
For chemotherapy as a treatment option prediction ROSE method showed a slightly better accuracy. For both algorithms  random forest model showed the highst accuracy.

For death_from_cancer prediction SVM showed the most accuracy.


For overall_survival prediction SVM had the most accuracy.



# CNBM
The classification and network based method pipeline was built to classify features (e.g., parameters, genes, proteins) that are specifically associated with breast invasive carcinoma (BRCA). For that purpose a pipeline was created that can be split into two major parts. The first part constructs a classifier based on a regression model and a support vector machine (SVM) to predict the cancer stage (spreading or non-spreding cancer type) of a patient by evaluation two parameters the number of lymph nodes and the her2/cent17-ratio. The second part evaluates genes that could play a role in this specific type of cancer by considering gene expression data. The same is done for protein expression data. The data for both parts has been derived from the Cancer Genome Atlas (http://cancergenome.nih.gov/).
This pipeline is very specifically design for BRCA because we still try to test which clinical data we can use and which parameters could play a significant role. In a later step we ant to provide this pipeline in a more general version such that it can be used for other cancer types.

Parts of CNBM
=============

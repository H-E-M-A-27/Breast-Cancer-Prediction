# Breast-Cancer-Prediction

### Background  and  motivation: 
<p align="justify">Breast  cancer  is  the  most  prevalent  form  of  cancer,  which  is  also responsible  for  the  highest  number  of  cancer-related  deaths  among  women.  The  American  Cancer Society estimates that about 288,000 women worldwide will be diagnosed with breast cancer in 2022. Cancers are associated with genetic abnormalities. Gene expression measures the level of gene activity in a tissue and gives information about its complex activities. Comparing the genes expressed in normal and diseased tissue can bring better insights about the cancer prognosis and outcomes.</p>

### Project  Goal: 
<p align="justify">Our  goal  is  to  analyze  the  attributes in ourdataset and  find  ones  that  display  a relationship withthe bestchances of surviving a breast cancerdiagnosis. </p>

### Description of work and results: 
<p align="justify">We builtfour machine learning modelsto predict the likeliness of survival, based on the identifiedcriticalattributes. We then compared the results of each of our four models for the bestfit. Our best model and results were usingRandom Forests with variable hyper tuning which achieved an accuracy of 72%.</p>

### Dataset  Description: 
<p align="justify">The  dataset  for  this  analysis  and  prediction  is  called  Breast  Cancer  Gene Expression Profiles (METABRIC) which contains sequencing data of 1,980 primary breast cancer samples with 693 attributes and is found on Kaggle.Of the 693variables, 31 were deemed critical. These included basic  patient  information  such  as  age  at  diagnosis, the  type  of  breast  cancer  surgery if  they  had  one, Booleanvalues for if they had treatments like chemo, radiation, or hormone therapy, as well as if the patient survived, how long they have survived post diagnosis and if they had passed, either from breast cancer or another reason. The other 662 variables are made up ofgenetic mutation information for each patient that can usually be used to predict whether a patient genetically predisposed to get breast cancer or other diseases. However, since allthe patients in this study already have breast cancer, the results from testing those variableswerenotassignificantas it would be given populations that include those that do not have a breast cancer diagnosis(Breast cancer gene expression profiles (METABRIC) 2019).</p>

### Related Work: 
<p align="justify">This project was derived from a dataset collected by Professors Carlos Caldas and Sam  Aparicio  that  started  a  series  of  published  papers  on breast cancer patients and  their  tumors beginning in 2016. </p>

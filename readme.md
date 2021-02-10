This git repository contains the Supplementary Information to the publication 
“Exploring chemical datasets with deep learning techniques – the octanol-water partition coefficient dataset as example”:


-	Exporing_chemical_datasets_DNN_log_P.py

-	Corrections.xlxs

-	Dataset_and_Predictions.xlxs


We used DeepChem library for model development. 
The full code for the DNN development is given 
at the GIT repository of DeepChem https://github.com/deepchem/deepchem. 
Our adapted code is provided here in Exporing_chemical_datasets_DNN_log_P.py.

The dataset for model development was taken from Mansouri et al. [1]. 
We downloaded the dataset at https://github.com/kmansouri/OPERA/blob/master/OPERA_Data.zip. 

Necessary corrections of the data are listed in Corrections.xlxs. 

The finally used dataset and resulting predictions for the dataset 
are listed in Dataset_and_Predictions.xlxs. 

The file also lists the dataset from Martel et al. [2] and the respective prediction results.


1.	Mansouri K, Grulke CM, Richard AM, Judson RS, Williams AJ. An 
	automated curation procedure for addressing chemical errors and 
	inconsistencies in public datasets used in QSAR modelling. 
	SAR QSAR Environ Res 27, 939-965 (2016).

2.	Martel S, et al. Large, chemically diverse dataset of logP 
	measurements for benchmarking studies. Eur J Pharm Sci 48, 21-29 (2013).

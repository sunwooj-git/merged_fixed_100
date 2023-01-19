# MERGED_flexible
- MERGED_flexible method is the regularized regression based imputation model that leverages both the individual-level genotype and the whole blood expression for imputing the tissue-specific transcriptome profile.
- We introduced this method in the study "__Building an optimal predictive model for imputing tissue-specific gene expression by combining genotype and whole blood transcriptome data__" in 2023.
- MERGED_flexible method is the best-working method among all gene expression imputation methods evaluated in our study.
- For the detailed description of MERGED_flexible method, please refer to our study.
- Writer / Maintainer: Sunwoo Jung < s17171717s@gmail.com >


## Notice
- The purpose of this repository is to release the imputation models we generated using MERGED_flexible method for reproducility and transparency of our study.
- Using MERGED_flexible method, we generated the imputation models for 47 human tissues.
- We were unable to release our impuation models for all 47 tissues due to the file size limit of Github repository.
- For now, we released the imputation models for _Adipose Subcutaneous (Rdata file; 717.2MB)_ in this repository.
- Upon request, we will be glad to share all of our models with readers of our study.


## Instruction
- We uploaded the jupyter notebook code named _access_models.ipynb_ along with the _Adipose Subcutaneous.Rdata_ file.
- _access_models.ipynb_ is the R based jupyter notebook and contains the guideline for accessing and exploring the imputation models generated using MERGED_flexible method.
- Below is our recommended instruction .
```
1. Locate the imputaion model file (Here: Adipose Subcutaneous.Rdata) and access_models.ipynb in the same directory.
2. Run the jupyter notebook and follow the codes.
```
- No version dependency is required.
- No need to import additional R functions.

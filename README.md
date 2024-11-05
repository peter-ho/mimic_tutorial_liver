## MIMIC Liver 

This [repository](https://github.com/peter-ho/mimic_tutorial_liver) contains a tutorial walking through steps to implement a model for identifying liver diseases diagnosis based on lab eevents and patient information based on MIMIC-III data.

## Methods

In this tutorial, features are extracted from MIMIC lab events that are related to liver, combining with patient information, features are fed into multiple classification algorithms. AUC ROC and several other metrics are computed to compare the results.

## Results

| Name| AUC-Train| AUC-Validate|
|-----|----------|-----------------------|
|        DecisionTree|  0.88611|    0.881711|
|        RandomForest| 0.903066|    0.897904|
|  LogisticRegression| 0.866879|    0.870065|
|    GradientBoosting| 0.961663|    0.928645|
|   Nearest Neighbors|  0.91832|    0.868384|
|          Neural Net|  0.88466|    0.873903|
|            AdaBoost| 0.882253|    0.885599|
|          GaussianMB|  0.78972|    0.791607|
|                 QDA| 0.830822|     0.83716|


## Citation for MIMIC-III evaluation
Barnes, Joseph Building a model for predicting acute kidney failure based on the mimic-IV clinical database
https://utexas.instructure.com/courses/1404605/modules/items/14200674

Ying, Ding Hospital readmission https://utexas.instructure.com/courses/1404605/files/79146993/download?download_frd=1

## Citation for MIMIC-III data 
MLA	Johnson, Alistair, et al. "MIMIC-III Clinical Database" (version 1.4). PhysioNet (2016), https://doi.org/10.13026/C2XW26.

APA	Johnson, A., Pollard, T., & Mark, R. (2016). MIMIC-III Clinical Database (version 1.4). PhysioNet. https://doi.org/10.13026/C2XW26.

Chicago	Johnson, Alistair, Pollard, Tom, and Roger Mark. "MIMIC-III Clinical Database" (version 1.4). PhysioNet (2016). https://doi.org/10.13026/C2XW26.

Harvard	Johnson, A., Pollard, T., and Mark, R. (2016) 'MIMIC-III Clinical Database' (version 1.4), PhysioNet. Available at: https://doi.org/10.13026/C2XW26.

Vancouver	Johnson A, Pollard T, Mark R. MIMIC-III Clinical Database (version 1.4). PhysioNet. 2016. Available from: https://doi.org/10.13026/C2XW26.

Johnson, A. E. W., Pollard, T. J., Shen, L., Lehman, L. H., Feng, M., Ghassemi, M., Moody, B., Szolovits, P., Celi, L. A., & Mark, R. G. (2016). MIMIC-III, a freely accessible critical care database. Scientific Data, 3, 160035. https://www.nature.com/articles/sdata201635

APA	Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

MLA	Goldberger, A., et al. "PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220." (2000).

CHICAGO	Goldberger, A., L. Amaral, L. Glass, J. Hausdorff, P. C. Ivanov, R. Mark, J. E. Mietus, G. B. Moody, C. K. Peng, and H. E. Stanley. "PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220." (2000).

HARVARD	Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P.C., Mark, R., Mietus, J.E., Moody, G.B., Peng, C.K. and Stanley, H.E., 2000. PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

VANCOUVER	Goldberger A, Amaral L, Glass L, Hausdorff J, Ivanov PC, Mark R, Mietus JE, Moody GB, Peng CK, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
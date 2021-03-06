# Credit_Risk_Analysis

# Overview of the analysis

_Fast Lending is a peer lending services company. This analysis is created using machine learning to predict credit risk. Machine learning is more accurate in identifying qualified candidates for loans, which will lead to lower default rates. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  Credit risk is an inherently unstable classification problem, as good loans easily outnumber risky loans. Using the credit card credit dataset from LendingClub, this analysis oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. To be able to predict credit risk._ 

# Results

# Random Oversampling

* Accuracy score for the model.

<img width="1011" alt="Screen Shot 2021-04-25 at 4 12 34 PM" src="https://user-images.githubusercontent.com/74740339/116008144-109ecf80-a5e1-11eb-8c12-5d57a909b255.png">

* Confusion matrix.

<img width="1009" alt="Screen Shot 2021-04-25 at 4 13 54 PM" src="https://user-images.githubusercontent.com/74740339/116008189-42b03180-a5e1-11eb-906c-073dedacab66.png">


* An imbalanced classification report.

<img width="1011" alt="Screen Shot 2021-04-25 at 4 14 35 PM" src="https://user-images.githubusercontent.com/74740339/116008218-5e1b3c80-a5e1-11eb-869a-7efed8eec449.png">

# SMOTE Oversampling

* Accuracy score for the model.

<img width="1012" alt="Screen Shot 2021-04-25 at 4 16 41 PM" src="https://user-images.githubusercontent.com/74740339/116008269-b6ead500-a5e1-11eb-980c-8bc2fa707805.png">

* Confusion matrix.

<img width="1019" alt="Screen Shot 2021-04-25 at 4 16 53 PM" src="https://user-images.githubusercontent.com/74740339/116008285-c5d18780-a5e1-11eb-98c1-f13dcf5bf889.png">


* An imbalanced classification report.

<img width="1019" alt="Screen Shot 2021-04-25 at 4 17 00 PM" src="https://user-images.githubusercontent.com/74740339/116008303-d681fd80-a5e1-11eb-9c4e-343d8467f8b3.png">

# Undersampling

* Accuracy score for the model.

<img width="1006" alt="Screen Shot 2021-04-25 at 4 20 54 PM" src="https://user-images.githubusercontent.com/74740339/116008399-51e3af00-a5e2-11eb-8016-0cff218c307b.png">

* Confusion matrix.

<img width="1010" alt="Screen Shot 2021-04-25 at 4 21 05 PM" src="https://user-images.githubusercontent.com/74740339/116008406-5dcf7100-a5e2-11eb-83d5-b85789a53a6a.png">


* An imbalanced classification report.

<img width="1007" alt="Screen Shot 2021-04-25 at 4 21 31 PM" src="https://user-images.githubusercontent.com/74740339/116008417-6c1d8d00-a5e2-11eb-8f0d-15a17d1d4948.png">

# Combination (Over and Under) sampling

* Accuracy score for the model.

<img width="1008" alt="Screen Shot 2021-04-25 at 4 27 25 PM" src="https://user-images.githubusercontent.com/74740339/116008566-3927c900-a5e3-11eb-9f4a-865bece3f42f.png">

* Confusion matrix.

<img width="1010" alt="Screen Shot 2021-04-25 at 4 27 33 PM" src="https://user-images.githubusercontent.com/74740339/116008569-3c22b980-a5e3-11eb-8105-ea7f1e11def7.png">


* An imbalanced classification report.

<img width="1019" alt="Screen Shot 2021-04-25 at 4 27 41 PM" src="https://user-images.githubusercontent.com/74740339/116008578-4349c780-a5e3-11eb-9e13-b32ad5a0054d.png">

# Easy Ensemble AdaBoost Classifier results

* Accuracy score for the model.

<img width="1006" alt="Screen Shot 2021-04-25 at 4 33 59 PM" src="https://user-images.githubusercontent.com/74740339/116008749-1813a800-a5e4-11eb-9cec-26cc9b450512.png">

* Confusion matrix.

<img width="1012" alt="Screen Shot 2021-04-25 at 4 34 06 PM" src="https://user-images.githubusercontent.com/74740339/116008751-1a760200-a5e4-11eb-88d4-4cbdb6b47aab.png">

* An imbalanced classification report.

<img width="1007" alt="Screen Shot 2021-04-25 at 4 34 15 PM" src="https://user-images.githubusercontent.com/74740339/116008754-1e098900-a5e4-11eb-8ba9-2d1c51aef945.png">

# Summary 








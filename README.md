# Machine-Intelligence-Project-

The project was done by maintaining the following steps:

## Preprocessing Section: 
The dataset originally (__[Train.csv](https://drive.google.com/file/d/16DKMe3Bq2uRvn6M40NSd-tUKJefOpjbh/view?usp=drive_link)__) had 81 Features. This was reduced to 55 by removing columns that had data less than 90% or 90% single unique value. We considered them as not having significant effects on the dataset. The updated dataset after this stage is (__[Train_update.csv](https://drive.google.com/file/d/1a2UApME1NSnVvwEFezFv1KaDJ-SdX8RP/view?usp=sharing)__). The list of removed Features in this stage is (__[here](https://drive.google.com/file/d/16upVq-TGGOqD9Xdib0i-qCiwL3MfOgvR/view?usp=drive_link)__).

## Em Analysis:
Initially the dataset had few catgorical features which we had to map. After the mapping the dataset was (__[mapped.csv](https://drive.google.com/file/d/1pW2YsZ8erM31H2DjDDrY1vOULVj0hf1Y/view?usp=sharing)__) and the list of elements that are mapped into for each column are (__[here](https://drive.google.com/file/d/1UtQ-f3LI43lNayf8-G3WvgzMznFy6tYb/view?usp=sharing)__). At the end of our EM analysis the dataset is (__[With_EM.csv](https://drive.google.com/file/d/1HZw9nimRv41mcN5RBatclaeUss-DfHka/view?usp=sharing)__).

## Feature Selection (Recursive Feature Elimination):
This gave us rank of important features that we selected. At the end of this stage we selected 25 most important Features. The updated dataset is (__[Final_dataset.csv](https://drive.google.com/file/d/120s3ikdmhucbZvlA7qxqEECew_NYG7m1/view?usp=sharing)__). 

## Model Training:
We considered 4 models for this project, which are,
* Logistic Regression
* Lightgbm
* Random forest
* Neural Network(NN)

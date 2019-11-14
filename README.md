# Breast_Cancer_Classification
A simple machine learning model to classify whether the Breast cancer is benign or malignant. To achieve this, Random Forest Algorithm has been used. Label Encoding has also been used to preprocess the dataset.

## Analysing the Dataset

![Screenshot (162)](https://user-images.githubusercontent.com/44607923/68864268-ddcb8900-0716-11ea-8c32-8e172ca9fed5.png)

Here, we can see that the dataset contains  569 rows and 33 columns.

![Screenshot (160)](https://user-images.githubusercontent.com/44607923/68864485-3b5fd580-0717-11ea-92e3-6a76fa4c3c60.png)
Here, ‘Diagnosis’ is the column which we are going to predict and hence it is the dependent variable , which says if the cancer is M = malignant or B = benign. 

## Data Preprocessing
### Encoding the categorical data
We need to encode the dependent variable into 0's and 1's, where 1 means M (malignant) and 0 means B(benign). It is done using LabelEncoder method from SciKit-Learn library.

![Screenshot (165)](https://user-images.githubusercontent.com/44607923/68865939-a27e8980-0719-11ea-9717-b3d1e5a1e650.png)  ![Screenshot (164)](https://user-images.githubusercontent.com/44607923/68865951-a7433d80-0719-11ea-80aa-acf833e6209e.png)
 
 The images show the dependent variable after encoding.
 
 ### Applying feature scaling
The dataset contains features highly varying in magnitudes, units and range hence, we need to apply feature scaling here. It is done using  StandardScaler method from SciKit-Learn library.
![Screenshot (167)](https://user-images.githubusercontent.com/44607923/68866955-2e44e580-071b-11ea-91d2-e7a35dc3ece5.png)
Data before encoding
![Screenshot (168)](https://user-images.githubusercontent.com/44607923/68867134-57fe0c80-071b-11ea-8069-c259b7605cc9.png)
Data after encoding

## Model Selection
After apply different types of classification, the accuracy for different algorithms was determined using the confusing matrix.



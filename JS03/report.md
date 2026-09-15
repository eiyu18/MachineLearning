# JobSheet 03 - Feature Extraction 

|  | Machine Learning |
|--|--|
| NIM |  244107020181 |
| Name |  Eiyu Azizuly Efendi |
| Class | TI - 3I |

## Lab Summary
## Lab 1: Feature Extraction in Tabular Data (Titanic Dataset)

In this lab, we learned how to prepare data before using it for machine learning. We used the Titanic dataset and processed the data by handling missing values, scaling numerical data, and converting categorical data into numbers. We also created a new feature called FamilySize. After that, we selected the most important features using SelectKBest and used them with Logistic Regression to predict passenger survival.

## Lab 2: TF-IDF Feature Extraction

TF-IDF is a method used to change text into numbers so that it can be processed by a machine learning model. TF-IDF gives a higher value to words that are important in a document and a lower value to words that appear frequently in many documents.

In this lab, we use TfidfVectorizer from the Scikit-learn library. The text documents are processed and converted into a TF-IDF matrix. Each row represents a document, while each column represents a word or feature. The value in the matrix shows how important a word is in a particular document.

## Lab 3: Feature Extraction in Image Data

In this lab, we learned how to extract features from an image using Python and the Pillow library. The image is separated into three color channels: Red, Green, and Blue (RGB). Then, a histogram is used to count how many pixels have each intensity value from 0 to 255. The resulting values can be used as numerical features that help a machine learning system process and analyze images.

## Assignment 

In this lab, we use the Wisconsin Breast Cancer dataset to predict whether a tumor is malignant (M) or benign (B). First, the diagnosis data is changed into numerical values so it can be processed by the machine learning model. The numerical features are then standardized so that they have a similar scale.

After that, feature selection is performed to choose the features that are most useful for prediction. We use SelectKBest to find the best features. The selected features are then used with Logistic Regression to classify the tumors.

The purpose of this process is to reduce unnecessary features while keeping the features that have the most influence on the prediction. The final step is to find the optimal number of features that gives good classification results.

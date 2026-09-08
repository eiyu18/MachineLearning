# JS02: Data Preprocessing Lab Report

## JS02-01: Exploratory Data Analysis (EDA)

Lab 1 focused on Titanic dataset before making any modifications. I used basic profiling functions (shape, info(), isnull().sum(), etc.) to review the structure and identify missing data. For numeric features, I mapped distributions using histograms, checked for Fare outliers using boxplots, and analyzed the Age-Fare relationship using a scatter plot and heatmap. Ultimately, the exploration revealed missing data in the Age, Cabin, and Embarked columns, meaning the dataset must be cleaned before moving on to the next phase.

## JS02-02 Data Preprocessing - Structured Data

Lab 2 focused on executing data imputation strategies to resolve previously identified missing values. Specifically, I replaced missing Age values with the mean, filled the highly incomplete Cabin column with a "DECK" placeholder, and imputed Embarked using the mode. The cleaned dataset was saved as Titanic-Dataset-Fixed.csv. A final verification confirmed zero missing values for Age and Cabin and ensured no data was lost

## JS02-03 (Overview) Feature Selection, Encoding, and Standardization

Lab 3 picked up where Lab 2 left off, using the cleaned dataset. narrowed things down to five columns: Survived, Pclass, Age, Sex, and Cabin. Since Sex and Cabin are categorical (text-based), converted them into numbers using LabelEncoder.

Then standardized Age using StandardScaler, which rescales the values so they're centered around a mean of 0, some values end up negative, some positive, depending on how far they are from the average.

## JS02-04 Data Preprocessing - Unstructured Data

Lab 4 shifted gears to image data using the classic Lenna image. First, I loaded and displayed it in its original form. Then I resized it down to 128×128 pixels.

After resizing, I converted the image to grayscale, stripping out the color information and leaving just brightness levels, a much simpler representation than the original RGB image.

## Assignment Wisconsin Breast Cancer

This assignment covered the essentials of preprocessing, dropping unnecessary columns, encoding the target label, and standardizing the features, leaving the dataset in solid shape for modeling and feature selection down the line.

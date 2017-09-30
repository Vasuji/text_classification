
[//]: # (Image References)

[image1]: ./pic/1.png
[image2]: ./pic/2.png 
[image3]: ./pic/3.png 
[image4]: ./pic/4.png 


# Text Classification

This repository includes text classification works which involves following steps:


## Step I: Getting and Cleaning Data
In this step data has been downloaded and cleaned. A new data frame has been created and saved as new data file. Final data file has 3117 rows. There are 5 different classes in the data file. 

[Python notebook: Getting and Cleaning Data](https://github.com/Vasuji/text_classification/blob/master/1.Getting_and_cleaning.ipynb)


## Step I: Exploratory Data Analysis
In this step some exploratory data analysis has been done. Few examples are
1. Plot of class frequencies
2. Net word frequencies plot
3. Plot of  frequencies of words in each class
4. Plot of Word cloud



| Class frequencies         | Net word freq     | Word freq per class     | Word cloud |
| ------------- |:-------------:|:-------------:| ------|
|![Left][image1] | ![Center][image2] | ![Right][image3]| ![Right][image4]

[Python notebook:Exploratory Data Analysis](https://github.com/Vasuji/text_classification/blob/master/2.Exploratory_data_analysis.ipynb)


## Step I: Model Selection and Tuning
This is them main body of the project it includes three files:

### 1. Model built with Bag of Words. 

[Python notebook: Bag of Words models](https://github.com/Vasuji/text_classification/blob/master/3.models/4.1.BagOfWords.ipynb)

### 2. Model built with TFIDF

[Python notebook: TF-IDF Models](https://github.com/Vasuji/text_classification/blob/master/3.models/4.2.TF-IDF.ipynb)

### 3. Model built with Word to vec

[Python notebook: Word to Vec Models](https://github.com/Vasuji/text_classification/blob/master/3.models/4.3.Word2Vec.ipynb)


## Discussion



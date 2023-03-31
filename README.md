Fake News Detection
This repository contains code for a fake news detection project. The goal of the project is to train machine learning models to classify news articles as either reliable or fake based on their content. The models are trained and evaluated using two different datasets: the Fake News Corpus and the LIAR dataset.


Data:
The two datasets used in this project are the Fake News Corpus and the LIAR dataset. The Fake News Corpus is a collection of news articles labeled as reliable or fake. The LIAR dataset is a collection of statements labeled as true, mostly-true, half-true, barely-true, false, or pants-on-fire. The statements are taken from various news sources and are labeled based on their truthfulness.

Preprocessing:
The first step in the project is to preprocess the text data in the datasets. This includes tokenizing the text, removing stop words and punctuation, and converting the text into numerical vectors that can be used as input to the machine learning models.

In this project, we use the TfidfVectorizer() class from the sklearn library to convert the text data into numerical vectors. We also use the LabelEncoder and to_categorical functions from sklearn to convert the target labels into numerical form.

Models:
In this project, we train and evaluate several machine learning models on the two datasets. The models we use are:

Logistic Regression
Naive Bayes
Support Vector Machine
Random Forest
Neural Network
For each model, we train the model on the training set, evaluate the model on the validation set, and test the model on the test set. We compute the accuracy and F1-score of each model on the test set and also display a confusion matrix for each model.


Conclusion:
Overall, the results show that the models perform well on the Fake News Corpus but struggle to classify statements from the LIAR dataset. This is likely due to the fact that the LIAR dataset contains statements instead of full news articles and the statements are labeled based on their truthfulness rather than their reliability. Nonetheless, the project demonstrates the potential of machine learning models in detecting fake news and provides a starting point for further research in this area.

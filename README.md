# Fake-News-Detection

### Introduction
Fake news detection is a hot topic in the field of natural language processing. The objective of this project is to classify news as fake or real ones. This project deals with data analysis, visualization and classification. 


### Dataset
You can dowload the dataset from [here](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset). This dataset consists of 2 files with fake and real data. The files consist of the following columns.
* Title
* Text
* Subject
* Date

### WORK DONE
The text is tokenized and transformed using count vectorizer and tfidf transformer. The tokenized data is fed as input to the pipeline, and classified.
Three classification models are used in this project.
* MultiNomial Naive Bayes
* Support Vector Machine
* Passive Aggressive Classifier

Performance evaluation metrics like accuracy and confusion matrix are used for evaluating the models.
You can read a detailed writeup of the project [here](https://medium.com/@joyceannie111/fake-news-detection-using-nlp-techniques-c2dc4be05f99).

### Future work
* Deep learning techniques works well with text classification. If you are interested, you can try it.

* BERT, GloVe, ELMo etc which are popularly used in the field of NLP can be used to improve the performance.

* Creating a web app using [Streamlit](https://www.streamlit.io/)

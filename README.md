# An NLP workshop - Categorizing tweets into relevant or non-relevant

adapted from https://github.com/hundredblocks/concrete_NLP_tutorial.git

## Workshop Overview

In this workshop you will combine a few different NLP techniques to classify tweets. You will:
- clean up your input data
- transform your text data into numerical vectors (because machine learning algorithms need numbers as inputs!)
- use those vectors as input to machine learning classifiers

We will present you with the code for three different **word embeddings** (i.e. ways to turn text into vectors of numbers) 
and two different **classification algorithms**. It will be your job to select an embedding and a model, train it with 
the data provided (you might want to perform some additional **cleansing** of the data beforehand) and then test the 
accuracy of your trained model. The team with the most accurate model wins!

## Environment Setup

If you are using Anaconda, you set up a new conda environment as follows:

```
conda env create -f env.yml
```

This creates a new conda environment called **nlpw**. To add this as a kernel to Jupyter, use the following command:
```
python -m ipykernel install --user --name nlpw --display-name "Python (nlpw)"
``` 

## Download pre-trained Word2Vec model

You can download a pre-trained Word2Vec model that was trained on a large corpus of Google News articles here: 
https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing
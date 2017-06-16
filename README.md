# Twitter Sentiment Analysis

This is a project for the Big Data Analysis Course in National Taipei University of Technology (NTUT). The program takes queries from users and spits out the current general sentiment regarding the specific topic in Twitter.

## Demonstration 

### Code Demo

* <a  target="_blank" href="https://michaelandhsm2.github.io/sentiment-analysis/Part 1 - NLP & Bag of Words.html"> Part 1 - NLP & Bag of Words</a>
* <a  target="_blank" href="https://michaelandhsm2.github.io/sentiment-analysis/Part 2 - Distributed Word Vectors.html"> Part 2 - Distributed Word Vectors</a>
* <a  target="_blank" href="https://michaelandhsm2.github.io/sentiment-analysis/Part 3 - Twitter Sentiment Analysis.html"> Part 3 - Twitter Sentiment Analysis</a>
* <a  target="_blank" href="https://michaelandhsm2.github.io/sentiment-analysis/Parallel Processing.html"> Part 4 - Parallel Processing for Large Datasets</a>
* <a  target="_blank" href="https://michaelandhsm2.github.io/sentiment-analysis/Demo - Word Vector & Clustered Words & Twitter Sentiment Analysis.html"> Project Demonstration</a>

### Slide Presentation

<a target="_blank" href="https://docs.google.com/presentation/d/1YWFTt3y2cAdzR0PiFLVFslEXv5H1K5kvNFhZGXo5-zc/pub?start=false&loop=false&delayms=3000">Google Slide Presentation for Term Presentation</a>

## Getting Started

### Prerequisites

You have to have Python 3.X and Jupyter Installed, and as for the modules used in the code, just install the following using a UNIX system.

`$ pip install tweepy re nltk pickle pandas numpy gensim sklearn`

### Installing

1. Due to the size of the dataset and the trained classifiers, you will have to download the following files from <a href="https://drive.google.com/drive/folders/0B2idKBpjHWuXa2o2b1h2aFlkeDQ?usp=sharing" target="_blank">this Google Drive link</a> and place them in its respective folders.

2. Run `$ jupyter notebook` in the folder, and open "Demo" for a demonstration.

3. If you wish to run parallel prosessing, type `$ ipcluster start --n=4 --profile='movie-view'` in your terminal to start the parallel workers.

## Built With

* Python
* Jupyter Notebook
* Ipythonparallel

## Authors

* **Michael Fu** - *System Design and Code Implementation* - [michaelandhsm2](https://github.com/michaelandhsm2)
* **Leon Shang** - *Code Implementation and Testing* - [leon20121005](https://github.com/leon20121005)
* **Sherry Wang** - *Algorithm Research and Implementation Consuling* - [asweetapple](https://github.com/asweetapple)

## Acknowledgments

* Dataset obtained from <a  target="_blank" href="http://help.sentiment140.com/for-students/">Stanford Twitter Sentiment Dataset</a>
* Inspiration - Kaggle's <a  target="_blank" href="https://www.kaggle.com/c/word2vec-nlp-tutorial">Bag of Words Meets Bags of Popcorn Tutorial</a>
* And the course of Big Data Analysis in Spring 2017, taught by <a href="http://www.cc.ntut.edu.tw/~jhwang/">Jenq-Haur Wang</a>.

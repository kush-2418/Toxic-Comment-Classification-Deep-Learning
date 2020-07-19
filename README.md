# Toxic-Comment-Classification-Deep-Learning

1. [ Demo ](#demo)
2. [ Overview ](#overview)
3. [ Dataset ](#data)
3. [ Installation](#install)
4. [ Run ](#run)


<a name="demo"></a>
### Demo
#### Link 

<a name="overview"></a>
### Overview

The Toxic Comment Classification project is sponsored by Google and Jigsaw, with a purpose to improve online conversation. 
The task is to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate. 
The dataset consists of comments from Wikipedia’s talk page edits. The model has been created using hybrid of deep learning architectures BiDirectional LSTM 
and 1 Dimensional Convolutional Neural Network. The words are embedded into vector form using pre-trained Glove word vectors. The model achieves the 
loss 0.227 and Log Loss 0.26. The model has been deployed using Flask framework over the Heroku server.
<a name="data"></a>

### Dataset
Download dataset from kaggle
Link - https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

### Glove Embedding
Download the pre-trained Glove Word Embedding using the given code
```python
!wget http://nlp.stanford.edu/data/glove.6B.zip
!unzip glove.6B.zip
```
<a name="install"></a>
### Installation

The Code is written in Python 3.7. To install the required packages and libraries, run this command in the project directory after cloning the repository:

> pip install -r requirements.txt

<a name="run" > </a>
### Run

Create an environment and clone this repository. To run this project run a command into terminal :

> python app.py


```

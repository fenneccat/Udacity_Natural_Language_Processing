# Udacity_Natural_Language_Processing
Codes learn from Udacity Course (Natural Language Processing)

## Project 1 - POS Tagger
Part of Speech Tagger using Hidden Markov Model.
`pomegranate` is used for build a model.
Simple HMM model with add-one Laplace Smoothing is applied


## Project 1 (Optional) - IBM Bookworm
By using **IBM Watson's Cloud-based NLP services**, build a simple QA model.
QA model with assistant workspace. By sending a query to system, simple matched answer can be returned.

## Project 2 - Machine Translator
Implement various RNN mdoels with `keras` to make machine traslator (Eng->Fr)
* Understand how to construct RNN model using `keras`
* 4 versions are available
	1. simple RNN (GRU) model which uses word number itself as input
	2. RNN model with embedding layer
	3. Bidiretional RNN model
	4. Encoder-Decoder model
	5. (final) Encoder-Decoder model with Embedding layer

## Exercise 1 - LDA topic Modeling
* Understand Latent Dirichlet Allocation
* Build LDA model with BOW and TFIDF
* Topic classification

## Exercise 2 - Sentimental Analysis
* Can draw WordCloud with IMDB image
![](https://github.com/fenneccat/Udacity_Natural_Language_Processing/blob/master/Exercise_Sentimental-Analysis/images/wordcloud.png)
1. classic ML classification models
* Make textdata into vector
* Sentimental analysis with GradientBoostingClassifier, GaussianNB

2. RNN classification model
* use LSTM to build sentimental anaylsis model

3. NN classification model
* Implement NN model from the base
* Parameter adjusting is contained

## Exercise 3 - Keras
* Can build NN models using Keras
	* MLP, RNN (LSTM)

## Exercise 4 - Attension Basics
* Reproduce and visualize a process of how attention is applied on single cell

## Exercise 5 - Deciphering Code with character level RNNs
* using many-to-many GRU cell to build code deciphering model
* Basic generation model to translate code to plain text

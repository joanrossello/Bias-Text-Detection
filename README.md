# Bias-Text-Detection

This project investigates different strategies for detecting bias text in Natural Language Processing. In particular:

* Use data processing to tokenize text datasets, produce Part-Of-Speech tagging and dependency tagging, and prepare the dataloaders for the bias detection models.
* Explore neural network classifiers with GloVe word embeddings, and features relating to syntactic and sematic relationships of the word under analysis and its context.
* Train and test LSTMs BiLSTMS and transformers for text classification.
* Fine-tune pre-trained large language models such as BERT and BLOOM for bias text detection.
* Develop graphical models for text classification. This involves processing the text data to generate the graph network it represents through PMI and TF-IDF scores of corpus documents and unique words, and generate the classification model by training graph convolutional networks, both transductive and inductive.
* Show that pre-trained language models display high performance and generalisation in detecting different types of bias, especially when combined with bias-related word embeddings, and bidirectional LSTMs (mixed endemble architectures).

![](/mixed3.png) 

The figure shows an example of a mixed ensemble model architecture.

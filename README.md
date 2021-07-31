# Article-Classifier

The utilization of machine learning procedures can help to classify articles of different types utilizing only their titles for the purpose of potentially filtering relevant articles from those that are irrelevant to a given purpose.

Using data derived from the BBC, we sought to classify articles into one of five categories:
 - technology
 - entertainment
 - politics
 - business
 - sport

To do so, we utilized various methods in text preprocessing in addition to deep learning procedures in the python programming language with shell code native to UNIX based operating systems. More specifically, we created convolutional neural networks with global max pooling layers with and without the use of premade word-vector embeddings. Using a train-test split, the accuracy of the two models in the classification of article categories was assessed on articles that were not seen during the model training process. The resulting models with and without the premade embedding vectors was  approximately 98.1% and 97.1%, respectively. This project indicates that using relatively concise yet validated deep learning models can be used for practically in a variety of endeavors.

To ensure reproducibility, the jupyter notebook was written in a format that allows users of Linux and Mac operating systems to replicate the models for use with new data. The word embeddings and article text files are not hosted in this repository but are instead retrieved using the wget command native to UNIX systems. The packages used may involve installation using a python package manager such as pip or anaconda, however. The result of the provided code are high-quality models that can aid the automation process of the classification article categories to aid in the identification of articles that are relevant to the end-user.


## References:
[Insight Resources - BBC Datasets](http://mlg.ucd.ie/datasets/bbc.html)

[D. Greene and P. Cunningham. "Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering", Proc. ICML 2006.](http://mlg.ucd.ie/files/publications/greene06icml.pdf)

[Glove Embeddings](https://nlp.stanford.edu/projects/glove/)

# bert-pos-tagging

1- the main goal

we'll be building a machine learning model that produces an output for every element in an input sequence, using PyTorch and TorchText. Specifically, we will be inputting a sequence of text and the model will output a part-of-speech (PoS) tag for each token in the input text. This can also be used for named entity recognition (NER), where the output for each token will be what type of entity the token is.

we'll be using a pretrained Transformer model, specifically the pre-trained BERT model. Our model will be composed of the Transformer and a simple linear layer


2- the dataset

the Universal Dependencies English Web Treebank (UDPOS) dataset we will download the data from torchtext.legacy


3- the model

the pre-trained BERT model ,
The model is relatively simple, with all of the complicated parts contained inside the BERT module which we do not have to worry about. We can think of the BERT as an embedding layer and all we do is add a linear layer on top of these embeddings to predict the tag for each token in the input sequence.


4- the results

we got train and valid accuracy which is 99.52% and 92.03%

and we got test accuracy 90.90%

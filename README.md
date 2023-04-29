# NLP-Sarcasm_Detector

This is a Natural Language Processing project. It uses neural networks to classify headlines in articles as sarcastic (0) or not sarcastic (1).

The input data is derived from an online source it. It consists of samples of headlines in one column and in another column, it indicates whether the specific 
is sarcastic or not. Each word in a text is tokenized using the tensorflor Tokenizer module class. This class allows a string of words to be transformed into a vector
where each word is mapped to a specific integer. Hence, the input data is a vector which is a tokenized form of a string. 

The neural network uses three layers. The first layer is an embedding layer which reduces the dimensional space of the inputs to a lower dimensional space for 
more efficiency. The second layer is a hidden layer with 24 units with 'relu' activation and the output layer has 1 unit with 'sigmoid' activation.

The result is a value that ranges from 0 - 1. If the value is closer to 1 then the input is sarcastic.

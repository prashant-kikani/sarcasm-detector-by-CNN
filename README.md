# sarcasm-detector-by-CNN
It predicts whether a given statement is sarcastic or not. <br/>
It uses neural network made of Convolutional1D layers, maxpooling, dropout and pretained GloVe embeddings in Embedding layer at first.<br/></br>
GloVe word embeddings can be downloaded at https://nlp.stanford.edu/projects/glove/ <br/>
I used this one : http://nlp.stanford.edu/data/glove.6B.zip (6B tokens, 400K vocab, uncased, 50d, 100d, 200d, & 300d vectors, 822 MB download) <br/>
Little data preprocessing is done to make data cleaner.<br/><br/>
## Possible future improvements
Data Preprocessing still can be done to get more accurate results. We can remove statements which are very difficult to predict. by doing that, we are giving a clean, more classified data to our neural network. And results will be better.<br/>
Structure of neural network also can be modified. Adding some more Conv1d layers won't cause any harm !! (But yes, it may become computationally expensive. As it will take longer time for training. And burn more GPU power too !!)

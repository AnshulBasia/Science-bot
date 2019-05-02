So, I am tryig to learn a complex function which would take embeddings of question and all the options and then 
will predict the probability of an answer being correct. 



Problem Solving Approach:

1.Understanding the data and different classes to answer of questions into.
2.Will try to take 75% questions to train and rest 25% to test
3.Output class will be a one hot vector
4.Input will be question and its options,  Will use word2vec or universal sentence encoder to compute embedding of a sentence to feed as an attribute of a question.
5.Starting with a simple 2 layer neural network to see how it performs.
6.Tune the network, used relu, apropiate lr and epochs.
7.Plan to use word2vec and for whole sentence, averaging them out to get one vector for the complete sentence.


Key problems that I tackeled were:

Data was very unorganized and random, understanding it, preprocessing it and organizing it took a bit of effort.
Embeddings played an important role, how to use them to predict the class was something to be thought upon.
Extacted important features from the data and removed the redundant features on my own.

I was planing to use universal sentence encoder but that was too big for me to download at my home, as of now, I just used word2vec embeddings and averaged out the embeddings for a sentence.
Instead of using random small vector, incorporate an unknown vector.
Since emebddings are already normalized, I did not really normalized the training data.

Got traing accuracy to be around 54 % which is on 4610 samples and then, I used 75% samples in total to train the model and got accuracy of 76% and 29% on training and testing respectively.

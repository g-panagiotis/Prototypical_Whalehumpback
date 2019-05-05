# Prototypical_Whalehumpback
Prototypical CNN for Whale humpback identification challenge (kaggle) (https://www.kaggle.com/c/humpback-whale-identification/overview)


Dataset can be found here: https://www.kaggle.com/c/6818/download-all Prototypical neural networks were introduced for few shot learning in 2017 by Jake Snell, Kevin Swersky and Richard S. Zemel in this paper(https://arxiv.org/pdf/1703.05175.pdf). 

This repository consists of 3 python files:
> Prototypical_whale_train.py which trains a Prototypical CNN on the dataset of Whalehumpback Identification challenge. Fold 0 denotes train in the whole dataset while Folds 1-5 train the NN in the respective data of the train dataset used for cross-validation.
> Prototypical_whale_evaluate.py which either evaluates the accuracy of a given fold or produces the predictions for the test dataset.
> Prototypical_utils.py contains the parameters of the NN (layers, loss function, etc.)

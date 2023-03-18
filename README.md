# RNN-LM-Network

This repository contains an implementation of a Recurrent Neural Network Language Model (RNNLM) that can be used for predicting the next word in a sentence based on the previous ones. This implementation uses Pytorch.

The main files in the repository are:

'model.py': contains the implementation of the RNNLM model

'utils.py': contains some utility functions such as get_ptb_dataset() to download the Penn Tree Bank dataset, and ptb_iterator() to generate batches of input and output sequences

'train.py': trains the RNNLM model using the Penn Tree Bank dataset

Prerequisites

Python 3.6 or higher
Pytorch
Numpy

Usage

Clone the repository using git clone https://github.com/your-username/rnnlm.git
Download and preprocess the Penn Tree Bank dataset using python preprocess.py. This will create a data/ directory containing the preprocessed dataset.
Train the model using python train.py.
You can modify the hyperparameters of the model in model.py by changing the values of the Config class attributes.

References

Mikolov, T., Karafiát, M., Burget, L., Černocký, J., & Khudanpur, S. (2010). Recurrent neural network based language model. In Eleventh annual conference of the international speech communication association.
Zaremba, W., Sutskever, I., & Vinyals, O. (2014). Recurrent neural network regularization. arXiv preprint arXiv:1409.2329.

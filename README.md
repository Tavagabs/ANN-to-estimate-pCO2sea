# ANN-to-estimate-pCO2sea

## Artificial Neural Network to estimate pCO2sea ##
## Produced by Carvalho, G. T. and Mejia, C., in 2024 ##

### This repository contains the python script for producing marine pCO2 estimates using 
the Artificial Neural Network method and analyzing its output (Artificial Neural Network to estimate pCO2sea).

The python script has two very important platforms for the Artificial Neural Network: TensorFlow and Keras.

TensorFlow is an open source platform, developed by Google, for research in machine learning and networks
deep neural networks. 
Keras is a high-level tool for neural networks that reduces the time required for the user to produce the model.

O scrip should be used in the following order.

1) Importing libraries

Example
import numpy as np

2) Import database and organize data

Example
trajet_file = 'Import database.csv'

3) Normalize the variables
   
4) Import TensorFlow and Keras

Example
import tensorflow as tf

5) List the normalized variables that make up the input and output of the neural network

Example
vars_for_model_input = [sss_norm_varlabel,sst_norm_varlabel,pco2at_norm_varlabel]
vars_for_model_output = [pco2_norm_varlabel]

6) From there the network can be traced


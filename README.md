# CSGO_analysis
## Description
This repository contains an analysis of GSGO tournaments data using SVM and NN. Two predictions are performed on the test data using two classifiers.  NN is configured to have 3 hidden layers with 2000 neurons each and ReLU activation. This is a rough implementation of classifiers without data augmentation. As one data augmentation technique, the order of the teams can be replaced, for example, from "team1 vs team2" to "team2 vs team1", and inverting "who_win" target value. This way the data can be increase twice for better generalization. 

## Installation
In order to rerun the program, it is necessary to install all relevent requirements listed in "requirements.txt" file using "pip install -r requirements.txt" command. 

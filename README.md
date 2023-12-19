# Machine learning repository
This repository contains the essential scripts, used for the entire design process in the project. Contains scripts from data generation, preprocessing, training of various neural networks and final testing of the designed model.

## CST interface
Contains the code for interfacing CST, automating the data generation process

## Data parser multi file
Contains data parser code, reading exported CST files and combining them into a single data python dictionary.

## Forward_model_new
Code for training the forward neural network model, contains normalization of the data as well as training and testing of the model. Saves the model as a .keras file.

## Reverse_model_notebook
Code for training the inverse model 1. Contains normalization, training, testing and saving of the model.

## Optimization_NN
Contains code for interpolating data set and visualizing samples of the synthesized data set.

## Parse_BW_FC
Contains code for extracting bandwidth and center frequency of s11 curves.

## Inverse_model_2
Contains code for training the inverse model 2.

## User interface
Contains a simple terminal user interface, loads inverse model 2 and predicts using the user input.
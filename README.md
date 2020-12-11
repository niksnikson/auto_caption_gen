Authors: Rachael Grudt and Nikson Panigrahi

Image caption generation is a machine translation problem. This report aims to solve that problem using
LSTM Neural networks and evaluate it using techniques BLEU and METEOR on the FLICKR30K dataset.

There are 4 separate ipynb files included here that produce the results discussed in our report on the CS 6120 Project. 

Part1_LoadData_RunCNN -  loads the dataset directly from Kaggle and extracts feature vectors from the Flickr30k dataset

Part2_TrainingRNNModel -  cleans the caption data, separates the data into training, validation and test sets, and runs the full models on the training dataset. 

Part3_ValidationModel - evaluates the models created in Part 2 on the validation dataset using BLEU and METEOR metrics

Part4_TestModel - evaluates the highest performing model from Part 3 on the test dataset

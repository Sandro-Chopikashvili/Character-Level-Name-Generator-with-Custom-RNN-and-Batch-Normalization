# Character-Level Name Generator

**Author:** Sandro Chopikashvili – Data Scientist / ML Engineer  

## Project Overview
This project implements a character-level Recurrent Neural Network (RNN) from scratch in PyTorch to generate names. It uses two hidden layers, embeddings, batch normalization, and manual backpropagation.

The network learns sequential patterns in names and predicts the next character given a sequence of previous characters.

## Features
- Data preprocessing: encoding names into integers, padding sequences.
- RNN with two hidden layers and custom `tanh` activation.
- Batch normalization applied to hidden layers.
- Forward and backward passes implemented manually.
- Softmax cross-entropy loss for training.
- Training loop with adaptive learning rate.
- Testing loop for evaluating loss and accuracy.

## File Structure
- `names.xlsx` – Dataset of names.
- `main.py` – Python script implementing the RNN, training, and testing.
- `README.md` – Project description.

## Project Steps
1. Importing libraries (torch, pandas, numpy).  
2. Loading and cleaning dataset.  
3. Encoding characters and creating sequences.  
4. Splitting dataset into training and test sets.  
5. Initializing RNN parameters, embeddings, and batch normalization parameters.  
6. Defining activation (`tanh`), loss (`softmax_cross_entropy`), batch normalization, forward, and backward functions.  
7. Training loop: mini-batch gradient descent with adaptive learning rate.

## Note
This project is for learning purposes only and is not intended for use with actual training data or as a production-ready model.

## Author
**Sandro Chopikashvili**  
Data Scientist / ML Engineer

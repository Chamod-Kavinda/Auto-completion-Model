# Auto-Completion Word Prediction using RNN
![Auto-complete](https://github.com/user-attachments/assets/ae99023c-d280-4263-acdf-cf10588bdcfe)

This project aims to build a Recurrent Neural Network (RNN) model to predict autocompletion suggestions for half-typed words. The model is trained using a wordlist of 10,000 common English words, and it provides possible completions for starting letters input by the user. This functionality is commonly seen in text input systems like email clients, text messaging apps, and search engines.

## Project Overview
The goal of this project is to train an RNN model that can autocomplete words given an incomplete string of 3-4 characters. For example, typing "univ" might suggest completions such as "university", "universal", etc.

## Features
Predicts word completions based on the first 3-4 letters.
Trained using a dataset containing 10,000 common English words.
Provides multiple completion suggestions for each input.
## How It Works
Input: A string of 3-4 starting letters, e.g., "univ".
Model: The RNN processes the input string and predicts possible word completions based on the trained model.
Output: The model returns a list of suggested completions such as "university", "universal", etc.

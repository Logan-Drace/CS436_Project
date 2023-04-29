# CS436_Project

This Repo is for CS 436 project. It fine-tunes the Reddit TL;DR dataset on BART for summarization.

# How It Works
1. Download Reddit TL;DR dataset
2. Clean that data set using the functions in the notebook to get ready fro training
3. Tune Hyper-Parameters
4. Run Model with the DatasetDict -> 'dd' 

# Modules Needed
Pandas, Numpy, transformers, pytorch, datasets, evaluate, nltk, and rouge_score

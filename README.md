# Questions Similarity using Siamese Neural Network

# Problem
The problem is the identification of similar questions on Quora.  
With millions of questions posted, it can be challenging for the user to find similar questions that have already been answered or addressed.

# Solution
To solve this problem, I employed natural language processing to clean and preprocess the data, and a Siamese Neural Network with LSTM layers and Manhattan distance metric to measure the similarity between pairs of questions.

# Implementation
1. Data import and Exploratory data analysis
2. Splitting the data,cleaning & preprocessing (Tokenize sentences, Remove capital letters, Remove stopwords, Remove non-alphanumeric characters, Lemmatize the tokens)
3. Vectorizing the Train and Test Sets using Word2Vec.
4. Train the Siamese Neural Network model & Test.
5. Visualization of the preformance.


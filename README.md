# Historical Word Embeddings:Harry Potter Movies Dataset
## Introduction
This project is focused on analyzing the movies' scripts data of parts 1,2 & 3 of the Harry Potter movies using word embedding modelling techniques. The goal is to learn the meaning of words in a high-dimensional space and analyze relationships between them for comparisons between different characters. The project includes preprocessing of the text data, training of word embeddings, and analysis of similarity matrixes, and relationship.

## Data
The data used for this project is the 3 CSV files of Harry Potter movies, which are provided in the github repository. The files are parsed to extract the text, and then processed to remove stop words, punctuation marks, and special characters. The final preprocessed text was used for data manipulation and feeding the word2vec models to compare the words embeddings between different movies characters.

## Requirements
The following libraries need to be installed for the successful execution of the code:

1. Pandas
2. Numpy
3. Matplotlib
4. Scikit-learn
5. TensorFlow

Analysis of Word Similarity and Relationship
The trained embeddings were analyzed using various techniques. The word similarity was calculated using the cosine similarity between the vectors. The relationship between words was analyzed using the nearest neighbors and clustering techniques. The results were visualized using plots and heatmaps.

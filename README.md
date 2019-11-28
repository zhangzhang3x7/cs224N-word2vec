# cs224N-word2vec

cs224N Assignment 2: Implementation of word2vec algorithem


Before you begin, first run the following commands within the assignment directory in order
to create the appropriate conda virtual environment.

conda env create -f env.yml
conda activate a2

We are going to use the Stanford Sentiment Treebank (SST) dataset to train word
vectors, and later apply them to a simple sentiment analysis task. You will need to fetch the datasets
firrst. To do this,

sh get_datasets.sh

Then, just 

python run.py

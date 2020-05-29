# Comparison on Machine Learning Models and BERT on SQuAD
This repository consists of our implementation of different machine learning models on SQuAD dataset along with a state-of-the-art model BERT. A pre-print is written in detail about the comparative analysis on SQuAD.<br>

Link to pre-print: https://arxiv.org/pdf/2005.11313.pdf

For running the final (ML_final.ipynb):
1. Run the first cell for importing all the libraries.
2. Run the cells after the "start here" section to avoid doing preprocessing again.(It takes 3-4 hours for preprocessing as the embedding files are quite large in size).
3. (Optional) To run sentiment analysis code: Get the vader lexicon with a different way rather than nltk.download(vader_lexicon) command. Try wget if possible.

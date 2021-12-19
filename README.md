# txtsim

**txtsim** is a Python script for discovering similar or related text files through measures of document similarity. Under the hood, it uses [scikit-learn](https://github.com/scikit-learn/scikit-learn) for text feature extraction, and [nltk](https://github.com/nltk/nltk) for text pre-processing. More specifically, the program recursively scans a given directory for text files, clean their content (by stripping the front matter if it's an `org` or `md` document) and some undesired characters, tokenize them, replace each token with its respective linguistic stem, generate a TF-IDF sparse matrix, and calculate the cosine similarity between these documents.

This is a work in progress. A minimum usable product (MUP) will be ready in a few months.

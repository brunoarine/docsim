# txtsim

**txtsim** is a Python script for discovering related text files through measures of document similarity. Under the hood, it uses [scikit-learn](https://github.com/scikit-learn/scikit-learn) for text feature extraction, and [nltk](https://github.com/nltk/nltk) for text preprocessing. More specifically, the program recursively scans a given directory for text files, strip undesired characters, tokenize the texts, replace each token with its respective linguistic stem, generate a TF-IDF sparse matrix, and calculate the cosine similarity between these documents.

This is a work in progress. A minimum usable product (MUP) will be ready in a few months.

## Features backlog

- [ ] Org-mode support
- [ ] Markdown support
- [ ] Ignore front matter
- [ ] Ignore link
- [ ] Recursive directory scan
- [ ] Display clusters of similar documents

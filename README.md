# Smart Scientific Content Auto-completion System

This repo represents an autocomplete system for scientific articles. We have approximately 1064 articles in this repo, and we aimed to train the LSTM model over these articles after preprocessing and then test the results.
This project is solely for educational purposes; however, you are welcome to contribute and fix any issues that may arise; please submit a pull request with the new changes and tag me!
Topic Modeling: use Topic Modeling with Word2Vec to extract k topics from a given corpus is represented in the ***project-First-Phase***. The model's output will allow you to describe the various k topics based on their top representative keywords and the distribution of topics per document.

The ***Proejct.ipynb*** which Use a word level with character-level LSTM to build a model that suggests completion to already typed
text, and make comparsion amonges the two approches.

The following files represent our ecperiments stages:

1- Project-CharBased-example-first-article-only: this fike was tested over one article since the omputation is high and take too long, within a need for a GPU, so we have tested our code over one artcile, this file for the secind phase of the projrect with connected the lda with lstm.

2- Project-CharBased&LDA-last-Edit-13-5-2021: the last edit we have did for our experiment.

3- Project-CharBased&LDA-SecondPhase-originalexperiment : this is the orignal file for our second phase which consist the word level, and the charchter level for auto complete system.

4- Project-First-Phase 

You can download the dataset [here](https://drive.google.com/file/d/1HrbRAWal2dcc819V9XgCVnPCZzQ7P7oN/view?fbclid=IwAR06OXYZ1Dti3cL4_YSDOSOkBFUI9hK6PEQ73Td7xwpLT4Jx_HeU2yHE-H8)
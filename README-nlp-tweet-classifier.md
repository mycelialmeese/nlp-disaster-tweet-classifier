# NLP Disaster Tweet Classifier

Binary text classification to determine whether a tweet describes a real disaster or not — based on the [Kaggle NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started) competition.

## Overview

This project applies natural language processing techniques to classify short-form social media text. The task is a classic NLP binary classification problem: given a tweet, predict whether it refers to an actual disaster event (1) or not (0).

## Approach

- Text preprocessing: tokenization, stopword removal, cleaning noisy tweet data
- Explored embedding strategies for representing tweet text numerically
- Trained and evaluated classification models, iterating on architecture and preprocessing
- Submitted predictions to Kaggle for external benchmark scoring

## Tech Stack

- **Framework:** PyTorch
- **Environment:** Jupyter Notebook (Kaggle)
- **Key concepts:** NLP preprocessing, tokenization, text embeddings, binary classification

## Context

Completed as part of an M.S. in Data Science deep learning module. The Kaggle format provided a real benchmark and held-out test set, which adds external validity beyond a standard homework assignment.

## Results

Achieved scored predictions on the Kaggle leaderboard. The project demonstrated practical NLP pipeline construction from raw messy text through to a deployed classifier.

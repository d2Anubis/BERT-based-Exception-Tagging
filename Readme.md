# [EY GDS Hackpions 2.0](https://www.hackerearth.com/challenges/hackathon/hackpions-2-ey-gds-hackathon/)

This repository contains the solution to the theme : NLP-based tagging solution

We have tried to build an AI operations model which will autolabel the exceptions and provide the solution without any user intervention. The solution can be divided into two parts:

► Categorizing exceptions by retrieving important keywords : by BM25 algorithm and Word2Vec implementation.

► Finding similar occurring exceptions and their solution scripts : this has been done using the BERT model.

We can create a self-learning model to recognize patterns, determine correlation with other input data set features, learn from data, and tag exceptions as they come. The algorithm should also be capable of classifying exceptions from categories never seen before. All the above tasks will be completed using BERT and Word2Vec models for high accuracy.

The search engine module will retrieve the resolution details and scripts for similar exceptions from the past. The solution will have a feedback network that will append the current solution for the exception into the database where it can act as a feedback for new exceptions.

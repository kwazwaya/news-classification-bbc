# BBC News Document Classification Using BERT

## Overview

This project performs multi-class document classification on BBC news articles using a pre-trained BERT (Bidirectional Encoder Representations from Transformers) model.

The objective is to automatically classify a news article into one of five topic categories:

- Business
- Entertainment
- Politics
- Sport
- Tech

The project uses a pre-trained BERT model from Google and fine-tunes it for the BBC news classification task.

## Problem Statement

With the large volume of digital news published every day, automatically organizing articles by topic can help improve document management and information retrieval.

This project treats news classification as a **multi-class text classification problem**, where the model predicts the topic of an article based on its text.

Given a BBC news article, the model predicts one of five categories:

```text
Business
Entertainment
Politics
Sport
Tech

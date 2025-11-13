# Changing Narratives of Self-Improvement: Topic Modeling Self-Help Literature

This project examines how self-help language changed from the 1970s to the 2010s. Using Python-based NLP and LDA topic modeling, it compares bestselling personal-growth books across the two decades to identify which themes persisted and which ones shifted. The work was published in the Kenyon Digital Archive.

## Overview

Two corpora were created: five bestselling self-help books from the 1970s and five from the 2010s. After converting each text to plain text, the data was cleaned, tokenized, and lemmatized. Latent Dirichlet Allocation was then used to surface the most salient terms and themes for each decade.

The results point to a clear thematic shift. The 1970s literature leans toward discipline, moral authority, spirituality, and traditional family roles. The 2010s literature focuses more on emotional resilience, habit-building, individualized routines, and authenticity. Both decades maintain an interest in growth and practical self-improvement.

## Files in This Repository

- **Changing Narratives of Self-Improvement (PDF)**  
  Summary of the project, including visualizations and thematic analysis.

- **1970s_lda_topic_modeling.ipynb**  
  Notebook used to process and model the 1970s corpus.

- **2010s_topic_modeling_.ipynb**  
  Notebook used to process and model the 2010s corpus.

## Methods

- Text preprocessing: tokenization, stopword removal, lemmatization, phrase detection  
- Dictionary and corpus creation with Gensim  
- LDA topic modeling with multiple topic-number trials  
- Extraction and interpretation of top-30 salient terms  
- Comparison of thematic patterns across eras

## Key Findings

- **1970s:** Emphasis on discipline, restraint, spirituality, and traditional family structures  
- **2010s:** Emphasis on emotional well-being, vulnerability, habit-building, and authenticity  
- **Shared focus:** Growth, motivation, and practical change

## Citation

If you reference this work, please credit the project as published in the Kenyon Digital Archive.

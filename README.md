Changing Narratives of Self-Improvement: Topic Modeling Self-Help Literature

This project looks at how the language of self-help shifted between the 1970s and the 2010s. Using Python-based NLP and LDA topic modeling, it compares bestselling personal-growth books from each decade to see which themes stayed the same and which ones changed. The work was published in the Kenyon Digital Archive.

Overview

The analysis focuses on two corpora: five bestselling self-help titles from the 1970s and five from the 2010s. After converting each book to plain text, the data was cleaned, tokenized, and lemmatized. Latent Dirichlet Allocation was then used to surface the most salient terms and themes within each decade.

The results point to a clear shift in tone and priorities. The 1970s texts lean toward discipline, moral authority, and traditional roles, often framed through spirituality and family. The 2010s texts highlight emotional resilience, habit-building, individual agency, and authenticity. Both decades share an interest in growth and practical change.

Files in This Repository

Changing Narratives of Self-Improvement (PDF)
Poster-style summary of the project, including methods, themes, and visualizations.

1970s_lda_topic_modeling.ipynb
Colab notebook used to process and model the 1970s corpus.

2010s_topic_modeling_.ipynb
Colab notebook used to process and model the 2010s corpus.

Methods

Text preprocessing (tokenization, stopword removal, lemmatization, phrase detection)

Dictionary and corpus creation with Gensim

LDA topic modeling with multiple topic-number trials

Interpretation of top-30 salient terms for each decade

Comparison of thematic patterns across eras

Key Findings

1970s: Themes tied to discipline, restraint, spirituality, and traditional family structures.

2010s: Themes centered on emotional health, vulnerability, personalized habits, and authenticity.

Shared thread: A consistent focus on growth, motivation, and personal change.

Citation

If you reference this work, please credit the project as published in the Kenyon Digital Archive.

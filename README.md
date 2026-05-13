# POS Patterns Across Genres: News vs Tweets

This project compares part-of-speech (POS) patterns across two text genres using spaCy: news-style text and tweet-style text.

The goal is to explore how grammatical patterns vary across genres and how POS-based features can support linguistic analysis in NLP.

---

## Goals

- Run POS tagging with spaCy
- Compare grammatical patterns across text genres
- Examine POS distributions such as nouns, verbs, adjectives, pronouns, and adverbs
- Identify frequent POS bigrams, such as `ADJ + NOUN` or `PRON + VERB`
- Interpret the results from a linguistic perspective

---

## Research Motivation

Different text genres often show different grammatical tendencies.

News-style texts may contain more nouns, nominal modification, and information-dense structures, while tweets may contain more pronouns, verbs, discourse markers, abbreviations, and informal constructions.

This project uses simple NLP methods to examine these differences and connect computational analysis with linguistic interpretation.

---

## Methods

For each genre, the project computes:

- POS distribution
- noun-to-verb ratio
- frequent POS bigrams
- qualitative observations about genre-specific patterns

---

## Project Structure

```text
data/        - sample news and tweet-style texts
notebooks/   - POS analysis notebook
README.md    - project description
```

---

## Tools

- Python
- spaCy
- pandas
- Jupyter Notebook

---

## Status

Work in progress. This project is being developed step by step as part of my NLP learning and research portfolio.

---

## Author

Priscilla Lola Adenuga  
Linguistics × NLP | Low-Resource Languages | Structure-Aware AI Evaluation

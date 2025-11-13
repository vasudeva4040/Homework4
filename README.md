Machine Learning - 
N.Vasudeva Reddy
700782257





NLP Coding Tasks – Token Processing & NER with Ambiguity Detection

This repository contains Python implementations for two NLP tasks:

Q1 — Token Processing Pipeline

The script performs the following steps:

Tokenization

Stopword removal

Lemmatization

Keeping only verbs and nouns (using POS tags)

Input example:
"John enjoys playing football while Mary loves reading books in the library."

Q2 — Named Entity Recognition + Pronoun Ambiguity Detection

This script:

Extracts named entities using spaCy

Checks for pronouns (“he”, “she”, “they”) and prints a warning if ambiguity exists

Input example:
"Chris met Alex at Apple headquarters in California. He told him about the new iPhone launch."

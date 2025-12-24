# Assignment 3 — Recurrent Neural Networks & Language Modeling

**Course:** COMP541 — Deep Learning  
**Topics:** RNNs, LSTM, GRU, Language Modeling, Sequence Classification  
**Submission format:** Jupyter Notebook + PDF report + output files

---

## Overview

This assignment focuses on **sequence modeling with Recurrent Neural Networks (RNNs)**.
The goal is to understand how different recurrent architectures capture temporal dependencies in text.

Two tasks are explored:

1. **Language Modeling** — predicting the next token in a sequence  
2. **Text Classification** — classifying sequences using recurrent models

Experiments compare **LSTM** and **GRU** architectures in terms of performance and behavior.

---

## Tasks

### 1. Language Modeling
- Implement character-level or word-level language models
- Train LSTM and GRU models
- Analyze loss curves and generated text

### 2. Sequence Classification
- Train RNN-based classifiers
- Compare LSTM and GRU performance
- Evaluate prediction outputs and accuracy

---

## Repository Contents

- **notebooks/**
  - `assignment3.ipynb` — Full implementation, training, and evaluation
- **report/**
  - `oozak23_assignment3.pdf` — Final written report
- **outputs/**
  - `lstm_lm_output.json`
  - `gru_lm_output.json`
  - `lstm_classifier_output.json`
  - `gru_classifier_output.json`
  - `classifier-output.json`
  - `output.json`
- **README.md**
  - Assignment overview and repository structure

---

## Notes

- JSON files store model outputs and evaluation results.
- All experiments are reproducible using the provided notebook.
- This work is intended for educational use as part of COMP541.

---

## Acknowledgements

This assignment is part of **COMP541: Deep Learning** and is used strictly for educational purposes.

# COMP541 — Deep Learning Assignments & Project

This repository contains my coursework for **COMP541: Deep Learning**, including all programming assignments and the course project.

Each assignment is organized in a separate folder and includes the corresponding Jupyter notebooks, reports, and supporting files.

---

## Repository Structure

- **assignments/**
  - **A1/** Word Embeddings & Deep Averaging Networks
  - **A2/** Neural Networks & Backpropagation
  - **A3/** Recurrent Neural Networks & Language Modeling
  - **A4/** Graph Neural Networks & Transformers

- **project/**
  - Research proposal
  - Progress report
  - Implementation notebooks and experiments

---

## Assignments

### Assignment 1 — Word Embeddings & Deep Averaging Networks
**Topics: Distributional Semantics & Representation Learning**

Main components:
- Constructed **count-based word embeddings** using co-occurrence matrices
- Applied **Truncated SVD** for dimensionality reduction
- Implemented and analyzed **GloVe-style prediction-based embeddings**
- Performed **semantic similarity analysis** in embedding space
- Built a **Deep Averaging Network (DAN)** for sentiment classification
- Compared count-based vs prediction-based embeddings empirically

Key skills:
- SVD / PCA intuition  
- Word similarity and embedding geometry  
- Neural text classification with averaged embeddings  

---

### Assignment 2 — Neural Networks & Convolutional Neural Networks
**Topics: Backpropagation, CNNs, Optimization**

Main components:
- Implemented **Multi-Layer Perceptrons (MLPs)** from scratch
- Analyzed **backpropagation**, loss surfaces, and convergence
- Built **Convolutional Neural Networks (CNNs)** in PyTorch
- Studied **receptive fields** and architectural depth
- Trained CNNs for **artist classification** on image data
- Investigated **overfitting vs generalization** using train/validation accuracy

Key skills:
- PyTorch training pipelines  
- CNN architecture design  
- Optimization with Adam  
- Performance diagnosis (bias–variance)  

---

### Assignment 3 — Recurrent Neural Networks & Language Modeling
**Topics: Sequence Modeling, RNNs, LSTMs**

Main components:
- Implemented a **frequency-based baseline classifier**
- Built **RNN-based sequence classifiers** from scratch
- Trained models to predict **vowel vs consonant continuation**
- Implemented **character-level language models**
- Compared **RNN vs LSTM architectures**
- Evaluated models using accuracy and sequence likelihood

Key skills:
- Recurrent architectures  
- Character-level modeling  
- Sequence classification and generation  
- Model comparison and analysis  

---

### Assignment 4 — Graph Neural Networks & Transformers
**Topics: GCNs, GATs, Self-Attention**

Main components:
- Implemented **Graph Convolutional Networks (GCN)** from scratch  
  (Kipf & Welling, 2016)
- Implemented **Graph Attention Networks (GAT)** with multi-head attention  
  (Veličković et al., 2018)
- Performed **node classification on the Cora citation dataset**
- Experimented with architectural depth, dropout, and hyperparameters
- Implemented a **Transformer-based sequence-to-sequence model** for translation
- Compared **GCN vs GAT performance** and analyzed attention behavior

Key skills:
- Graph-based learning  
- Attention mechanisms  
- Sparse adjacency handling  
- End-to-end deep learning experiments  

---

## Course Project

### Learned Dynamic Graph Construction for Multi-Sensor Fusion in Autonomous Driving

This project explores **learning adaptive graph structures** for **multi-sensor (LiDAR–camera) fusion** in autonomous driving perception systems.

Core ideas:
- Replace fixed graph topologies (e.g., k-NN, radius graphs) with **learned connectivity**
- Learn **sparse, dynamic graphs** end-to-end
- Improve **efficiency, flexibility, and scalability** of graph-based perception models

Project materials:
- **Project Proposal:** `COMP441_Proposal.pdf`
- **Progress Report:** `comp441_progress_report_merdem22_ozak23-4.pdf`
- Ongoing implementation and experiments

---

## Notes

- Large datasets and pretrained models are **not included**.
- All work is completed for **educational purposes** as part of COMP541.
- The repository is structured to emphasize **clarity, reproducibility, and research-level understanding**.

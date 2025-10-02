# Assignment 1 - N-Gram Language Models  

## Group Info
- **Group Name**: Group 11  
- **Members**:  
  - Abhirup Mukherjee (AXM240026)  
  - Adem Odza (AXO180008)
  - Buvana Seshathri (BXS240020)
  - Samiha Kuncham (SXK240025)
---

## Project Overview
This project implements **n-gram based language models** using Python.  
The main goals are:
1. Train **unsmoothed unigram and bigram models** on the provided corpus.  
2. Implement **smoothing techniques** (e.g., Laplace, Add-k).  
3. Handle **unknown words** in the validation set.  
4. Compute **perplexity** on validation data and analyze results.  

---

## Features
- Tokenization and preprocessing of input corpus.  
- Unigram and bigram probability computation.  
- Unknown word replacement with `<unk>` token.  
- Smoothing methods:
  - Laplace (add-1) smoothing  
  - Add-k smoothing (configurable `k`)  
- Perplexity computation for evaluation.  

---


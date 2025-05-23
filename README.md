# Fake Speech Detection Using AI

## Overview

This repository contains a comprehensive project for detecting fake or synthesized speech using artificial intelligence. It includes all necessary code, scripts, and resources to preprocess audio, extract features, train and evaluate machine learning models, and assess detection performance. Additionally, the repository features a detailed report documenting the methodology, experiments, and results.

## Contents

- **/data/**: Sample audio datasets (or scripts to download/prepare them)
- **/models/**: Model architectures, training checkpoints, and weights
- **/scripts/**: Utility scripts for preprocessing, training, evaluation, and inference
- **/notebooks/**: Jupyter notebooks for experiments, visualization, and analysis
- **/report/**: Project report (PDF, Markdown, or LaTeX) detailing:
  - Problem statement and motivation
  - Literature review and related work
  - Dataset details
  - Feature extraction and modeling
  - Experimental results and analysis
  - Conclusions and future work
- **requirements.txt**: List of Python dependencies
- **README.md**: Project overview and instructions

## Key Features

- End-to-end pipeline for fake speech detection
- Support for popular audio feature extraction (MFCCs, spectrograms, etc.)
- Multiple model architectures (traditional ML and deep learning)
- Reproducible experiments and results
- Well-documented code and a detailed final report

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/paesas-upc/Fake-Speech-Detection-Using-AI.git
   cd Fake-Speech-Detection-Using-AI
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the dataset**
   - Place your audio files in the `data/` directory or use provided scripts to download/preprocess datasets.

4. **Run preprocessing and feature extraction**
   ```bash
   python scripts/preprocess.py
   ```

5. **Train the model**
   ```bash
   python scripts/train.py
   ```

6. **Evaluate or test the model**
   ```bash
   python scripts/evaluate.py
   ```

7. **Read the report**
   - See the `/report/` directory for the full project report, including methodology and findings.

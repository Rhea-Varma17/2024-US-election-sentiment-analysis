
# 2024 U.S. Election Twitter Analysis

This repository analyzes political discourse surrounding the **2024 U.S. Presidential Election** using Twitter data.

The project applies:
- **VADER sentiment analysis**
- **LDA topic modeling**

to study polarization, candidate-centric discourse, and sentiment dynamics.

---

## Repository Structure
`
.
├── 01_preprocessing.ipynb
├── 02_sentiment_and_topic_analysis.ipynb
└── README.md`


---

## Notebook Overview

### Data Preprocessing
**`01_preprocessing.ipynb`**
- Cleans raw Twitter text
- Creates task-specific text fields:
  - `text_vader`
  - `text_lda`
- Prepares data for downstream NLP tasks

### Sentiment & Topic Analysis
**`02_sentiment_and_topic_analysis.ipynb`**
- Performs VADER sentiment analysis
- Fits LDA topic models
- Analyzes:
  - Sentiment asymmetry
  - Volume vs sentiment tradeoffs
  - Topic-specific sentiment patterns

---

## Dataset Source

This project uses the **X (Twitter) 2024 U.S. Election Dataset**, originally compiled by:

> **S. Sinking**,  
> *X 2024 US Election Dataset*, GitHub repository, 2024.  
> Available online: https://github.com/sinking8/x-24-us-election

Due to platform data-sharing policies, the dataset itself is **not redistributed** in this repository.

---

## Reproducibility Instructions

To reproduce the analysis:

1. Download the dataset from the original repository linked above
2. Extract the relevant CSV file
3. Place it in the root directory as:

---

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- vaderSentiment
- matplotlib
- seaborn

---

## Disclaimer

This project **does not predict election outcomes**.  
It analyzes **online discourse**, which may not reflect real-world voting behavior.

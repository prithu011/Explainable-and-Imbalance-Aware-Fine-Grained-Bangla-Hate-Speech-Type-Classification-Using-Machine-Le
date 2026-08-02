# Explainable and Imbalance-Aware Fine-Grained Bangla Hate Speech Type Classification Using Machine Learning

## Overview

This project investigates **fine-grained Bangla hate speech
classification** using the **BanglaMultiHate** dataset. Instead of
binary hate/non-hate detection, it classifies comments into specific
hate categories while emphasizing reproducible preprocessing, feature
engineering, class imbalance analysis, and explainable AI.

## Project Title

**Explainable and Imbalance-Aware Fine-Grained Bangla Hate Speech Type
Classification Using Machine Learning**

## Problem Statement

Existing Bangla hate speech systems often classify comments only as
*hate* or *non-hate*. This project performs fine-grained classification
into six categories:

-   Abusive
-   Political Hate
-   Religious Hate
-   Sexism
-   Profane
-   None

The project also investigates class imbalance and interpretable machine
learning techniques to support transparent moderation.

## Dataset

**Dataset:** BanglaMultiHate

Dataset URL:

https://huggingface.co/datasets/aridhasan/BanglaMultiHate

## Repository Structure

``` text
├── Phase3_Data_Transformation_Feature_Engineering.ipynb
├── data/
├── processed/
├── artifacts/
├── figures/
├── reports/
└── README.md
```

## Current Phase

This repository currently contains **Phase 3: Data Transformation &
Feature Engineering**.

Implemented:

-   Dataset loading and validation
-   Missing value handling
-   Duplicate detection
-   Data quality assessment
-   Exploratory Data Analysis (EDA)
-   Bangla text preprocessing
-   Unicode normalization
-   Text cleaning
-   Feature derivation
-   Feature scaling
-   Label encoding
-   Metadata encoding
-   TF-IDF feature extraction
-   Character n-gram TF-IDF
-   Optional dimensionality reduction
-   Export of processed datasets
-   Reproducibility checks

No predictive model is trained in this phase.

## Exploratory Data Analysis

The notebook includes:

-   Dataset overview
-   Missing value analysis
-   Duplicate analysis
-   Class distribution
-   Label imbalance
-   Split comparison
-   Comment length analysis
-   Word and bigram frequency
-   Emoji, URL, hashtag and mention analysis
-   Lexical diversity
-   Optional word clouds
-   Distribution visualizations

## Feature Engineering

Implemented features include:

-   Character count
-   Word count
-   Average word length
-   Digit ratio
-   Punctuation ratio
-   Emoji count
-   URL count
-   Mention count
-   Hashtag count
-   Bangla character ratio
-   English character ratio
-   Lexical diversity
-   TF-IDF
-   Character TF-IDF
-   Optional Truncated SVD features

## Technologies

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   SciPy
-   Hugging Face Datasets

## Reproducibility

The notebook is designed to execute sequentially from top to bottom.

Practices followed:

-   Fixed random seed
-   Deterministic preprocessing
-   Train-only fitting
-   Saved preprocessing artifacts
-   Exported processed datasets

## Future Work

Future phases may include:

-   Classical machine learning
-   Transformer models
-   Hyperparameter tuning
-   Model comparison
-   SHAP
-   LIME
-   Error analysis
-   Final evaluation

## Authors

**Group 14**

Course: **CSE437 -- Data Science Project**

## License

Academic use only. Please follow the original BanglaMultiHate dataset
license and cite the dataset authors.

## Acknowledgements

-   BanglaMultiHate authors
-   Hugging Face
-   Open-source Python community

# Supply-Chain-Late-Delivery-Risk-Prediction
DSC624 NLP and LLM assignment – Supply Chain Late Delivery Risk Prediction
# Supply Chain Late Delivery Risk Prediction

## Project Overview
This project predicts late-delivery risk using the DataCo SMART Supply Chain Dataset.

## Objective
To compare traditional machine-learning models with a hybrid model using pretrained text embeddings for supply-chain risk prediction.

## Dataset
DataCo SMART Supply Chain Dataset

Kaggle: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

Mendeley DOI: https://doi.org/10.17632/8gx2fvg2k6.5

## Models
1. Decision Tree (Baseline)
2. Decision Tree with SentenceTransformer embeddings
3. HistGradientBoosting
4. CatBoost

## Text Embedding
Pretrained SentenceTransformer model: all-MiniLM-L6-v2

## Results

| Model | F1-score |
|---|---:|
| Decision Tree | 66.25% |
| Decision Tree + Text Embeddings | 66.29% |
| HistGradientBoosting | 71.27% |
| CatBoost | 90.16% |

## Installation

```bash
pip install -r requirements.txt
```

## Execution Instructions
1. Download the dataset from the source link.
2. Open the notebook in Google Colab.
3. Upload the dataset.
4. Install the required libraries.
5. Run the notebook cells sequentially.

## Project Details
Course: DSC624 – Natural Language Processing and Large Language Models

Project: Task 2 – Supply Chain Risk and Fraud Detection

Focus: Late Delivery Risk Prediction

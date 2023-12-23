# Subjectivity-Detection-in-News-Articles

This repository explores the application of NLP techniques to identify subjectivity in news articles. The project encompasses dataset preprocessing, GloVe embedding generation, and the training of two distinct models: Long Short-Term Memory (LSTM) and a transformer encoder. Subsequently, the exploration extends to fine-tuning BERT and GPT-2 for enhanced subjectivity detection, prompted by results from the transformer encoder.

## Key Features
* Dataset Preprocessing: Comprehensive cleaning and preprocessing of news articles.
* Embedding Generation: Utilization of GloVe embeddings for text representation.
* Model Training: Implementation of LSTM and transformer encoder models for subjectivity detection.
* Model Fine-Tuning: Experimentation with fine-tuning BERT and GPT-2 for improved performance.

## Results

| **Architecture** | **Parameters (In millions)** | **Accuracy (%) - Preprocessed Data** | **Accuracy (%) - Raw Data** |
|:------------------:|:-----------------------------:|:--------------------------------------:|:-----------------------------:|
| LSTM              | 0.102                         | 61.46                                | 62.5                        |
| Transformer       | 0.383                         | 62.5                                 | 65.62                       |
| BERT              | 109.483                       | **78.12**                            | 70.83                       |
| GPT-2             | 354.824                       | 61.45                                | 61.45                       |

*Table 1: Results on the test corpus*

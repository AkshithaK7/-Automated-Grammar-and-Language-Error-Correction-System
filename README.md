# Automated Grammar and Language Error Correction System

## Overview

This project develops an **Automated Grammar and Language Error Correction System** that detects, corrects, and provides feedback on grammatical errors in English sentences. The system leverages **T5** and **BART** transformer models, fine-tuned on the **JFLEG dataset**, achieving high accuracy in grammar correction. Additionally, **OpenAI's GPT API** is integrated to provide detailed feedback, enhancing user understanding and learning.

## Features

- Grammar Correction using fine-tuned **T5** and **BART** models.
- Interactive Feedback Generation via OpenAI GPT API.
- Evaluation using GLEU Scores for accuracy assessment.
- Support for Batch Processing to handle multiple sentences at once.
- Open-Source Implementation for transparency and extensibility.

## Data Sources

- **JFLEG Dataset:** A benchmark dataset for grammatical error correction.
- **Augmented Data:** Artificially generated incorrect sentences for robustness.
- **User Input Data:** Sentences submitted for real-time correction and feedback.

## Methodology

1. **Data Preparation:** Cleaning, tokenization, and augmentation.
2. **Model Training:** Fine-tuning **T5** and **BART** with augmented data.
3. **Grammar Correction:** Processing user input and generating corrections.
4. **Feedback Generation:** OpenAI’s GPT API provides educational insights.
5. **Evaluation:** Comparing performance using **GLEU Scores**.

## Key Findings

- T5 Model GLEU Score: **0.8049**
- BART Model GLEU Score: **0.7744**
- T5 outperformed BART, making it the preferred model for deployment.
- Feedback mechanisms significantly improve user engagement and learning.
- Augmented training data enhanced model generalization.

## Setup & Usage

### Technology Stack

 Tools & Libraries
 - Machine Learning Framework:PyTorch
 - NLP Libraries: Hugging Face Transformers, Hugging Face Datasets, NLTK
 - API Integration: OpenAI GPT API
 - Programming Language: Python

### System Requirements

 Hardware
- CUDA-enabled GPU (recommended)
- Minimum 16GB RAM
- Python 3.8+

### Dependencies

- torch
- transformers
- datasets
- nltk
- matplotlib
- wordcloud
- openai
- pandas

## Future Enhancements

- Improve handling of complex sentence structures.
- Enhance real-time response efficiency.
- Expand dataset coverage to include idiomatic expressions.
- Develop a web-based interface for broader accessibility.



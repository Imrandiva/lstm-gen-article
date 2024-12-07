# Text Generation with Recurrent Neural Networks

This project explores text generation using Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) models. It implements training, validation, and evaluation pipelines for character-level datasets, with options for hyperparameter tuning and advanced decoding techniques.

## Features

- **Model Support**: Includes both RNN and LSTM architectures for sequence learning.
- **Data Handling**: Processes character-level datasets for training, validation, and testing.
- **Hyperparameter Tuning**: Supports grid search for parameters like node size, batch size, and learning rate.
- **Text Decoding**: Offers temperature scaling and nucleus sampling for text synthesis.
- **Evaluation**: Generates text outputs and calculates BLEU scores for quality assessment.

## Usage

### Prerequisites
- Python 3.x
- Required libraries: `datasets`, `Networks`, `Training`, `bleu_score`

### Input Files
- `train.txt`: Training data
- `val.txt`: Validation data
- `test.txt`: Test data

### Running the Script
1. Define model parameters in the `model_info` dictionary (e.g., model type, nodes, batch size).
2. Execute the script:
   ```bash
   python main.py

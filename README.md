# Fine-Tuned AI Code Review Assistant

## Overview

This project demonstrates how to fine-tune a pretrained DistilBERT model using Hugging Face Transformers to classify Python code into different categories.

The model predicts one of four categories:

- Security
- Bug
- Style
- No Issue

This is an educational project designed to demonstrate supervised fine-tuning and text classification.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Pandas
- Scikit-learn
- Google Colab

## Project Workflow

1. Prepare a labeled dataset of Python code.
2. Encode the target labels.
3. Split the data into training and testing sets.
4. Load a pretrained DistilBERT model.
5. Tokenize the code examples.
6. Fine-tune the model.
7. Evaluate model performance.
8. Predict categories for new code examples.
9. Save the fine-tuned model.

## Installation

Install the required libraries:

```bash
pip install transformers datasets accelerate scikit-learn pandas torch
```

## Usage

Open the Jupyter notebook in Google Colab and execute the cells in order.

The notebook demonstrates dataset preparation, model training, evaluation, prediction, and saving the trained model.

## Dataset

The initial dataset contains a small number of manually labeled examples for demonstration purposes.

It is not sufficient for reliable real-world code review. Larger, diverse, and carefully validated datasets are needed to improve generalization.

## Limitations

- Predictions may be inaccurate.
- The dataset is very small.
- The model is not a substitute for security scanners, automated testing, or professional code review.
- A predicted category does not prove that a vulnerability or bug exists.

## Future Improvements

- Expand the training dataset.
- Evaluate the model using larger, independent test sets.
- Add more detailed code review explanations.
- Integrate static analysis tools.
- Build a web interface.
- Integrate the reviewer into a GitHub workflow.

## Learning Objectives

This project demonstrates pretrained models, tokenization, supervised fine-tuning, model evaluation, and inference using Hugging Face Transformers.

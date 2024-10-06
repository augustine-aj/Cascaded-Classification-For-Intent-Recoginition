# Cascaded-Classification-For-Intent-Recoginition

# Intent Recognition System Using BERT

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction
This project implements a two-stage intent recognition system using BERT (Bidirectional Encoder Representations from Transformers). The goal is to classify user queries into two categories: **Symptom Checker** and **Non-Symptom Checker**. The project leverages the Hugging Face Transformers library for model training and evaluation.

## Getting Started
To get a local copy of the project up and running, follow these simple steps.
1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Project Structure
The project directory has the following structure:
- **data/**: Contains the dataset used for training and testing the model.
- **models/**: 
  - **route_model/**: Folder for the binary classification model.
  - **non_symptom_model/**: Folder for the non-symptom checker classification model.
- **notebooks/**: Contains the Jupyter notebook with the model code.
- **requirements.txt**: Lists the Python dependencies required for the project.
- **README.md**: This file, providing an overview of the project.

## Requirements
Make sure you have the following Python libraries installed:
- `transformers`
- `torch`
- `pandas`
- `scikit-learn`
- `numpy`
- `joblib`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/intent-recognition-system.git
   cd intent-recognition-system
2. Install the required libraries:
   ```bash
   Copy code
   pip install -r requirements.txt

## Usage
1. Load the dataset and preprocess it.
2. Train the BERT models using the provided functions.
3. Make predictions on new queries using the predict_intent function.

## Training
The training function utilizes the AdamW optimizer and the cross-entropy loss function to optimize the BERT model's parameters over a specified number of epochs. The training process includes:
* Tokenizing input sentences.
* Performing forward and backward passes.
* Updating the model weights based on the loss.

## Evaluation
After making predictions, the model's performance is evaluated using:
* Accuracy: Percentage of correct predictions.
* F1-Score: A balance between precision and recall, useful for imbalanced datasets.
* Detailed metrics for both classes using classification_report.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or suggestions.

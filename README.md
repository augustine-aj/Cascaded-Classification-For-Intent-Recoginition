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
- [License](#license)

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




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

## Project Structure
The project directory has the following structure:
project-directory/
├── data/
│   └── faq_queries_intents.csv   # Your dataset file
├── models/
│   ├── route_model/              # Folder for the binary classification model
│   └── non_symptom_model/        # Folder for the non-symptom checker classification model
├── notebooks/
│   └── intent_recognition.ipynb  # Your Jupyter notebook with the model code
├── requirements.txt              # File listing the Python dependencies
└── README.md                     # Project README file with information


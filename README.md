# Grammar Scoring System for Spoken Audios

This repository contains the code and documentation for the "Building a Grammar Scoring System for Spoken Audios" project, which was developed as part of the SHL Hiring Assessment.

## Overview

The objective of this project is to develop a Grammar Scoring Engine that predicts a continuous score between 0 and 5 for spoken audio samples. The project covers:
- Audio preprocessing and feature extraction
- Model training using a regression algorithm
- Evaluation using Pearson Correlation
- Generating a CSV file in the required submission format



## Getting Started

1. **Google Colab:**
   - Open the notebook `grammar_scoring_system_colab.ipynb` in Google Colab.
   - Follow the instructions in the notebook to install dependencies, load the dataset, train the model, and generate predictions.

2. **Dataset:**
   - The dataset consists of training audio files, test audio files, and CSV files (`train.csv`, `test.csv`, and `sample_submission.csv`).
   - Upload the dataset to your Colab session or mount your Google Drive to access the files.

3. **Running the Code:**
   - Execute each cell in the notebook sequentially.
   - The notebook includes cells for:
     - Installing required packages (e.g., `librosa`, `sklearn`, `pandas`)
     - Loading and preprocessing audio files
     - Extracting features (e.g., MFCCs)
     - Training a regression model
     - Evaluating model performance using Pearson correlation
     - Generating the submission CSV file
     


## Dependencies

- Python 3.x
- NumPy
- Pandas
- Librosa
- scikit-learn
- Matplotlib



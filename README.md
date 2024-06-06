# Speaker-Verfication-Using-GMM

Based on the provided notebook content, here is a README file for your GitHub repository:

---

# Speaker Verification Using Gaussian Mixture Models

This project implements a speaker verification system using Gaussian Mixture Models (GMM). The project includes data preprocessing, feature extraction, and model training, leveraging various techniques to enhance the accuracy and performance of the verification system.

## Project Overview

The primary steps involved in this project are:
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Extraction
4. Model Training and Evaluation
5. Speaker Verification

## Installation

To run this project, you need to install the required libraries. You can use the following commands to install them:

```bash
pip install kaggle pydub soundfile
```

## Dataset

The dataset used for this project can be uploaded directly to Google Colab. Ensure you have the necessary permissions to access the dataset.

## Preprocessing

### Data Cleaning
Comprehensive data cleaning was performed to remove noise and ensure data integrity.

### Preemphasis Filtering
Applied preemphasis filtering to enhance high-frequency components of speech signals.

### Spectral Gating
Implemented spectral gating techniques to reduce background noise in audio recordings.

## Feature Extraction

### Mel-Frequency Cepstral Coefficients (MFCC)
Extracted MFCC features from audio signals to capture essential speech characteristics.

### Zero-Crossing Rate (ZCR)
Conducted ZCR analysis to understand the characteristics of speech signals and aid in feature selection.

### Additional Features
- Amplitude Envelope
- Root-Mean Square Energy
- Fourier Transform

## Experimental Analysis

Performed thorough experimental analyses on various de-noising methods and their effects on feature extraction, including:
- HighPass Filter
- PCEN
- Spectral Gating

## Model Training

Features were stored in a dictionary with speaker names as keys and feature dataframes as values. Trained individual speaker models and a universal background model.

## Evaluation and Verification

Evaluated the model's performance and conducted speaker verification to test the accuracy of the system.

## Usage

To train the model and evaluate the performance, run the provided notebook in Google Colab.

## Downloading Models

Trained models can be downloaded and used for speaker verification tasks.

---

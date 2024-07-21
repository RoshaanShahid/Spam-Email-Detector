# Spam Email Detector

This repository contains a Spam Email Detector project using Natural Language Processing (NLP) and Tkinter for the graphical user interface (GUI). The project is designed to classify emails as spam or not spam using a trained machine learning model.

## Features

- **Data Preprocessing:** Includes text cleaning, tokenization, stopword removal, and lemmatization.
- **Machine Learning Model:** Uses a Linear Support Vector Classifier (LinearSVC) for email classification.
- **User Interface:** Provides a user-friendly GUI built with Tkinter for easy interaction.

## Project Structure

- **data/**: Contains the `mail_data.csv` file with email data.
- **models/**: Stores the serialized model and vectorizer (`cv.pkl` and `svm.pkl`).
- **src/**: Contains the main Python script for data preprocessing, model training, and GUI creation.
- **README.md**: This file.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-email-detector.git
   cd spam-email-detector

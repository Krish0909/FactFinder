# FactFinder

## Project Overview
Web application for detecting fake news using machine learning, text summarization, and hate speech analysis.

## Key Features
- Multiple ML classifiers for fake news detection
- URL and text input support
- Text summarization
- Hate speech analysis
- Ensemble prediction model

## Configuration
- Update Hugging Face API token
- Ensure 'cleaned_WELFake_Dataset.csv' is in project directory

## Classifiers
- Naive Bayes
- Passive Aggressive Classifier
- Logistic Regression

## Limitations
- Requires internet connection
- Model accuracy varies
- Dependent on training data


## Tech Stack
- Flask
- Python
- Scikit-learn
- Transformers
- Hugging Face API

## Setup

### Prerequisites
- Python 3.8+
- pip

### Installation
```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate  # Unix
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```

### Requirements
Create `requirements.txt`:
```
flask
pandas
numpy
scikit-learn
transformers
requests
beautifulsoup4
torch
huggingface_hub
```

## Running the Application
```bash
python app.py
```

# Preview
![image](https://github.com/user-attachments/assets/d86a24c8-a1d6-4d0e-925a-68b013fe8fe3)

![image](https://github.com/user-attachments/assets/566115e9-53dd-4ffd-8e92-630e1ae17484)

# Fake and Real News Detection using RNN

This project implements a Recurrent Neural Network (RNN) model designed to identify fake news articles from real ones. By analyzing text patterns and sequential dependencies, the model classifies input text as 'Fake' or 'Real'.

## Key Features
- **Data Preprocessing:** Cleaning, tokenization, and vectorization of news text.
- **Model Architecture:** Implemented a robust RNN model to capture temporal dependencies in text.
- **Evaluation:** Includes scripts for training, evaluation, and real-time prediction.

## Dataset
- [Insert Dataset Name/Source Link Here]
- The model was trained on a labeled dataset consisting of [X,XXX] news articles.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ks-tejaskumar/Fake_and_Real_News_Detection_RNN.git
   cd Fake_and_Real_News_Detection_RNN

##Set up the environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

##Usage:
Train the model: python train.py
Evaluate performance: python evaluate.py
Predict news authenticity: python predict.py --input "Paste your headline or news text here"

##Performance Metrics:
Accuracy: [e.g., 94.5%]
Precision: [e.g., 0.93]
Recall: [e.g., 0.94]
F1-Score: [e.g., 0.93]

##Contributing:
Contributions are welcome! Please fork the repository and open a pull request.

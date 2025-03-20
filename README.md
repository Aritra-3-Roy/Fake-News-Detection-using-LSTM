# Fake News Detection using LSTM

## Overview
Fake news detection is a crucial task in today's digital world, where misinformation can spread rapidly. This project leverages a **Long Short-Term Memory (LSTM)** model to classify news articles as **Fake or Real** based on textual data.

## Features
- **Preprocessing of textual data** using NLP techniques.
- **Deep learning model** built with LSTM to classify fake news.
- **Dataset used:** Fake news dataset from Kaggle.
- **Model evaluation metrics** including accuracy, precision, recall, and F1-score.
- **Jupyter Notebook implementation** with detailed explanations.

## Dataset
The dataset used in this project consists of labeled news articles categorized as either **Fake** or **Real**. It includes:
- **title**: The title of the news article.
- **text**: The body content of the article.
- **label**: `1` for Fake news and `0` for Real news.

## Installation & Setup
To run this project, install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/Aritra-3-Roy/Fake-News-Detection-using-LSTM.git
cd Fake-News-Detection-using-LSTM

# Install dependencies
pip install -r requirements.txt
```

## Model Architecture
The LSTM model follows this structure:
1. **Text preprocessing**: Tokenization, stopword removal, and vectorization.
2. **Embedding layer**: Converts words into dense vectors.
3. **LSTM layers**: Captures sequential dependencies in text.
4. **Dense layers**: Classifies text as Fake or Real.
5. **Activation function**: Sigmoid for binary classification.

## Usage
Run the Jupyter Notebook to train and evaluate the model:
```bash
jupyter notebook Fake_News_Detection_LSTM.ipynb
```

## Results
- Achieved **high accuracy** in detecting fake news.
- Performance metrics include:
  - Accuracy: **~X%** (Replace with actual value)
  - Precision, Recall, F1-Score

## Future Enhancements
- Improve dataset quality and size.
- Experiment with transformer-based models (e.g., BERT, RoBERTa).
- Deploy as a web application using **Streamlit**.

## Contributors
- **Aritra-3-Roy** - Developer & Maintainer

## License
This project is licensed under the **MIT License**.

## Acknowledgments
- Kaggle for providing the dataset.
- TensorFlow/Keras community for deep learning resources.


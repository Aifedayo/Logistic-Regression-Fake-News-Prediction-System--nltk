
# Logistic Regression: Fake News Prediction System

## Overview
This project implements a logistic regression model to classify news articles as **real** or **fake**. Using natural language processing (NLP) techniques and the `nltk` library, the model analyzes text features to identify deceptive content, making it a valuable tool for combating misinformation.

## Dataset
- **Source**: The dataset contains labeled news articles categorized as **real** or **fake**.
- **Features**: Includes article text, headlines, and publication details.

## Project Structure
- **Text Preprocessing**: Includes tokenization, stop-word removal, stemming, and vectorization using TF-IDF.
- **Model Training**: The logistic regression model is trained on transformed text features to predict authenticity.
- **Evaluation**: Model performance evaluated with accuracy.

## Requirements
- Python libraries: `pandas`, `scikit-learn`, `numpy`, `nltk`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aifedayo/Logistic-Regression-Fake-News-Prediction-System--nltk.git
   ```
2. **Run the Notebook**:
   Open and run the Jupyter Notebook to follow the data preprocessing, model training, and evaluation steps.

## Results
- The model achieves an accuracy of 97.5% on the test data, demonstrating its effectiveness in distinguishing real news from fake news.

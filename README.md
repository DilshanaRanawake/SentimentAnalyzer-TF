# 🎭 Sentiment Analysis using TensorFlow (IMDB Reviews)

This project is a **Deep Learning-based Sentiment Analysis** model that classifies IMDB movie reviews as **Positive** or **Negative** using an **LSTM (Long Short-Term Memory) network** in TensorFlow & Keras.

## Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction
This project uses an **LSTM (Long Short-Term Memory)** network with TensorFlow to classify IMDB movie reviews as either positive or negative. The model is trained on the IMDB dataset and can predict sentiment for new reviews.

✅ Deep Learning-based Sentiment Classifier  
✅ Trained on 25,000 IMDB reviews  
✅ Uses word embeddings for text understanding  
✅ Custom review sentiment prediction  

---

## Key Features
- ✅ **IMDB dataset** (preprocessed into sequences)  
- ✅ **LSTM for sentiment classification**  
- ✅ **Visualizes training performance** (accuracy & loss)  
- ✅ Allows **custom review sentiment prediction**  

---

## 📌 Demo Screenshot
Here’s an example of the model predicting sentiment:  

![Prediction Example](https://github.com/DilshanaRanawake/SentimentAnalyzer-TF/blob/main/screenshots/1.png)  

---

## 📊 Model Performance

### 📈 **Training Accuracy vs. Validation Accuracy**
This graph shows how the model improves over **epochs**.

![Accuracy Graph](https://github.com/DilshanaRanawake/SentimentAnalyzer-TF/blob/main/screenshots/3.png)

### 📉 **Training Loss vs. Validation Loss**
The loss should decrease over time as the model learns.

![Loss Graph](https://github.com/DilshanaRanawake/SentimentAnalyzer-TF/blob/main/screenshots/2.png)

### 🔎 **Confusion Matrix**
Displays how well the model classifies positive & negative reviews.

![Confusion Matrix](https://github.com/DilshanaRanawake/SentimentAnalyzer-TF/blob/main/screenshots/4.png)

---

## 🎯 Future Improvements
- ✅ Use **Bidirectional LSTM** for better context understanding.
- ✅ Implement **Pretrained Word Embeddings** (e.g., GloVe, Word2Vec).
- ✅ Create a **Web App Interface** for easy review testing.

---

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/DilshanaRanawake/SentimentAnalyzer-TF.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the IMDB dataset or use the preprocessed version included.
2. Run the model training script:
    ```bash
    python train_model.py
    ```
3. After training, input the `sentiment_model.h5` file (output of the `train_model.py`) into the `predict_sentiment.py` and run it:
4. Alternatively, use the prediction script for custom sentiment analysis directly by inputting a review:
    ```bash
    python predict_sentiment.py "Your movie review text here."
    ```

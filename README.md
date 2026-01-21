# Sentiment Analysis on Movie Reviews

A beginner-friendly natural language processing project that trains a neural network to classify movie reviews as positive or negative using the **IMDB dataset** with **TensorFlow/Keras**.

The goal is to practice:
* Text preprocessing
* Building and training neural networks
* Evaluating performance
* Visualizing results

---

# Dataset

* 50,000 movie reviews labeled as positive or negative
* Reviews are pre-tokenized into integer sequences
* Split into training and test sets

---

# Model Overview

The neural network consists of:
1. **Embedding layer** – converts words into vectors
2. **Global Average Pooling** – summarizes text features
3. **Dense layers** – learn patterns
4. **Sigmoid output** – predicts positive sentiment probability

Trained using:
* Optimizer: Adam
* Loss function: Binary Crossentropy
* Metric: Accuracy

---

# Training Results

* Training and validation accuracy increase steadily
* Validation accuracy closely follows training accuracy
* Final test accuracy: ~85–88%

---

# Tools & Technologies

Python | TensorFlow/Keras | NumPy | Matplotlib | Google Colab

---

# Future Improvements

* Use LSTM or GRU layers
* Add custom text prediction
* Hyperparameter tuning

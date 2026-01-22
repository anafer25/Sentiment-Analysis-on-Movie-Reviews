# Sentiment Analysis on Movie Reviews

This project implements a baseline sentiment classifier using TensorFlow/Keras, inspired by standard IMDB tutorial architectures that trains a neural network to classify movie reviews as positive or negative using the **IMDB dataset** with **TensorFlow/Keras**.

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

# Result Analysis

The training and validation accuracy plot shows that:
* Both training and validation accuracy increase steadily over epochs.
* Validation accuracy closely follows the training accuracy, indicating **minimal overfitting**.
* The model reaches approximately **85–88% accuracy** on unseen test data, which is solid for a simple architecture.
* The plateau toward the later epochs suggests the model is approaching its capacity with this architecture, meaning additional complexity (like LSTM/GRU layers) could improve performance.

This plot confirms that the model **learned meaningful patterns from the text data** rather than memorizing the training set.


---

# Tools & Technologies

Python | TensorFlow/Keras | NumPy | Matplotlib | Google Colab

---

# Future Improvements

* Use LSTM or GRU layers
* Add custom text prediction
* Hyperparameter tuning

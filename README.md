# Harmonized Tariff Schedule Dataset

This project predicts whether a product entry in the Harmonized Tariff Schedule includes "Additional Duties" based on its text description.

## 📊 Dataset

The dataset includes:
- Product description text
- "Additional Duties" column (binary target: 0 or 1)

## 🧠 Model Used

A binary classification model built using:
- Tokenized and padded product descriptions
- A neural network with an embedding-like input layer (via dense layers)

## 🔧 Tech Stack

- **Pandas** & **NumPy** for data processing
- **TensorFlow / Keras** for building and training the model
- **Tokenizer** and `pad_sequences` from Keras for text preprocessing

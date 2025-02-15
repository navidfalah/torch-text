# Text Classification with PyTorch and TorchText 📚🤖

This project demonstrates **text classification** using **PyTorch** and **TorchText** on a **Twitter sentiment analysis dataset**. The goal is to classify tweets as positive or negative using an LSTM-based model. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** and **TorchText** to build and train an LSTM model for text classification. 🤖📚
- Leverages the **Twitter Sentiment Analysis Dataset** for training and validation. 🧠🔍
- Implements text preprocessing, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch torchtext pandas spacy
!python -m spacy download en_core_web_sm
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the Twitter Sentiment Analysis Dataset.
2. **Preprocess Data**: Applies text preprocessing and splits the data into training, validation, and test sets.
3. **Build Model**: Defines and trains an LSTM model for text classification.
4. **Evaluate Model**: Evaluates the model's performance on the validation set.
5. **Text Augmentation**: Demonstrates back translation for text augmentation.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the Twitter Sentiment Analysis Dataset.
  - Applies text preprocessing and splits the data into training, validation, and test sets.

- **Model Definition**:
  - Defines an LSTM model with embedding and linear layers.
  - Uses cross-entropy loss for training.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and validation loss.

- **Evaluation**:
  - Evaluates the model's performance on the validation set.
  - Visualizes training and validation loss.

- **Text Augmentation**:
  - Demonstrates back translation for text augmentation.

---

## Results 📊

- **Training/Validation Loss**: The model achieves low training and validation loss.
- **Text Augmentation**: Demonstrates back translation for generating augmented text data.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/5: Training Loss: 0.123, Validation Loss: 0.045
Epoch 2/5: Training Loss: 0.045, Validation Loss: 0.032
```

---

## Dependencies 📦

- `torch`
- `torchtext`
- `pandas`
- `spacy`
- `googletrans`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝

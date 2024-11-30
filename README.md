# Next-Word Predictor Using LSTM

This project is a **Next-Word Prediction** system built using a **Long Short-Term Memory (LSTM)** neural network model. The model predicts the next word in a given sequence of text, enhancing text input methods and aiding in various natural language processing (NLP) applications.

## Project Overview

The system takes an input text sequence and predicts the next word based on learned patterns from a training dataset. It leverages an LSTM model to handle the sequential nature of text and provide accurate predictions.

### Key Features:
- **LSTM Neural Network** for sequence prediction.
- **Tokenizer** for handling input text sequences.
- **Customizable Vocabulary Size** and **Sequence Length**.
- Ability to generate multiple word suggestions.

---

## Project Structure

```
├── model.h5               # Trained LSTM model
├── tokenizer.pkl          # Tokenizer used for sequence transformation
├── index.html             # Web-based user interface
├── style.css              # Styling for the web interface
├── main.js                # JavaScript for handling predictions
├── Next Word Predictor.ipynb # Training and model development Jupyter notebook
├── README.md              # Project documentation (this file)
```

---

## Requirements

To reproduce or enhance this project, the following Python libraries are required:

```bash
pip install tensorflow numpy pickle-mixin
```

---

## Dataset

The dataset used for training the model contains various sequences of text to ensure robust learning of language patterns. You can modify the dataset in the Jupyter notebook to enhance or focus predictions on specific domains.

---

## Model Training

1. **Preprocessing**: The text data is tokenized and transformed into sequences suitable for LSTM training.
2. **Model Architecture**: The LSTM network is configured with layers suited for sequential data prediction.
3. **Training**: The model is trained using the dataset until it achieves satisfactory accuracy.

---

## Running the Project

### 1. Locally:

1. Open the `index.html` file in any web browser.
2. Input a seed text, and the system will display predicted next-word suggestions.

### 2. Jupyter Notebook:

1. Open `Next Word Predictor.ipynb`.
2. Run all cells to train and test the model.

---

## How to Customize

- **Model Tuning**: Modify the LSTM layers and parameters in the notebook.
- **Sequence Length**: Adjust the `max_sequence_len` variable to change the length of input sequences.
- **Vocabulary**: Use different datasets to broaden the vocabulary and improve model accuracy.

---

## Future Improvements

- Enhance the UI for better user interaction.
- Integrate multiple language support.
- Improve prediction accuracy by increasing the dataset size.
- Implement more efficient model compression for faster prediction.

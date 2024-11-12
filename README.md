# Generating Poetic Texts with RNN

This project leverages Recurrent Neural Networks (RNNs) to generate poetic texts based on a provided dataset of poetry. Using sequence-to-sequence learning, this model captures the structure, rhythm, and style of poems, allowing for creative, original text generation that mirrors traditional poetic language.

## Features

- **Text Generation with RNN**: Generates poetic text by training an RNN on a poetry dataset.
- **Character-level Language Modeling**: The model is trained character-by-character for detailed text prediction.
- **Customizable Training**: Adjustable parameters for epochs, batch size, and learning rate to control model training.
- **Preprocessing and Tokenization**: Preprocesses text data and tokenizes it for RNN compatibility.
- **Model Saving and Loading**: Save and reload models to continue training or generate texts as needed.

## Requirements

- Python 3.x
- Keras
- TensorFlow
- NumPy

To install dependencies, run:

```bash
pip install -r requirements.txt
```
## Usage

Prepare Dataset: Add your poetry dataset in a .txt file (e.g., poems.txt).
Train the Model: Use the following command to train the RNN on the dataset:

```bash
python train_model.py --data_path "data/poems.txt" --epochs 50
```
## Results
The trained model produces lines that echo the style of the input poetry. Experiment with various seed words to explore different poetic expressions!

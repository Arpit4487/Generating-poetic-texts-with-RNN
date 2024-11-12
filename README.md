# Generating-poetic-texts-with-RNN

This project uses Recurrent Neural Networks (RNNs) to generate poetic texts based on a given dataset of poetry. Leveraging sequence-to-sequence learning, this model captures the structure, rhythm, and style of poems, producing creative, original texts that mimic the language of traditional poetry.

Features
Text Generation with RNN: Generates poetic text by training an RNN on a poetry dataset.
Character-level Language Modeling: The model is trained character-by-character for fine-grained text prediction.
Customizable Training: Adjustable parameters for epochs, batch size, and learning rate to control training precision.
Preprocessing and Tokenization: Preprocesses text data and tokenizes it for compatibility with RNN input requirements.
Model Saving and Loading: Save and reload models to continue training or generate texts at any time.
Requirements
Python 3.x
Keras
TensorFlow
NumPy
Install the dependencies using:

bash
Copy code
pip install -r requirements.txt
Usage
Prepare Dataset: Include your poetry dataset in a .txt file (e.g., poems.txt).
Train the Model: Run the training script to fit the RNN to the dataset.
bash
Copy code
python train_model.py --data_path "data/poems.txt" --epochs 50
Generate Poetic Texts: Once trained, generate poetic text based on a seed word or phrase.
bash
Copy code
python generate_text.py --seed "Love is"
Results
The trained model can produce lines of text that resemble the input style of poetry. Experiment with different seed words to explore the model's creativity!

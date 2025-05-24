# Next Word Predictor: Shakespeare's Hamlet with LSTM

This project utilizes a Long Short-Term Memory (LSTM) model to predict the next word in a sequence from Shakespeare's *Hamlet*. The model is trained on the complete text of *Hamlet* and can generate contextually relevant word predictions based on a given input.

## 📁 Project Structure

- `code.ipynb`: Jupyter Notebook containing the full implementation of the LSTM model, including data preprocessing, model training, and evaluation.
- `shakespeare-hamlet.txt`: Raw text file containing the complete text of Shakespeare's *Hamlet*, used for training the model.
- `tokenizer.pkl`: Serialized tokenizer object used to convert text into sequences of integers for model input.
- `nextword_model.h5`: Saved Keras model containing the trained LSTM network for word prediction.
- `Training_Loss_And_Accuracy_Plot.png`: Visual plot showing the training loss and accuracy over epochs.

## ⚙️ Requirements

To set up the environment for this project, install the necessary dependencies using the provided `requirements.txt` file.

## 🧑‍💻 Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/TulsiBasetti/Next_Word_Predictor-_Shakeshpeare_Hamlet_LSTM.git
   cd Next_Word_Predictor-_Shakeshpeare_Hamlet_LSTM
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
3. Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook code.ipynb

## 📈 Training and Evaluation
The model's performance is visualized through the Training_Loss_And_Accuracy_Plot.png, which shows the loss and accuracy metrics over the training epochs.

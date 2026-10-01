# Next Word Prediction using RNN-LSTM

A deep learning project that predicts the next word based on the text entered by the user. The project uses an **LSTM (Long Short-Term Memory) neural network** to learn patterns from text and generate the most likely next word.

## Features

* Predicts the next word from user input
* Uses an LSTM-based RNN model
* Text preprocessing with Keras Tokenizer
* Sequence padding for model input
* Streamlit web interface
* Displays the predicted next word

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Streamlit
* LSTM
* RNN
* Natural Language Processing (NLP)

## Project Structure

```text
Next-word-prediction-using-RNN-LSTM/
│
├── app.py
├── lstm_model.h5
├── tokenizer.pkl
├── requirements.txt
└── README.md
```

## How It Works

1. The user enters a sentence in the Streamlit application.
2. The text is converted into numerical tokens using the trained tokenizer.
3. The sequence is padded to the required input length.
4. The LSTM model predicts the probability of the next word.
5. The word with the highest probability is selected as the prediction.
6. The predicted word is displayed in the application.

## Model Details

* Model: LSTM-based RNN
* Vocabulary Size: 10,000
* Embedding Dimension: 25
* LSTM Units: 128
* Maximum Sequence Length: 745
* Output Layer: 10,000-class Softmax

## Installation

Clone the repository:

```bash
git clone https://github.com/abhinav2-005/Next-word-prediction-using-RNN-LSTM.git
cd Next-word-prediction-using-RNN-LSTM
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## Example

**Input:**

```text
Machine learning is
```

**Predicted next word:**

```text
...
```

The prediction depends on the patterns learned by the trained model.

## Files

* `app.py` – Streamlit frontend and prediction logic
* `lstm_model.h5` – Trained LSTM model
* `tokenizer.pkl` – Saved text tokenizer
* `requirements.txt` – Required Python libraries

## Future Improvements

* Train the model on a larger and more diverse dataset
* Improve prediction accuracy
* Predict multiple next words
* Add top-k word predictions
* Improve the Streamlit interface

## Author

**Abhinav Raavi**

GitHub: https://github.com/abhinav2-005

```
```

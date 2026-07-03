# 📝 LSTM Next Word Prediction

A Deep Learning project that predicts the **next word** in a sentence using an **LSTM (Long Short-Term Memory)** model trained on **William Shakespeare's Hamlet**. The project demonstrates the complete NLP pipeline, from text preprocessing to model inference, with a simple Streamlit web application.

---

## 🚀 Features

- Train an LSTM model for next-word prediction
- Uses **Shakespeare's Hamlet** as the training corpus
- Text preprocessing and tokenization
- N-gram sequence generation
- Sequence padding
- Early Stopping to reduce overfitting
- Save and load the trained model and tokenizer
- Interactive prediction using Streamlit

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NLTK
- NumPy
- Streamlit
- Pickle

---

## 📂 Project Structure

```text
LSTM-NEXT-WORD-PREDICTION/
│
├── app.py                 # Streamlit application
├── experiments.ipynb      # Model training notebook
├── hamlet.txt             # Shakespeare's Hamlet dataset
├── next_word_lstm.h5      # Trained LSTM model
├── tokenizer.pickle       # Saved tokenizer
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/amnsingh05/lstm-next-word-prediction.git
cd lstm-next-word-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 🧠 Model Workflow

```
Hamlet Dataset
      │
      ▼
Text Preprocessing
      │
      ▼
Tokenization
      │
      ▼
N-Gram Sequence Generation
      │
      ▼
Padding
      │
      ▼
Embedding Layer
      │
      ▼
LSTM
      │
      ▼
Dense + Softmax
      │
      ▼
Next Word Prediction
```

---

## 💡 Example

**Input**

```text
To be or not to be
```

**Predicted Output**

```text
that
```

> Prediction may vary depending on the trained model.

---

## 📚 Concepts Covered

- Natural Language Processing (NLP)
- Tokenization
- Sequence Modeling
- Word Embeddings
- LSTM Networks
- Early Stopping
- Model Serialization
- Next Word Prediction

---

## 📌 Future Improvements

- GRU implementation
- Transformer-based model
- Top-K predictions
- Beam Search
- Larger training datasets
- Deploy online

---

## 👨‍💻 Author

**Aman Singh**

**GitHub:** https://github.com/amnsingh05

**Repository:** https://github.com/amnsingh05/lstm-next-word-prediction

**LinkedIn:** https://www.linkedin.com/in/amnsingh0

---

⭐ If you found this project helpful, consider giving it a star!

<h1 align="center">🧠 LSTM Next Word Predictor</h1>

<p align="center">
A PyTorch implementation of an LSTM-based Next Word Prediction model trained on the <b>Alice in Wonderland</b> corpus.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![NLP](https://img.shields.io/badge/NLP-LSTM-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Learning%20Project-orange?style=for-the-badge)

</p>

<p align="center">
⭐ Built from scratch using PyTorch as part of my NLP & Deep Learning learning journey.
</p>

---
# 🧠 LSTM Next Word Predictor

> **A PyTorch implementation of an LSTM-based Next Word Prediction model trained on the _Alice in Wonderland_ corpus.**

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![NLP](https://img.shields.io/badge/NLP-LSTM-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Learning%20Project-orange?style=for-the-badge)

</p>

---

# 📖 About The Project

This repository is part of **my learning journey in Deep Learning and Natural Language Processing (NLP).**

The objective of this project was to understand **how an LSTM learns language patterns** by predicting the next word in a sentence.

Instead of relying on high-level libraries, I implemented the complete pipeline manually—from text preprocessing to training an LSTM model and generating text autoregressively.

---

# 🚀 Features

✅ Text preprocessing

✅ Tokenization using NLTK

✅ Vocabulary creation

✅ Unknown token handling (`<unk>`)

✅ Sequence generation

✅ Sequence padding

✅ Train-Test Split

✅ Custom PyTorch Dataset & DataLoader

✅ LSTM implementation

✅ Next Word Prediction

✅ Autoregressive text generation

---

# 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| Deep Learning | PyTorch |
| NLP | NLTK |
| Data Processing | NumPy |
| Visualization | Matplotlib |
| ML Utilities | Scikit-Learn |

---

# 📂 Project Structure

```text
LSTM-Next-Word-Predictor/
│
├── data/
│   └── alice.txt
│
├── notebooks/
│   └── Next_word_LSTM.ipynb
│
├── models/
│   └── lstm_model.pth
│
├── images/
│   ├── training_loss.png
│   └── prediction_demo.png
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

# 🏗️ Model Architecture

```
Input Sequence
        │
        ▼
Embedding Layer
        │
        ▼
LSTM Layer
        │
        ▼
Fully Connected Layer
        │
        ▼
Softmax
        │
        ▼
Predicted Next Word
```

---

# 📈 Training Performance

The training loss consistently decreases over epochs, showing that the model successfully learns language patterns from the dataset.

<p align="center">

![Training Loss](images/training_loss.png)

</p>

---

# 📊 Evaluation

| Metric | Score |
|---------|-------|
| Training Loss | **0.2433** |
| Training Accuracy | **93.16%** |

> Since this project focuses on language generation, qualitative examples are also included below to demonstrate the model's behavior.

---

# ✨ Example Prediction

### Input Prompt

```text
Alice was beginning to
```

### Generated Output

```text
Alice was beginning to get
Alice was beginning to get very
Alice was beginning to get very tired
Alice was beginning to get very tired of
Alice was beginning to get very tired of sitting
Alice was beginning to get very tired of sitting by
Alice was beginning to get very tired of sitting by her
Alice was beginning to get very tired of sitting by her sister
Alice was beginning to get very tired of sitting by her sister on
Alice was beginning to get very tired of sitting by her sister on the
Alice was beginning to get very tired of sitting by her sister on the matter
Alice was beginning to get very tired of sitting by her sister on the matter.
```

<p align="center">

![Prediction Demo](images/prediction_demo.png)

</p>

---

# 📚 What I Learned

Working on this project helped me understand:

- How text is converted into numerical sequences
- Vocabulary creation for NLP models
- Tokenization and preprocessing
- Sequence padding
- Building custom PyTorch datasets
- Training recurrent neural networks (LSTMs)
- Language modeling
- Autoregressive text generation
- Model evaluation in NLP

---

# 🚀 Future Improvements

- [ ] Add Dropout Regularization
- [ ] Implement Multi-layer LSTM
- [ ] Compare with a GRU model
- [ ] Train on a larger text corpus
- [ ] Explore Beam Search decoding
- [ ] Build a Transformer-based next-word predictor

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/<YOUR_USERNAME>/LSTM-Next-Word-Predictor.git
```

Install the dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```text
notebooks/Next_word_LSTM.ipynb
```

---

# 💡 Note

This project was built as part of my learning journey in **Deep Learning** and **Natural Language Processing**.

The goal was to understand the concepts behind LSTMs and language modeling by implementing the complete workflow from scratch. Feedback, suggestions, and improvements are always welcome!

---
## 🤝 Connect With Me

GitHub: https://github.com/Sanjay-jat

If you have suggestions, ideas, or feedback about this project, feel free to open an issue or connect with me.

---
## ⭐ If you found this project interesting, consider giving it a star!


### Language Modeling with LSTM built with:

* **Python** for preprocessing and model scripting
* **PyTorch** for building the language model with LSTM
* **TorchText** for vocabulary management and tokenization
* **NLTK** for text preprocessing and tokenization
* **Matplotlib** for visualizing training performance
* **Gutenberg Dataset** for sample training text

---

# LSTM-based Language Modeling from Scratch

This project implements a **word-level language model** trained on a text corpus using an **LSTM (Long Short-Term Memory)** network. The model learns to predict the next word given a sequence of preceding words. It leverages PyTorch and its recurrent neural network modules to build and train the model step by step.

### **Key Insights:**

* Uses `nltk.corpus.gutenberg` to load and clean training data.
* Builds a vocabulary using `torchtext.vocab` and maps words to indices.
* Trains an `nn.LSTM` model to predict the next token in a sequence.
* Explores how loss reduces over epochs and provides generated text as output.
* Provides an example of text generation using a seed word to sample output.

---

## Dependencies

```bash
pip install torch torchtext nltk matplotlib
```

---

## License

This project is licensed under the MIT License.

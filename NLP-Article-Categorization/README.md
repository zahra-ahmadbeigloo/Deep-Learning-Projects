### Article Categorization using:

* **Python** for preprocessing and training logic
* **PyTorch** for model architecture, training, and evaluation
* **TorchText** for tokenization and vocabulary building
* **Pandas** for reading and organizing dataset
* **Matplotlib** for plotting training metrics

---

# Article Categorization with RNN (Text Classification)

This project performs **multi-class article classification** using a custom RNN model built in PyTorch. The dataset consists of news articles paired with category labels, and the pipeline includes preprocessing, tokenization, vocabulary generation, and model training.

### **Key Insights:**

* Implements `get_tokenizer()` and `build_vocab_from_iterator()` to build a vocab from raw text
* Uses PyTorch `Dataset` and `DataLoader` to handle batch training with text inputs
* Applies **BOS/EOS tagging**, sequence padding, and label encoding for compatibility
* Trains a simple RNN-based classifier to predict article categories
* Captures training loss and accuracy metrics across epochs

---

## Dependencies
```bash
pip install torch torchtext pandas matplotlib
```

---

## License
This project is licensed under the MIT License.

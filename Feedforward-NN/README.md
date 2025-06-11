### Feedforward Neural Networks (Fully Connected Networks) built with:

* **Python** for preprocessing, modeling, and data handling
* **PyTorch & TensorFlow/Keras** for model definition and training
* **Scikit-learn, Pandas, NumPy** for dataset manipulation and evaluation
* **Matplotlib** for result visualization and diagnostics

---

# Feedforward Neural Network Projects (Classification Tasks)

This directory contains multiple projects implementing **Multilayer Perceptrons (MLPs)** for classification problems using fully connected layers. These models are trained on tabular and image data including MNIST digits, breast cancer diagnostics, and iris classification.

Each project explores model architecture design, activation functions, optimizers (SGD, Adam), loss functions, and batch training using PyTorch or Keras. It is intended to provide foundational understanding of deep learning with MLPs across binary and multiclass settings.

---

### **Key Insights:**

* Models trained with both `CrossEntropyLoss` and `Softmax` outputs for classification.
* Regularization (like dropout or deeper layers) tested for generalization and overfitting.
* Model saving/loading mechanisms included (e.g. `.keras`, PyTorch `.pt` state dict).
* Optimization and performance vary with architecture depth, batch size, and learning rate.
* Feature normalization and one-hot encoding improve training stability.

---

### Current Subprojects

#### MNIST Digit Classification (Keras)

* Input: Flattened 28x28 grayscale images (784-dim)
* Achieved up to **98.44%** validation accuracy
* Includes model serialization and reloading for continued training

#### Breast Cancer & Iris Classification (PyTorch)

* Binary and multi-class classification with tabular features
* Tested different optimizers, hidden sizes, and dataset balancing strategies
* Accuracy and loss curves analyzed across multiple runs

---

## Dependencies

```bash
pip install tensorflow torch scikit-learn pandas numpy matplotlib ucimlrepo
```

---

## License

This directory and its projects are licensed under the MIT License.

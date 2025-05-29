### Basic CNN on MNIST built with:

* **Python** for backend logic and training control
* **TensorFlow / Keras** for building and training the CNN
* **NumPy** for efficient numerical operations
* **Matplotlib** for visualizing training and evaluation

---

# Basic CNN for Handwritten Digit Recognition

This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The model is built using TensorFlow/Keras and trained on grayscale images (28x28) to recognize digits 0 through 9.

### **Key Insights:**

* A two-layer CNN architecture is sufficient to achieve >98% accuracy on MNIST.
* Adding a second convolutional and pooling block improves generalization.
* Optimizer: **Adam** combined with **categorical crossentropy** gives fast convergence.
* Final test error rate was reduced to less than 1.5% by tuning batch size and epochs.
* Visualizations of predictions and training metrics helped track learning performance.

---

## Dependencies

```bash
pip install tensorflow matplotlib numpy
```

---

## License

This project is licensed under the MIT License.

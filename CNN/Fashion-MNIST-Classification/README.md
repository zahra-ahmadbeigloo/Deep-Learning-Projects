### **Fashion MNIST Classification with CNN built with:**

* **Python** for model development and training
* **TensorFlow** & **Keras** for building and training the CNN
* **Matplotlib** for visualization
* **NumPy** for array manipulation and preprocessing
* **Fashion-MNIST dataset** for image-based fashion category classification

---

# Fashion MNIST Image Classification

This project builds and trains a **Convolutional Neural Network (CNN)** to classify grayscale images of clothing items into one of 10 fashion categories (e.g., T-shirt, sneaker, coat, etc.) from the Fashion-MNIST dataset. The model is trained using Keras' high-level API on TensorFlow backend, with dropout and ReLU activations to improve generalization and performance.

### **Key Insights:**

* The model uses two convolutional layers followed by max-pooling to extract image features.
* **Dropout** layers are added to reduce overfitting, improving test performance.
* Achieves high classification accuracy (\~89–91%) on test data.
* Visualizations include sample predictions and performance metrics across epochs.
* Fashion-MNIST proves effective as a benchmarking dataset for testing CNN architectures.

---

## Dependencies

```bash
pip install tensorflow matplotlib numpy
```

---

## License

This project is licensed under the MIT License.

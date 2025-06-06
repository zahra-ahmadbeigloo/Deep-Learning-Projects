### Crack Detection with CNNs built with:

* **Python** for data handling and training logic
* **TensorFlow/Keras** for deep learning using **Sequential API**
* **NumPy** for preprocessing and array manipulation
* **Matplotlib** for plotting model performance
* **OpenCV** or PIL for image handling and loading

---

# Concrete Crack Classification using CNN (Binary Classification)

This project implements a **Convolutional Neural Network (CNN)** to classify images of concrete as either **cracked** or **non-cracked**. The model is trained on a dataset containing thousands of labeled concrete surface images.

### **Key Insights:**

* Images are resized and normalized before being fed into the CNN.
* The architecture includes `Conv2D`, `MaxPooling2D`, `Dropout`, and `Dense` layers.
* Binary classification is achieved using `sigmoid` activation in the output layer.
* The model achieves high validation accuracy and visualizations show improved learning across epochs.
* `EarlyStopping` and `ModelCheckpoint` callbacks are used to enhance generalization and training efficiency.

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib opencv-python pillow
```

---

## License

This project is licensed under the MIT License.


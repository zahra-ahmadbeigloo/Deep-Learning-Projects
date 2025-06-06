### Built with:

* Python
* TensorFlow / Keras
* Pretrained Models: VGG16, ResNet50
* Matplotlib, NumPy
* Jupyter Notebook
---

## VGG16 vs ResNet50 for Image Classification

This project compares the performance of two popular pre-trained deep learning models—**VGG16** and **ResNet50**—on an image classification task using transfer learning. The models were fine-tuned and evaluated on a custom dataset to determine which architecture offers better performance in terms of accuracy, loss, and generalization.

---

### Project Description

The notebook explores how transfer learning with VGG16 and ResNet50 behaves on the same dataset:

* Image preprocessing using `ImageDataGenerator`
* Loading VGG16 and ResNet50 without top layers
* Adding custom dense layers for binary classification
* Freezing the convolutional base and training the dense layers
* Unfreezing select layers for fine-tuning
* Evaluating accuracy, loss, and plotting training curves

---

### Key Insights

* VGG16 tends to overfit more easily and has a higher parameter count.
* ResNet50's residual blocks allow for better convergence and generalization.
* ResNet50 achieved better validation accuracy and lower loss in fewer epochs.

---

### Dependencies

Install necessary packages using:

```bash
pip install tensorflow matplotlib numpy
```

---

### License

This project is for educational use only.

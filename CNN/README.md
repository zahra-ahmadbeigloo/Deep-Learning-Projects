# CNN Projects

This directory contains multiple deep learning projects focused on **Convolutional Neural Networks (CNNs)**, covering fundamentals to applied image classification. Implemented using **PyTorch** and **TensorFlow/Keras**, these projects demonstrate core techniques such as **data augmentation**, **transfer learning**, **custom architecture**, and **training visualization**.

---

## Concepts Covered

* CNN Layer Stacking (Conv → ReLU → Pool → FC)
* Batch Normalization, Dropout
* Data Augmentation Techniques
* Feature Map Visualization
* Loss & Accuracy Plotting
* Transfer Learning (in related projects)

---

## **Projects Included:**

### **Simple CNN for Image Classification**

* **Tools:** PyTorch, torchvision, matplotlib
* Built a minimal CNN with convolutional layers, ReLU, and max pooling to classify grayscale images.
* Trained using SGD and cross-entropy; performance visualized across epochs.
* **Sub-directory:** `Simple-CNN`

---

### **Fashion MNIST Classification (PyTorch)**

* **Tools:** PyTorch, torchvision, matplotlib
* Classified 10 clothing categories using a CNN.
* Visualized prediction probabilities and learned feature maps.
* Focused on model evaluation and error analysis.
* **Sub-directory:** `Fashion-MNIST`

---

### **Anime Image Classification with CNN**

* **Tools:** PyTorch, PIL, torchvision
* Preprocessed anime-style images and classified characters or traits using CNNs.
* Managed a custom dataset, optimized training loop, and evaluated per-class accuracy.
* **Sub-directory:** `Anime-Image-Classification-CNN`

---

### **Data Augmentation in CNN**

* **Tools:** TensorFlow, Keras, ImageDataGenerator
* Demonstrated real-time data augmentation techniques (flipping, shifting, zooming).
* Compared model performance with and without augmentation.
* Improved generalization by expanding training diversity.
* **Sub-directory:** `Data-Augmentation-in-CNN`

---

## Dependencies

Install project-wide tools with:

```bash
pip install torch torchvision matplotlib tensorflow
```

Each sub-project may include its own environment file for specific requirements.


---

## License

All projects in this repository are open-sourced under the MIT License.



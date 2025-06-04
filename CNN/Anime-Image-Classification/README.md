### Anime Image Classification with CNN built with:
- **Python** for modeling and preprocessing
- **NumPy** & **Matplotlib** for tensor handling and visualization
- **PyTorch** for deep learning (custom CNN architecture)
- **Google Colab** for cloud-based model training

---

# Anime Character Classification with CNN

This project builds and trains a custom Convolutional Neural Network (CNN) to classify anime characters from image data. The model is designed and trained from scratch using PyTorch, handling grayscale input images and predicting classes with a softmax classifier.

### **Key Insights:**
- Dataset preprocessing involved reshaping and normalizing input tensors with shape `(batch_size, 1, 64, 64)` for grayscale images.
- CNN model includes `Conv2D`, `ReLU`, and `MaxPooling` layers to extract spatial features.
- Achieved non-trivial accuracy despite limited dataset size, demonstrating effectiveness of basic CNN architecture.
- Used forward hooks to inspect output tensor shapes through layers—useful for debugging and understanding internal transformations.

---

## Dependencies

```bash
pip install torch torchvision matplotlib numpy
```

---
License
This project is licensed under the MIT License.

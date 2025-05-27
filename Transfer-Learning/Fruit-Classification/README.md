### Fruit Classification Using Transfer Learning built with:
- **Python** for data preprocessing and deep learning workflows
- **TensorFlow / Keras** for model design and training (using VGG16)
- **ImageDataGenerator** for image augmentation and loading
- **Matplotlib** for plotting training and validation metrics

---

# Fruit Classification Using VGG16 Transfer Learning

This project demonstrates how to classify different types of fruits using transfer learning. A pre-trained **VGG16 model** is fine-tuned for this multi-class classification task with 24 fruit categories.

The pipeline includes:
- Data augmentation
- Feature extraction via a frozen convolutional base
- Fine-tuning of the last few layers
- Learning rate scheduling and early stopping

---

## Key Insights:
- **Initial training** with frozen base layers achieved ~72% validation accuracy.
- **Fine-tuning** the last 5 layers improved performance to over **83% validation accuracy**.
- Use of `ReduceLROnPlateau` dynamically reduced learning rate to enhance convergence.
- Visualization and predictions on unseen test images confirmed robust classification.

---

## Dependencies

```bash
pip install tensorflow==2.16.2
pip install matplotlib==3.9.2
pip install numpy==1.26.4
pip install scipy==1.14.1
pip install scikit-learn==1.5.2
````

---

## License

This project is licensed under the MIT License.

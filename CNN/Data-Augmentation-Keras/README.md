### Data Augmentation in CNNs with Keras built with:  
- **Python** for scripting and image preprocessing  
- **TensorFlow/Keras** for deep learning and `ImageDataGenerator` APIs  
- **NumPy** for image matrix manipulation  
- **Matplotlib** for visualization of augmented samples  
- **Pillow (PIL)** for creating and modifying base image files  

---

# Data Augmentation with Keras

This project demonstrates how to apply **real-time data augmentation** to image datasets using `ImageDataGenerator` in Keras. It covers a variety of techniques to artificially expand training data and improve generalization of CNNs. The project uses synthetic and CIFAR-10 data as input and visualizes transformations including **rotation, zoom, flips, normalization, and custom noise functions**.

### **Key Insights:**  
- Augmentations such as **rotation, shift, shear, zoom, and flip** improve model robustness by simulating real-world distortions.  
- **Normalization** (both sample-wise and feature-wise) helps in faster and more stable model convergence.  
- Custom preprocessing functions (e.g., **random noise injection**) can simulate specific image conditions like sensor noise or blur.  
- Visual inspection of augmented images confirms the diversity and validity of transformations.  
- These techniques are essential in small or imbalanced datasets to prevent overfitting and improve generalization.

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib pillow
```

---
## License
This project is licensed under the MIT License.

### Classifying Waste Products Using Transfer Learning built with:  
- **Python** for image preprocessing and model training  
- **TensorFlow / Keras** for deep learning modeling  
- **VGG16** pretrained model for feature extraction and fine-tuning  
- **ImageDataGenerator** for real-time data augmentation  
- **Matplotlib** for visualizing performance metrics  
- **Sklearn** for evaluation metrics like precision, recall, and F1-score  

---

# Waste Product Classification (Organic vs Recyclable)

This project applies **Transfer Learning using VGG16** to classify waste products as either **Organic (O)** or **Recyclable (R)**. It leverages feature extraction and fine-tuning phases, improving classification accuracy with progressive training strategies.

### **Key Insights:**  
- VGG16 was used as the base model with pretrained ImageNet weights.
- Feature extraction followed by fine-tuning yielded higher classification accuracy.
- Custom learning rate scheduler and early stopping enhanced training stability.
- Final accuracy: **83%** on the test set after fine-tuning.

---

## Dependencies

```bash
pip install tensorflow==2.17.0 numpy==1.26.0 matplotlib==3.9.2 scikit-learn==1.5.1
```

---

## License
This project is licensed under the MIT License.

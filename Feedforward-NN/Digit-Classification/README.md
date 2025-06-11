### MNIST Digit Classification using Feedforward Neural Network built with:  
- **Python** for data loading and modeling  
- **TensorFlow / Keras** for model building, training, and evaluation  
- **Matplotlib** for visualizing sample data  
- **NumPy** for matrix reshaping and scaling  
- **One-hot Encoding** for categorical targets  
- **Model Saving/Loading** with `.keras` serialization  

---

# Dense Neural Network for MNIST Digit Classification

This project implements a deep feedforward neural network (fully connected MLP) to classify handwritten digits from the MNIST dataset. The network is built using Keras `Sequential` API and trained using softmax cross-entropy loss. The model is also saved and later reloaded for further training and evaluation.

### **Key Insights:**  
- MNIST images are flattened from 28×28 to 784-dimensional vectors.  
- The first model achieved **98.06%** validation accuracy with 3 Dense layers.  
- A deeper architecture (5 hidden layers) achieved **98.44%** accuracy.  
- The saved model was reloaded and fine-tuned for 10 more epochs.  
- Final reloaded model achieved **97.98%** accuracy — indicating slight overfitting on continued training.  

---

## Dependencies

```bash
pip install tensorflow matplotlib numpy
```

---
## License
This project is licensed under the MIT License.

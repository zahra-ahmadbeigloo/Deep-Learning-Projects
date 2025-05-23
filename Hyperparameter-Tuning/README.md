### MNIST Classification with Keras Tuner built with:  
- **Python** for scripting and numerical processing  
- **TensorFlow / Keras** for model creation, compilation, and training  
- **Keras Tuner** for hyperparameter tuning (Random Search)  
- **Scikit-learn** for train-test splitting  
- **NumPy** for reshaping and normalization  

---

# Hyperparameter Tuning for MNIST Digit Classification

This project performs **hyperparameter optimization** on a feedforward neural network (MLP) using **Keras Tuner's RandomSearch** on the MNIST dataset. The goal is to identify the optimal number of hidden units and learning rate for maximum validation accuracy.

### **Key Insights:**  
- A simple MLP with a tunable Dense layer was evaluated over 10 trials using `RandomSearch`.  
- Best model achieved **97.5% validation accuracy** with:
  - `units = 320`
  - `learning_rate ≈ 0.00127`  
- After tuning, the best model was retrained and evaluated, achieving **97.4% test accuracy**.  
- The model demonstrates high accuracy with minimal architecture and optimized training hyperparameters.

---

## Dependencies

```bash
pip install tensorflow keras-tuner scikit-learn numpy
```

---
## License
This project is licensed under the MIT License.

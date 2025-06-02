### Custom Dense Layer with TensorFlow built with:
- **Python** for backend logic and scripting  
- **TensorFlow / Keras** for building and training neural network models  
- **NumPy** for numerical computations and synthetic data creation  
- **Matplotlib** for loss visualization (optional)  
- **ModelCheckpoint & Evaluation** for testing generalization

---

# Custom Dense Layer Implementation in TensorFlow

This project demonstrates how to define and integrate a custom fully connected (Dense) layer in TensorFlow using object-oriented programming with subclassing. The model is trained on synthetic data for a multi-class classification task and evaluated using cross-entropy loss.

### **Key Insights:**  
- Defined a reusable custom `Dense` layer using `tf.keras.layers.Layer` with manual weight and bias initialization.  
- Trained a two-layer neural network with ReLU activation followed by a softmax output.  
- Visualized model summary and generated architecture plots using `plot_model`.  
- Evaluated generalization performance using synthetic test data.  
- Extended the model with Dropout regularization to reduce overfitting and improve loss stability.

---

## Dependencies

```bash
pip install tensorflow==2.16.2
pip install graphviz pydot numpy matplotlib
````

---

## License

This project is licensed under the MIT License.

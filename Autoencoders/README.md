### MNIST Autoencoder Built with:

* **Python** for model logic and data handling
* **TensorFlow** and **Keras** for building and training neural networks
* **NumPy** for numerical operations
* **Matplotlib** for visualization

---

# Building an Autoencoder on MNIST

This project implements a deep learning autoencoder for compressing and reconstructing MNIST digits. The goal is to explore unsupervised learning techniques such as dimensionality reduction, denoising, and regularization using a fully connected autoencoder architecture.

### **Key Insights:**

* Built an encoder-bottleneck-decoder structure for learning compressed representations of handwritten digits.
* Evaluated impact of different bottleneck (latent space) sizes on reconstruction quality.
* Trained denoising autoencoders using noisy input images to learn robust latent features.
* Applied **L2 regularization** to improve generalization and reduce overfitting.
* Visualized original vs reconstructed images and plotted encoded features in 2D latent space.

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib
```

---

## License

This project is licensed under the MIT License.


### MNIST Digit Generation with GANs built with:

* **Python** for backend logic and training routines
* **TensorFlow/Keras** for deep learning (**Sequential API**, **custom training loop**)
* **NumPy** for data manipulation and random vector generation
* **Matplotlib** for visualizing generated images and loss curves

---

# Handwritten Digit Generation using GAN (MNIST)

This project implements a **Generative Adversarial Network (GAN)** to synthesize realistic images of handwritten digits using the MNIST dataset. It includes a generator network to produce fake images and a discriminator network to distinguish real from fake. The adversarial training setup leads to progressively improved digit generation.

### **Key Insights:**

* The generator starts from a 100-dimensional noise vector and learns to create 28×28 grayscale digits.
* The discriminator learns to identify real MNIST images from generator output, with accuracy improving over epochs.
* Initially, discriminator accuracy is low, but improves as both networks stabilize.
* Generator uses `LeakyReLU` activations and `BatchNormalization` to avoid vanishing gradients and improve training dynamics.
* Visual inspection of generated images shows gradual quality improvement, demonstrating GAN learning capability.

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib
```

---

## License

This project is licensed under the MIT License.

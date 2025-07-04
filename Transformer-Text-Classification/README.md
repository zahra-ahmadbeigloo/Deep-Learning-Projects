### Transformer-based Text Classification built with:  
- **Python** for preprocessing and data handling  
- **TensorFlow/Keras** for model architecture and training  
- **Custom Transformer implementation** including Multi-Head Attention and Positional Encoding  
- **TextVectorization layer** for tokenizing and embedding raw text  
- **Matplotlib** for training visualization  

---

# Transformer-based Text Classification (Keras)

This project implements a **Transformer model from scratch** using **TensorFlow/Keras** for the task of **text classification**. The model classifies news headlines into one of four predefined categories. All core Transformer components — such as **multi-head attention**, **positional encoding**, and **feedforward blocks** — are custom-implemented. The model is trained on a small labeled text dataset to demonstrate the use of Transformers beyond NLP generation, focusing on **sentence-level understanding** for classification tasks.

---

### **Key Insights:**  
- Built a full **Transformer encoder** architecture manually using Keras layers.  
- Used `TextVectorization` for tokenizing and embedding raw headlines.  
- Achieved ~85% accuracy on the validation set after training.  
- Demonstrated the effectiveness of Transformers for **supervised NLP tasks** like classification, not just text generation.  
- Visualization confirmed stable training and improved accuracy across epochs.

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib
```
---

## License

This project is licensed under the MIT License.

### Breast Cancer Classification built with:

- **Framework**: PyTorch
- **Libraries**: Scikit-learn, pandas, numpy, matplotlib, torch, ucimlrepo
- **Datasets**:
  - UCI ML Breast Cancer Wisconsin Diagnostic
  - Scikit-learn Iris dataset
 
--- 
# Breast Cancer Classification with Feedforward Neural Network

This project demonstrates binary and multi-class classification using fully connected deep neural networks in PyTorch. It includes two datasets:
- Breast Cancer Wisconsin (Diagnostic) dataset for binary classification (Malignant vs. Benign)
- Iris dataset for 3-class classification (Setosa, Versicolor, Virginica)

Both models are built from scratch using PyTorch’s `nn.Module` and trained with different optimizers, neuron sizes, and architectures to observe performance differences.

---

### Project Description

#### 🧪 Breast Cancer Classification:
- Binary classification (B = 0, M = 1)
- Balanced dataset of 400 samples (200 B, 200 M)
- Train-test split with stratification
- Fully connected NN with:
  - Input: 30 features
  - Hidden Layer: 64 neurons (also tested 128)
  - Output Layer: 2 classes
- Compared results using:
  - Adam vs. SGD optimizers
  - Default vs. expanded hidden layers

#### Iris Classification:
- Multi-class classification (3 flower types)
- Input: 4 features
- Hidden layer: 128 neurons
- Output: 3 neurons with CrossEntropyLoss

Both models include:
- Batch training via `DataLoader`
- Training vs. Test loss visualization per epoch
- Observations on optimizer effect and architecture tuning

---

### Key Insights

- Adam optimizer converged faster on breast cancer dataset but SGD produced smoother training.
- Increasing hidden layer neurons (from 64 to 128) slightly improved performance.
- Balanced sampling avoided bias due to original dataset imbalance.
- The Iris dataset required more epochs to reach decent generalization due to 3-class nature.

---

### Dependencies

```bash
pip install torch==2.3.1 pandas==2.2.2 numpy==1.26.4 matplotlib==3.8.0 scikit-learn==1.5.0 ucimlrepo==0.0.7
````

---

### License

This project is released under the MIT License.

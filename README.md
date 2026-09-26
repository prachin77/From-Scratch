# 🚀 AI & Machine Learning From Scratch Series

Welcome to the **AI & Machine Learning From Scratch** series! This repository is dedicated to breaking down and building foundational Artificial Intelligence and Machine Learning models, algorithms, and neural networks from first principles.

Instead of treating modern frameworks like black boxes, this series explores how the math, algorithms, optimization routines, and backpropagation actually work under the hood using **pure Python, NumPy, and PyTorch fundamentals**.

---

## 📚 Repository Roadmap & Topics

| # | Topic | Notebook | Colab | Description | Tech Stack | Status |
|---|-------|----------|:-----:|-------------|------------|:------:|
| 1 | **Linear Regression** | [`NeuralNetwork/LinearRegression/`](NeuralNetwork/LinearRegression/) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prachin77/From-Scratch/blob/main/NeuralNetwork/LinearRegression/linear_nn.ipynb) | Single-variable linear regression predicting marks from study hours | PyTorch (`nn.Module`), Pandas, Matplotlib | ✅ Completed |
| 2 | **Neural Network from Scratch** | [`NeuralNetwork/numpy_mnist.ipynb`](NeuralNetwork/numpy_mnist.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prachin77/From-Scratch/blob/main/NeuralNetwork/numpy_mnist.ipynb) | Multi-class digit classification on the MNIST dataset | Pure NumPy, Math & Linear Algebra | ✅ Completed |
| 3 | **Logistic Regression** | `Coming Soon` | — | Binary and multiclass classification with sigmoid & cross-entropy loss | NumPy / PyTorch | ⏳ In Progress |
| 4 | **Multi-Layer Perceptron (MLP)** | `Coming Soon` | — | Fully-connected deep neural networks with activation functions & backpropagation | NumPy / PyTorch | 📅 Planned |
| 5 | **Optimizers From Scratch** | `Coming Soon` | — | Implementing Gradient Descent, Momentum, RMSprop, and Adam | Pure Python & NumPy | 📅 Planned |
| 6 | **Convolutional Neural Networks (CNN)** | `Coming Soon` | — | Convolutions, pooling, feature maps, and computer vision classification | PyTorch | 📅 Planned |
| 7 | **Transformers & Attention** | `Coming Soon` | — | Self-attention mechanism, Multi-head attention, and Encoder-Decoder architecture | PyTorch | 📅 Planned |

---

## 🛠️ Getting Started

### 1. Prerequisites
Make sure you have **Python 3.10+** installed on your system.

### 2. Clone the Repository
```bash
git clone https://github.com/prachin77/From-Scratch.git
cd From-Scratch
```

### 3. Set Up a Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies
```bash
pip install torch numpy pandas matplotlib scikit-learn jupyter
```

### 5. Launch Jupyter Lab / Notebook
```bash
jupyter notebook
```
Navigate to any notebook (e.g. `NeuralNetwork/LinearRegression/linear_nn.ipynb`) and run the cells interactively!

---

## 🤝 How to Engage & Contribute

Community contributions and discussions are welcome! Whether you are catching a typo, implementing a new algorithm, optimizing a function, or suggesting a topic:

### 💬 GitHub Discussions
* Have a question about how backpropagation or gradient descent works?
* Want to suggest the next topic or model to implement?
* Head over to the **Discussions** tab to share ideas, ask questions, and learn together.

### 🐛 Reporting Issues
* If you find a bug, mathematical inaccuracy, or broken link:
  1. Go to the **Issues** tab.
  2. Click **New Issue**.
  3. Provide a clear description of the problem, code snippet, and steps to reproduce.

### 🔀 Contributing via Pull Requests (PRs)
1. **Fork** this repository to your GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/prachin77/From-Scratch.git
   ```
3. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature/topic-name-or-fix
   ```
4. **Make your changes**:
   * Keep notebooks clean and well-commented.
   * Include mathematical intuition and markdown explanations where appropriate.
   * Ensure any heavy datasets or raw files are added to `.gitignore`.
5. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add: [Topic/Algorithm] implementation from scratch"
   ```
6. **Push to your fork**:
   ```bash
   git push origin feature/topic-name-or-fix
   ```
7. Open a **Pull Request (PR)** against the `main` branch with a description of what you added or improved.

---

## 📄 License
This repository is open-source and available under the [MIT License](LICENSE).

---

⭐ **If you find this series helpful, consider giving it a star!**
